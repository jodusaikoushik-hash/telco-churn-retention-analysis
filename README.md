# 📉 Telco Customer Retention: A Strategic Deep Dive

**Workflow:** Python (cleaning & EDA) → Pandas (analysis) → Matplotlib/Seaborn (visualizations)

---

## 📋 The Business Problem

Customer churn is costing the business **$1.45M in annual recurring revenue.** 
My objective was to find where the "revenue leak" is happening, identify 
high-risk customer profiles, and recommend targeted retention strategies.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python | Data cleaning & exploratory analysis |
| Pandas | Data manipulation & feature engineering |
| Matplotlib & Seaborn | Visualizing churn drivers and trends |

---

## 📁 Dataset

- **Source:** [Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** 7,043 customers | 21 features
- **Fields:** Demographics, services, contract type, charges, churn status

---

## 🔍 Top 3 Discovery Insights

1. **The $1.45M Impact:** Churn isn't just a number — it's a major financial drain requiring strategic intervention
2. **Contract Type is Key:** Month-to-month customers are **~15x more likely** to leave than two-year contract customers
3. **The Fiber Optic Problem:** Fiber Optic users churn at **42%** — pointing to service quality or pricing issues

---

## 💡 Key Business Recommendation

**Highest-risk segment:** New customers (0–12 months tenure) on month-to-month 
contracts using Fiber Optic internet with monthly charges above $70.

Targeted retention actions:
- Improved onboarding experience for new customers
- Discounted long-term contract offers for month-to-month users
- Proactive support and pricing review for Fiber Optic customers

Could reduce overall churn by an estimated **15–20%**, recovering approximately 
**$217K–$290K in annual revenue.**

---

## 📂 Project Structure

```text
telco-churn-retention-analysis/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebook/
│   └── Churn_Analysis_Report.ipynb
└── README.md

---

## ▶️ How to Run

1. Clone this repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `notebook/Churn_Analysis_Report.ipynb` in Jupyter
4. Run all cells (Kernel → Restart & Run All)

---

## 👤 Author

**Sai Koushik Jodu** — Aspiring Data Analyst | SQL • Python • Power BI  
[LinkedIn](https://www.linkedin.com/in/jodusaikoushik) | [GitHub Portfolio](https://github.com/jodusaikoushik-hash)
