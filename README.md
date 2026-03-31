# 🏷️ AutoTriage: NLP-Powered GitHub Issue Priority Detection

> Automatically predict the priority of GitHub issues —
> high, medium, or low — using DistilBERT fine-tuned on
> 114,073 real GitHub issues.

## 🚧 Status
**In Progress — Phase 3: Exploratory Data Analysis**

## 📌 Problem
Open source maintainers and engineering leads spend 2-3 hours
daily manually triaging GitHub issues. This causes high priority
bugs to sit unnoticed for days, buried under low priority noise.
AutoTriage automates this using NLP — reducing triage time to
15-20 minutes and ensuring high priority issues are never buried.

## 🛠️ Tech Stack
- **Model:** DistilBERT (HuggingFace Transformers)
- **Dataset:** sharjeelyunus/github-issues-dataset (114,073 issues)
- **Platform:** Kaggle (Tesla T4 GPU)
- **Deployment:** Streamlit (coming soon)

## 📊 Results
🚧 Model training in progress — results will be added here

## 📓 Notebook
[View Phase 1 & 2 — Business Understanding & Problem Definition](https://github.com/jagdishkollur/autotriage-nlp/blob/main/autotriage-phase-1-2-business-understanding.ipynb)

## 🚀 Demo
🚧 Streamlit app coming soon

## 📁 Repository Structure
```
autotriage-nlp/
├── autotriage_phase1_phase2.ipynb  ← Phase 1 & 2 complete
├── README.md
└── .gitignore
```

---
*Metrics, confusion matrices, and live demo will be
added upon project completion.*
```

Commit with message:
```
docs: update README with proper notebook link and structure
