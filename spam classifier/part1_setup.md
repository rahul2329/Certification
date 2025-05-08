# Exploratory Data Analysis – Quick Setup Guide

Ensure Python 3 is installed by running `python` or `python3` in your terminal. If not, install it from [python.org](https://www.python.org/).

### Create a Virtual Environment

Choose one of the following methods to isolate your project environment:

* **Anaconda/Miniconda:**

  ```bash
  conda create --name forageenv python=3.9
  conda activate forageenv
  ```

* **venv (Standard Python):**

  ```bash
  python3 -m venv forageenv
  source forageenv/bin/activate
  ```

### 📦 Install Dependencies

Install required packages using:

```bash
pip3 install -r requirements.txt
```

### 🚀 Launch Jupyter Notebook

Start your notebook interface with:

```bash
jupyter notebook
```

---

