# chatbot_arena

Baseline solution for Kaggle competition:
LLM Classification Finetuning (Chatbot Arena preference prediction)

Competition page:
https://www.kaggle.com/competitions/llm-classification-finetuning

Leaderboard:
https://www.kaggle.com/competitions/llm-classification-finetuning/leaderboard

## Current Results

### DistilBERT

- Submission status: submitted
- Rank: 112 / 257
- Name: Jozef Makis
- Score: 1.04331
- Submissions: 5
- Last updated: 1d
- Model: DistilBERT notebook

### TF-IDF Baseline

- Submission status: submitted
- Rank: 168 / 263
- Model: TF-IDF + chi-square feature selection baseline

## Baseline Summary

- Text parsing from conversation turns (`prompt`, `response_a`, `response_b`)
- Multiple TF-IDF vocabularies (prompt + response blocks)
- Chi-square (`chi2`) feature selection
- Multiclass classifier for `model_a`, `model_b`, `tie`
- Submission file generated as `submission.csv`
