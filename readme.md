# AI-Assisted Credit Card Validator 💳

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![GitHub Copilot](https://img.shields.io/badge/AI-GitHub_Copilot-black?logo=github-copilot&logoColor=white)](https://github.com/features/copilot)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?logo=github-actions&logoColor=white)]()
[![Tests](https://img.shields.io/badge/Tests-Pytest-yellow?logo=pytest&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A robust credit card brand identifier developed to demonstrate **AI Pair Programming** efficiency. It features automated testing pipelines and code coverage analysis.

## 📋 Project Overview

This project was built to explore the capabilities of **GitHub Copilot** in a real-world coding scenario. The goal was to develop a logic that identifies credit card brands (Visa, Mastercard, Elo) based on input patterns.

Beyond the logic, this repository serves as a **DevOps & QA Lab**, demonstrating:
* **AI-Driven Development:** Leveraging LLMs to generate regex patterns and boilerplate.
* **Continuous Integration (CI):** Automatic testing on every push using GitHub Actions.
* **Quality Assurance:** Strict Unit Testing with `pytest` ensuring logic reliability.

## ✨ Key Features

* **🤖 AI-Generated Logic:** Core algorithms optimized using GitHub Copilot suggestions.
* **🔍 Brand Detection:** Identifies major card issuers:
    * Visa
    * Mastercard
    * Elo
* **🧪 Automated Testing:** Comprehensive test suite in `tests/test_core.py` ensuring zero regressions.
* **⚙️ CI/CD Pipeline:** A `.github/workflows/ci.yml` workflow that automatically runs tests and checks build integrity.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **AI Assistant:** GitHub Copilot
* **Testing:** Pytest
* **CI/CD:** GitHub Actions

## 📂 Project Structure

```text
ai-assisted-card-validator/
├── .github/workflows/   # CI Pipeline configuration (YAML)
├── docs/                # Documentation assets
├── tests/               # Unit tests (Pytest)
├── identificador_bandeira_cartao.py  # Core Logic Script
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```
🚀 How to Run
Clone the repository:

Bash
git clone [https://github.com/Fesisp/ai-assisted-card-validator.git](https://github.com/Fesisp/ai-assisted-card-validator.git)
cd ai-assisted-card-validator
Install dependencies:

Bash
pip install -r requirements.txt
Run the script (Manual Test):

Bash
python identificador_bandeira_cartao.py
Run Automated Tests:

Bash
pytest -v
👨‍💻 Author
Felipe Spinola

LinkedIn

Portfolio

This project demonstrates the synergy between Human Engineering and Artificial Intelligence.


---

### 3. O Arquivo `.gitignore` (Limpeza)

Você tem pastas de cache (`__pycache__`) e arquivos de cobertura (`.coverage`) que não devem ser versionados. Use este `.gitignore` para limpar a casa.

**Arquivo:** `.gitignore`

```text
# Python caches
__pycache__/
*.py[cod]
*$py.class

# Testing & Coverage
.coverage
htmlcov/
coverage.xml
.pytest_cache/

# Environment
.env
.venv/
venv/
env/

# IDEs
.vscode/
.idea/
```
# OS Files
.DS_Store
Thumbs.db
