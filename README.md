# CSI4142 — Assignment 1 (EDA) | Premier League & Championship

This repository contains my **Assignment 1** for **CSI4142 (Fundamentals of Data Science)**.  
The goal of this project is to perform **Exploratory Data Analysis (EDA)** and extract **evidence-based insights** using tables and visualizations.

---

## Project Overview

In this notebook, I analyze historical match data from:
- **English Premier League (EPL)**
- **EFL Championship**

I follow the assignment requirements (including the required analysis types often labeled **r1–r8**) and present **10 insights** supported by plots and summary tables.

---

## Dataset

- Original dataset on Kaggle: `panaaaaa/english-premier-league-and-championship-full-dataset`
- For reproducibility, the notebook loads CSVs directly from public raw links:
  - EPL: https://raw.githubusercontent.com/idxwze/CSI4142-A1-data/main/England%20CSV.csv  
  - Championship: https://raw.githubusercontent.com/idxwze/CSI4142-A1-data/main/England%202%20CSV.csv  

---

## What’s Inside

- Data loading (public URLs)
- Data quality checks (types, missing values, duplicates)
- Feature engineering (e.g., total goals, goal difference, season year, bins)
- **10 insights**, each with:
  - a one-sentence conclusion
  - supporting evidence (plots/tables)
  - a short interpretation
- Final conclusion + limitations + references

---

## Key Highlights (Examples)

- Most matches end with **2–3 total goals**; high-scoring games (6+ goals) are rare.
- **Home wins** are the most common outcome overall (home advantage effect).
- EPL matches are **slightly higher-scoring** than Championship matches on average.
- More shots generally relate to more goals, but the relationship is **weak-to-moderate** (efficiency matters).
- Season trends show noticeable fluctuations in scoring and home-win rates over time.

---

## How to Run

### 1) Clone the repository
```bash
git clone https://github.com/<your-username>/CSI4142-A1-EDA.git
cd CSI4142-A1-EDA
```

### 2) Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

### 3) Open the notebook
```bash
jupyter notebook
```
### 4) Reproduce results
In Jupyter: **Kernel → Restart & Run All**

---

## Tools Used
- Python
- Jupyter Notebook
- pandas, NumPy
- Matplotlib, Seaborn

---

## Notes
Some match statistics (shots, corners, cards, referee, etc.) have missing values, especially for older seasons.  
I handle this by filtering only the necessary rows for analyses that require those fields (**no artificial imputation**).

---

## Author
**Seifeddine Reguige**
