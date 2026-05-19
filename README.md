# 🧠 100 Days of ML — Rimsha's Learning Journal

> *"The best way to learn data science is to do data science — every single day."*

[![Days Completed](https://img.shields.io/badge/Days%20Completed-30%2B-blueviolet?style=for-the-badge)](.)
[![Language](https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python)](.)
[![Tools](https://img.shields.io/badge/Tools-Pandas%20%7C%20NumPy%20%7C%20Seaborn%20%7C%20Sklearn-blue?style=for-the-badge)](.)
[![Status](https://img.shields.io/badge/Status-Active%20%F0%9F%94%A5-brightgreen?style=for-the-badge)](.)

---

## 👩‍💻 About This Repository

This is my **public learning journal** — a daily commitment to becoming a better data scientist.

Every notebook here represents a real session where I picked a concept, got my hands dirty with actual data, and built something I could look back on. No copy-paste tutorials. No shortcuts. Just consistent, hands-on practice.

**Who is this for?**
- Beginners looking for reference implementations
- Anyone doing their own #100DaysOfML challenge
- Recruiters who want to see *how* someone learns, not just what they claim to know

---

## 📂 Repository Structure

```
100-days-of-ml/
│
├── 📊 eda/
│   ├── EDA_housing_data.ipynb          # Full EDA on California Housing dataset
│   ├── univariate_analysis.ipynb       # Distributions, histograms, box plots
│   ├── bivariate_analysis.ipynb        # Correlation, scatter plots, heatmaps
│   └── pandas_profiling.ipynb          # Automated EDA reports
│
├── ⚙️ preprocessing/
│   ├── feature_scaling_standardization.ipynb   # StandardScaler on Social Network Ads
│   ├── normalization_wine_data.ipynb            # MinMaxScaler on Wine dataset
│   └── feature_engineering.ipynb               # Creating & transforming features
│
├── 🌐 data-collection/
│   ├── API_movies_data.ipynb           # Fetching & parsing movie data from API
│   ├── working_with_API.ipynb          # REST API fundamentals with Python
│   └── web_scraping.ipynb              # BeautifulSoup scraping pipeline
│
├── 🗄️ data-handling/
│   ├── working_with_csv.ipynb          # CSV read/write/manipulation tricks
│   ├── working_JSON_SQL.ipynb          # JSON parsing + SQL queries in Python
│   └── csv_files_working.ipynb         # Advanced CSV operations
│
└── 📋 README.md
```

---

## 🗂️ Notebooks at a Glance

| # | Notebook | Concept | Dataset | Key Skills |
|---|----------|---------|---------|------------|
| 01 | `univariate_analysis.ipynb` | Statistical analysis of single variables | Various | Histograms, KDE, Box plots |
| 02 | `bivariate_analysis.ipynb` | Relationships between two variables | Various | Correlation, Scatter plots |
| 03 | `EDA_housing_data.ipynb` | Full exploratory data analysis | California Housing | Pandas, Seaborn, Matplotlib |
| 04 | `pandas_profiling.ipynb` | Automated EDA reports | Various | ydata-profiling |
| 05 | `feature_scaling_standardization.ipynb` | Standardization | Social Network Ads | StandardScaler, Sklearn |
| 06 | `normalization_wine_data.ipynb` | Normalization | Wine Dataset | MinMaxScaler |
| 07 | `feature_engineering.ipynb` | Creating new features | Various | Pandas transformations |
| 08 | `API_movies_data.ipynb` | Fetching data from REST APIs | Movies API | Requests, JSON |
| 09 | `web_scraping.ipynb` | Web scraping pipeline | Live web data | BeautifulSoup |
| 10 | `working_JSON_SQL.ipynb` | Working with JSON & SQL | Various | sqlite3, json module |

---

## 🛠️ Tech Stack

```python
# Core
import pandas as pd
import numpy as np

# Visualization
import matplotlib.pyplot as plt
import seaborn as sns

# Machine Learning
from sklearn.preprocessing import StandardScaler, MinMaxScaler

# Data Collection
import requests
from bs4 import BeautifulSoup

# Profiling
from ydata_profiling import ProfileReport
```

---

## 🚀 How to Run These Notebooks

### 1. Clone the repository
```bash
git clone https://github.com/rimsha-deve/100-days-of-ml.git
cd 100-days-of-ml
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests beautifulsoup4 ydata-profiling
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

### 4. Navigate to any folder and open a notebook ✅

---


## 🔗 Connect With Me

If you're also doing #100DaysOfML, let's connect and hold each other accountable!

[![GitHub](https://img.shields.io/badge/GitHub-rimsha--deve-black?style=flat-square&logo=github)](https://github.com/rimsha-deve)

---

## ⭐ If This Helped You

Give this repo a star — it helps other learners find it and keeps me motivated to keep pushing notebooks every day!

---

*Started: 2025 | Status: Ongoing 🔥*
