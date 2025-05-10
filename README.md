# Frequentist Inference Case Study - Part A

This project explores core concepts in frequentist statistics, including confidence intervals and hypothesis testing. It was developed as part of Springboard's Data Science Career Track.

## 📘 Overview

Using simulated population data, we:

- Estimate population parameters from samples
- Calculate 95% confidence intervals using both z- and t-distributions
- Identify when it’s inappropriate to use the z-distribution
- Perform a one-sample t-test to determine statistical significance

## 🔍 Key Questions Answered

- **Q15**: Estimate population mean using a sample of size 50  
- **Q16**: Why using the z-distribution is incorrect when σ is unknown  
- **Q17**: Compute correct confidence interval using the t-distribution
- 
# 📘 Frequentist Inference Case Study – Part B

This notebook applies frequentist statistical inference to a real-world dataset (`insurance2.csv`) to explore differences in medical charges.

---

## 🔍 Objective:
Use statistical tests to determine whether:
- The average charge has dropped below a critical threshold
- People with insurance are charged more than those without

---

## ✅ Topics Covered:

- Visualizing skewed real-world data
- Applying the Central Limit Theorem (CLT) to justify t-tests
- Calculating one-sided and two-sided confidence intervals
- Performing hypothesis testing using `scipy.stats.ttest_ind`
- Interpreting p-values and rejecting or retaining null hypotheses

---

## 📊 Statistical Concepts Applied:

- **One-sample t-test** to compare average charge against a fixed value
- **Two-sample t-test** to compare insured vs. uninsured groups
- **Manual and automated calculations** of t-statistics and p-values
- Forming null and alternative hypotheses and drawing conclusions

---

## 🧪 Key Findings:

- The average charge was **well above** \$12,000 — no business concern
- There is a **statistically significant difference** in charges:
  > Insured individuals are charged significantly more than uninsured individuals  
  > (t ≈ 11.89, p ≈ 0.0000)

---

## 📦 Tools:
- Python
- NumPy, pandas
- SciPy (`ttest_ind`, `norm.cdf`)
- Matplotlib



## 📂 Files

- `confidence_interval_analysis.ipynb`: Final cleaned notebook for Q14–Q17
- `Frequentist Inference Case Study - Part A (3).ipynb`: Raw/working notebook
- `insurance2.csv`: Sample dataset for other exercises
- `Frequentist Inference Case Study - Part B (2).ipynb`: (optional Part B content)

## 🧪 Tools Used

- Python 3.10+
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## ✅ Status

This analysis focuses on simulation-based inference and lays a foundation for more advanced statistical modeling.

## 👤 Author

Mesfin Kebede  
[GitHub Profile](https://github.com/mesfin-k)
