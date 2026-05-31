# Exploratory Data Analysis Assignment

**Student:** Mani Dixit | **Batch:** PGDSAI3 | **Institute:** HeroVired

---

## 📓 View the Notebook

👉 **[Click here to view the rendered notebook on NBViewer](https://nbviewer.org/github/manidixit16/Exploratory-Data-Analysis-Assignment/blob/main/notebooks/Mani_Dixit_PGDSAI3.ipynb)**

> *GitHub sometimes has issues rendering large `.ipynb` files. Use the NBViewer link above for the best viewing experience.*

---

## Repository Structure

```
Exploratory-Data-Analysis-Assignment/
├── notebooks/
│   ├── Mani_Dixit_PGDSAI3.ipynb   ← Main submission notebook
│   └── *.png                       ← Generated plot images
├── data/
│   └── raw/
│       └── superstore.csv          ← Source dataset
├── requirements.txt
└── README.md
```

## Assignment Coverage

| Section | Topics |
|---|---|
| Q1 | Data Cleaning — missing values, duplicates, unknown columns, dtypes |
| Q2 | Univariate Analysis — Numerical Features (distributions, skewness, outliers) |
| Q3 | Univariate Analysis — Categorical Features (cardinality, balance, geographic bias) |
| Q4 | Bivariate Analysis — Numerical vs Numerical (correlations, profit drivers, time trends) |
| Q5 | Bivariate Analysis — Categorical vs Numerical (profit/sales by category & segment) |
| Q6 | Bivariate Analysis — Market vs Region, Category, Country |

## How to Run Locally

```bash
pip install -r requirements.txt
cd notebooks
jupyter notebook Mani_Dixit_PGDSAI3.ipynb
```

The notebook reads data from `../data/raw/superstore.csv`.
