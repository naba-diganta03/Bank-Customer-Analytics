# Banking Data Analysis

A comprehensive data analysis and visualization project on banking customer data using **Python (EDA)** and **Power BI (Dashboard)** to uncover customer patterns, account relationships, and business insights.

---

## Project Structure

- `BankEDA.ipynb`: Exploratory Data Analysis in Python.
- `Banking Dashboard.pbix`: Interactive Power BI Dashboard.
- `Banking.csv`: (Assumed) raw dataset used in the analysis.

---

## Problem Statement

The goal is to analyze customer financial behavior, product holdings, and account correlations in order to:

- Understand income and product distribution.
- Identify high-value customers.
- Suggest opportunities for cross-selling and better risk management.

---

## Exploratory Data Analysis (Python)

EDA was performed using:
- **Pandas, NumPy** for data manipulation
- **Matplotlib, Seaborn** for visualization

### Key Insights from EDA:

- **Income Band Analysis**: Most customers fall under the Medium income category.
- **Account Correlation**: Strong positive correlation between Bank Deposits, Checking, Saving, and Foreign Currency accounts.
- **Skewed Distributions**: Many financial features (e.g., Loans, Income, Business Lending) are right-skewed, indicating a small group of high-value customers.
- **Risk vs Income**: Low-income customers tend to have higher risk weights.
- **Occupation Trends**: Certain professions correlate with better loyalty scores and diversified account holdings.

*For full insights, see the last section of the Jupyter Notebook.*

---

## Power BI Dashboard

The `.pbix` file provides a clean, interactive view of:
- **Income Band Distributions**
- **Account-Wise Comparisons**
- **Branch & Occupation Analysis**
- **High/Low Risk Segmentation**
- **Loyalty Classification Visualizations**

### Business Use-Cases:
- Identify customers for **cross-selling**.
- Target **specific occupations/income segments**.
- Use data-driven decisions for **risk mitigation** and **portfolio expansion**.

---

## Tools & Technologies

| Tool         | Purpose                        |
|--------------|--------------------------------|
| Python       | Data preprocessing & EDA       |
| Pandas/Numpy | Data wrangling                 |
| Seaborn      | Statistical visualization      |
| Power BI     | Dashboard creation             |
| GitHub       | Version control (optional)     |

---

## How to Use

1. Clone the repository or download the files.
2. Open the Jupyter Notebook `BankEDA.ipynb` to explore data insights.
3. Launch `Banking Dashboard.pbix` in Power BI Desktop to explore interactive visuals.

---

## Future Scope

- Add predictive modeling (e.g., churn or credit risk).
- Integrate live data pipelines (ETL + scheduled dashboards).
- Embed Power BI dashboard to a web application or portal.

---

## Contact

For queries or collaboration: **Nabadiganta Acharjee**  
Mail: acharjeenabadiganta3456@gmail.com  

---
