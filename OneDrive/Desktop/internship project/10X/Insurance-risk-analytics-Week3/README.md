
# 🚗 Insurance Risk Analysis

This repository contains code and analysis for the **End-to-End Insurance Risk Analytics & Predictive Modeling** challenge by 10 Academy.

---

## 📌 Project Overview

- **Goal**: Analyze historical car insurance claim data to identify low-risk clients and optimize premiums.
- **Company**: AlphaCare Insurance Solutions (ACIS)
- **Scope**: South African insurance data from Feb 2014 to Aug 2015.
- **Key Outputs**:
  - Insightful EDA and risk segmentation
  - A/B testing for key features like location and gender
  - Predictive modeling for claim amount and premium optimization

---

## 🗂️ Tasks Breakdown

- **Task 1**: GitHub Setup & EDA
- **Task 2**: Data Version Control with DVC
- **Task 3**: A/B Hypothesis Testing
- **Task 4**: Statistical & Machine Learning Modeling

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Seaborn, Scikit-learn, XGBoost)
- Jupyter Notebooks
- Git + GitHub
- DVC (Data Version Control)
- GitHub Actions (CI/CD)
- SHAP for model interpretability

---

## 📁 Folder Structure


Created structure:
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── unittests.yml
├── .gitignore
├── requirements.txt
├── pyproject.toml
├── README.md
├── Makefile
├── .env
├── src/
│   ├── __init__.py
│   ├── core/
│   ├── models/
│   ├── utils/
│   └── services/
├── tests/
│   ├── __init__.py
│   ├── unit/
│   └── integration/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── scripts/
│   ├── __init__.py
│   └── README.md
├── docs/
│   └── README.md
├── data/
│   └── README.md
├── config/
│   ├── __init__.py
│   └── settings.py
└── examples/
    ├── __init__.py
    └── README.md


---

## 🚀 Getting Started

1. Clone this repository:
2. Install Python dependencies:
3. Start exploring notebooks in the `notebooks/` directory.

---

## 🧪 GitHub Actions (CI/CD)

A simple GitHub Actions workflow runs on every push to validate the setup.  
Workflow file: `.github/workflows/python-app.yml`

```yaml
name: CI Pipeline

on: [push, pull_request]

jobs:
build:
 runs-on: ubuntu-latest

 steps:
   - uses: actions/checkout@v3

   - name: Set up Python
     uses: actions/setup-python@v4
     with:
       python-version: '3.10'

   - name: Install dependencies
     run: |
       pip install -r requirements.txt

   - name: Run tests
     run: |
       echo "Tests coming soon!"

🧑‍💻 Author
Barkilign Mulatu

Data Analytics Fellow - 10 Academy

| Milestone        | Date         |
| ---------------- | ------------ |
| Start            | 11 June 2025 |
| Interim Report   | 15 June 2025 |
| Final Submission | 17 June 2025 |

git add README.md
   git commit -m "Finalize README with project structure and CI setup"
   git push origin task-1
