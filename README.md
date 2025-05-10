# 📊 Frequentist Inference Case Study

This project explores foundational concepts in **frequentist statistics** using both simulated and real-world data. It was developed as part of Springboard’s Data Science Career Track.

---

## 📁 Part A – Simulated Population Analysis (Heights)

Using synthetic height data generated from a normal distribution, this notebook demonstrates:

- Estimating population parameters from samples
- Applying the Central Limit Theorem (CLT)
- Calculating 95% confidence intervals using **z** and **t distributions**
- Performing a **one-sample t-test** for hypothesis testing
- Understanding when it is **inappropriate to use a z-test**

### 🔍 Key Questions Answered

- **Q15**: Estimate the population mean from a sample of size 50
- **Q16**: Why the **z-distribution** is invalid when σ is unknown
- **Q17**: Correct confidence interval using the **t-distribution**

---

## 📁 Part B – Real-World Data Inference (Medical Charges)

This notebook analyzes real data (`insurance2.csv`) to explore whether:

- The average medical charge has dropped below a critical threshold
- **Insured individuals** are charged **more** than those without insurance

### ✅ Topics Covered

- Visualizing skewed real-world data
- Justifying the use of the CLT to apply t-tests
- Calculating **one-sided** and **two-sided** confidence intervals
- Performing **one-sample** and **two-sample t-tests**
- Interpreting **p-values** and drawing conclusions from results

### 🧪 Key Findings

- The average charge was **well above** \$12,000 → no concern
- There is a **statistically significant** difference in charges:
  > Insured individuals are charged **significantly more**  
  > (t ≈ 11.89, p ≈ 0.0000)

---

## 📦 Tools Used

- Python 3.10+
- NumPy
- pandas
- SciPy (`ttest_ind`, `norm.cdf`)
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Files

- `Frequentist Inference Case Study - Part A (3).ipynb`: Simulated analysis (heights)
- `Frequentist Inference Case Study - Part B (2).ipynb`: Real-world data analysis (charges)
- `insurance2.csv`: Dataset used in Part B
- `confidence_interval_analysis.ipynb`: (optional notebook for Q14–Q17 deep dive)

---

## ✅ Status

This case study demonstrates simulation-based inference techniques and lays the groundwork for more advanced statistical modeling and real-world decision-making.

---

## 👤 Author

**Mesfin Kebede**  
[GitHub Profile](https://github.com/mesfin-k)
