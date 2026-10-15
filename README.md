# Basic CI Workflow Demo (Experiment 2)

**Course:** DevOps Lab (MCA Semester 5)  
**Institution:** CHRIST (Deemed to be University)  
**Student:** Vishal Singh (Reg No: 25225028)  
**GitHub:** [Vishal-Singh27](https://github.com/Vishal-Singh27)

---

## 📌 Project Overview
This repository implements a Continuous Integration (CI) automated workflow using **GitHub Actions**. Whenever a developer commits or pushes code changes to the `main` branch or opens a Pull Request targeting `main`, GitHub Actions automatically initializes a virtual runner (`ubuntu-latest`), configures Python 3.x, and executes automated unit tests using the Python `unittest` framework.

## 🛠 Project Structure
```text
basic-ci-project/
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitlab-ci.yml
├── app.py
├── test_app.py
└── README.md
```

## 🚀 Running Tests Locally
```bash
python3 -m unittest -v
```

## ⚙️ CI Pipeline Configuration
The workflow triggers on:
- `push` to branch `main`
- `pull_request` to branch `main`
