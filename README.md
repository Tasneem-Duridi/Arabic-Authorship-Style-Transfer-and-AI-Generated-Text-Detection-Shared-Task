# Arabic AI-Generated News Detection — ARATECT 4.3 (Subtask 3)

**Official implementation of the PTUK-HULAT system** for detecting AI-generated Arabic news articles, developed for the [ARATECT 4.3 Shared Task](https://github.com/ARATECT) (Subtask 3: ArabicNewsGen).  
Our system ranked **4th** on the official leaderboard with an **F1-score of 0.78** on the test set.

---

## 📄 Overview
The authenticity of digital content is increasingly challenged by the rise of generative AI tools.  
This repository contains the code, training scripts, and evaluation pipeline for detecting **machine-generated Arabic news text** using multilingual transformer models, specifically **XLM-RoBERTa-base** and **XLM-RoBERTa-large**.

---

## 🏆 Competition Details
- **Task**: Arabic News Text Detection (ArabicNewsGen) — classify Arabic news articles/passages as **Human-written** or **AI-generated**.
- **Dataset**: Provided by ARATECT, covering domains such as politics, economics, technology, and sports.
- **Evaluation metrics**: F1-score (primary), Accuracy (secondary).
- **Ranking**: 4th place in Subtask 3.

---

## 📊 Results Summary

| Model                  | F1-score | Precision | Recall | Accuracy |
|------------------------|----------|-----------|--------|----------|
| XLM-RoBERTa-large (dev)| 0.9272   | 0.8897    | 0.9680 | 0.9240   |
| XLM-RoBERTa-base (test)| 0.7800   | 0.7260    | 0.8480 | 0.7640   |


---

## 🛠 Requirements

```bash
python>=3.9
torch>=2.0.0
transformers>=4.40.0
scikit-learn>=1.3.0
accelerate>=0.29.0
pandas
numpy
