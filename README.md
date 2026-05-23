# Exploratory Data Analysis Assignment

**Dataset:** Superstore Global Sales Data (~51,290 rows)  
**Assignment:** HeroVired / HeroX — EDA Graded Assignment  
**Submitted by:** Mani Dixit

## Structure

| File | Description |
|---|---|
| `Mani_Dixit_EDA.ipynb` | Main Jupyter notebook with all Q1–Q6 analysis |
| `superstore.csv` | Source dataset |

## Questions Covered

- **Q1:** Data Cleaning (missing values, duplicates, unknown columns, dtypes)
- **Q2:** Univariate Analysis — Numerical Features
- **Q3:** Univariate Analysis — Categorical Features
- **Q4:** Bivariate Analysis — Numerical vs Numerical
- **Q5:** Bivariate Analysis — Categorical vs Numerical
- **Q6:** Bivariate Analysis — Market vs Region, Category, Country

## Key Findings

- Dataset has 8 missing rows and 1 unknown column (`记录数`) — both handled in Q1
- Sales, Profit, and Shipping Cost are heavily right-skewed with significant outliers
- Discount is the strongest negative driver of Profit (r = -0.32)
- Technology category yields highest median sales AND profit
- APAC and EU markets are the most profitable despite US having the most orders
