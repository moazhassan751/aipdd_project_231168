\# AI Project Design and Development: Lab 01



\*\*Course:\*\* AI Project Design and Development (AI-316)

\*\*University:\*\* Air University Islamabad

\*\*Lab Instructor:\*\* Farhan Zafar

\*\*Student:\*\* Moaz Hassan Khan Manj (Roll No. 231168)



\## Description

This repository contains my work for \*\*Lab 01: Foundations of AI Engineering \& Project Setup\*\*. It covers setting up a clean, production-ready AI project from scratch.



\## Lab Tasks

1\. \*\*Repository structure:\*\* standard folders and a `.gitignore` for Python, Jupyter, virtual environments, and model weights

2\. \*\*Virtual environment:\*\* `aipdd\_env` with numpy, opencv-python, matplotlib, ultralytics, and jupyter, with pinned versions in `requirements.txt`

3\. \*\*Git workflow:\*\* initial commit, `feature/lab01-setup` branch, and merge into `main`

4\. \*\*Jupyter setup:\*\* notebook using the `aipdd\_env` kernel, printing package versions

5\. \*\*Documentation:\*\* project specification written in Markdown inside the notebook



\## Project Structure

```

aipdd\_project\_231168/

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



\## How to Run

```bash

python -m venv aipdd\_env

aipdd\_env\\Scripts\\activate

pip install -r requirements.txt

jupyter notebook

```

Then open the notebook in the `notebooks/` folder.

