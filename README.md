# Medical LLM Hallucination Detection

**Project:** Reducing Hallucinations in Medical Large Language Models Using Retrieval-Augmented Verification and Confidence Scoring

## Summary
This project builds a system that queries a Large Language Model (LLM) on medical questions, retrieves supporting evidence from medical literature (PubMed), and computes a confidence score that helps detect hallucinated (incorrect) answers. The goal is to reduce hallucination rate and provide explainable confidence measures.

## Repo structure
- `data/` — dataset download & preprocessing scripts  
- `notebooks/` — Colab notebooks: baseline_model, retrieval_model, evaluation  
- `baseline/` — baseline inference code (LLM)  
- `improved/` — retrieval + confidence scoring code  
- `experiments/` — logs, plots, evaluation tables  
- `requirements.txt` — Python dependencies

## Quick start (Colab)
1. Open `notebooks/baseline_model.ipynb` in Google Colab.  
2. Run cells to install requirements and load the PubMedQA dataset.


