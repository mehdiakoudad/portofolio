# 🛒 Supermarket Transaction Analysis in SQL & Python

**Date:** March 14, 2023  
**Dataset:** [Polish Supermarket Transactions](https://www.mdpi.com/2306-5729/4/2/67/htm)  
**Tools:** SQL, Python (Pandas, Matplotlib, nbconvert)

---

## 📖 Project Overview
This project analyzes supermarket point-of-sale (POS) transaction data to extract **business and operational insights**.  
It answers key questions about:

- **Payment method trends** (card vs cash)  
- **Average spend per transaction** by payment type  
- **Impact of Sunday trading restrictions** in Poland  
- **Daily sales trends** and peak periods  
- **Staffing optimization opportunities**

The analysis blends **SQL** for data extraction with **Python** for visualization and storytelling, making it a complete retail analytics case study.

---

## 📊 Key Insights

1. **Card transactions dominate** slightly over cash, and card users spend more per transaction.  
   → Focus on card terminal reliability, card-linked promotions, and high-value customer targeting.

2. **Sunday closures** have **no negative impact** on weekly revenue — shoppers simply shift purchases to Friday/Saturday.  
   → Opportunity to save on labor and operational costs by closing on Sundays or shortening Sunday hours.

3. **Thursday–Saturday** are peak sales days: +25% more transactions and +40% more revenue compared to early-week.  
   → Adjust staffing, inventory, and promotions to align with peak patterns.

4. On open Sundays, **18–20 operators** are scheduled.  
   → Reallocating them to peak days could improve throughput or cut labor costs.

---

## 📂 Repository Structure

```
supermarket-transaction-analysis-sql/
│
├── data/                             # Optional: Sample anonymized dataset or schema
│   └── README.md                     # Dataset description & link
│
├── notebooks/
│   ├── supermarket_transaction_analysis_storytelling_with_summary.ipynb  # Final version w/ Executive Summary
│   └── supermarket_transaction_analysis_storytelling.ipynb                # Version w/ embedded stories
│
├── reports/
│   ├── supermarket_transaction_analysis.pdf   # Business-friendly PDF (optional)
│   └── visuals/                               # Exported charts/images
│
├── scripts/                                   # SQL queries or Python scripts if separated from notebook
│
├── README.md
└── LICENSE                                    # (Optional) License file
```

---

## ⚙️ How to Run

1. **Clone this repository:**
```bash
git clone https://github.com/your-username/supermarket-transaction-analysis-sql.git
cd supermarket-transaction-analysis-sql
```

2. **Open the notebook:**
```bash
jupyter notebook notebooks/supermarket_transaction_analysis_storytelling_with_summary.ipynb
```

3. **Run all cells** to reproduce the analysis.  
   Ensure you have Python 3.x, Jupyter, Pandas, and Matplotlib installed.

---

## 📷 Example Visuals

### 1. Payment Method Mix
Shows the proportion of card vs cash transactions, highlighting card's dominance and its higher average ticket.

### 2. Daily Sales Patterns
Reveals peak shopping days (Thu–Sat) and lowest traffic on Sundays.

### 3. Sunday Trading Impact
Compares revenue for weeks with and without Sunday trading, showing no loss in total sales.

*(You can export charts to `reports/visuals/` for embedding in this README.)*

---

## 📄 Executive Summary

This analysis provides **actionable recommendations** for supermarket operations:

- **Labor Allocation**: Shift Sunday staff to peak days to reduce costs or increase throughput.  
- **Checkout Optimization**: Invest in card payment infrastructure and reduce reliance on cash lanes.  
- **Marketing Strategy**: Target high-value card users with basket-expansion offers.  
- **Inventory Planning**: Stock up before peak days and consider “Sunday-closed packs” for pre-closure shopping surges.

---

## 📜 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙋 Author
**Your Name**  
[LinkedIn](https://www.linkedin.com/) • [Portfolio](https://github.com/your-username)
