# AI Project Design and Development: Lab 01

**Course:** AI Project Design and Development (AI-316)
**University:** Air University Islamabad
**Lab Instructor:** Farhan Zafar
**Student:** Moaz Hassan Khan Manj (Roll No. 231168)

## Description

This repository contains my work for **Lab 01: Foundations of AI Engineering & Project Setup**. It covers setting up a clean, production-ready AI project from scratch.

## Lab Tasks

1. **Repository Structure:** Standard folders and a `.gitignore` for Python, Jupyter, virtual environments, and model weights.
2. **Virtual Environment:** `aipdd_env` with NumPy, OpenCV, Matplotlib, Ultralytics, and Jupyter, with pinned versions in `requirements.txt`.
3. **Git Workflow:** Initial commit, `feature/lab01-setup` branch, and merge into `main`.
4. **Jupyter Setup:** Notebook using the `aipdd_env` kernel and printing package versions.
5. **Documentation:** Project specification written in Markdown inside the notebook.

## Project Structure

```text
aipdd_project_231168/
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── notebooks/
├── src/
├── configs/
├── logs/
├── .gitignore
├── requirements.txt
└── README.md
```

## How to Run

### 1. Create a Virtual Environment

```bash
python -m venv aipdd_env
```

### 2. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\aipdd_env\Scripts\Activate.ps1
```

**Windows CMD:**

```cmd
aipdd_env\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open the notebook from the `notebooks/` folder.

