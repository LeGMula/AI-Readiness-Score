# AI Readiness Score - Retail Sector Analysis  

## Overview  
This repository introduces the **AI Readiness Score**, a quantitative model designed to predict a company's AI adoption potential based on publicly available financial and operational data. The model aims to classify companies into:
- **AI Leaders**: Companies successfully leveraging AI for operational efficiency.
- **Turnaround Opportunities**: Companies with high potential but not yet fully utilizing AI.
- **AI Laggards**: Companies with limited potential for AI-driven transformation.

## Key Features  
✅ **Data-Driven Classification:** Uses **10 years of financial data (2014-2024)** from the retail sector to predict AI readiness.  
✅ **Custom AI Readiness Model:** Leverages **logistic regression & financial metrics** to classify companies.  
✅ **Publicly Available Data:** Built using **Compustat** dataset with retail industry focus (SIC: 5200-5999).  
✅ **Actionable Insights for Investors:** Provides an **AI adoption framework** for **Private Equity (PE) firms** to identify undervalued investment opportunities.

---  

## Dataset & Methodology  
- **Dataset:** `dl0qiiqg8ytvdnss.csv` (Retail industry financial data)  
- **Jupyter Notebook:** [`AI_readiness.ipynb`](AI_readiness.ipynb) (Full analysis, models & findings)  
- **Timeframes Used:**
  - **2014-2016**: Baseline pre-AI performance  
  - **2017-2019**: Early AI adoption phase  
  - **2020-2024**: Performance during AI acceleration (used for classification)

---  

## Key Findings  
### 1️⃣ **AI Leaders Start with High SG&A Ratios but Improve Over Time**  
📌 Companies that **initially had high SG&A (overhead costs)** but successfully reduced them **became AI Leaders**.  
📌 **SG&A reduction correlates strongly with EBITDA margin improvements**.  

https://github.com/LeGMula/AI-Readiness-Score/blob/main/Screenshot%202025-03-08%20at%2015.37.25.png

### 2️⃣ **Turnaround Opportunities Have High Potential but Limited Progress**  
Some large companies **have high SG&A but haven't fully leveraged AI**.  
Examples: **McDonald's, Costco, Loblaw, Ahold Delhaize**.

https://github.com/LeGMula/AI-Readiness-Score/blob/main/Screenshot%202025-03-08%20at%2015.40.25.png

### 3️⃣ **AI Laggards Often Had Strong Past Performance But Declined**  
 **Past high EBITDA margins do not guarantee AI readiness.**  
AI Laggards (e.g., Wendy's, Wingstop) **failed to improve operational efficiency** over time.  

https://github.com/LeGMula/AI-Readiness-Score/blob/main/Screenshot%202025-03-08%20at%2015.42.14.png

---  

## Private Equity Implications  
 **How Can PE Investors Use This Model?**
- **Target Selection:** Identify **high SG&A firms with transformation potential** (best investment opportunities).  
- **Due Diligence Focus:** Use financial & operational metrics to **predict AI adoption success**.  
- **Value Creation Strategy:** Implement AI-driven cost reduction **early in the holding period** to maximize returns.  

---  

##  How to Use This Repository  
###  **Run the Model**  
1️⃣ Clone this repository:  
```bash
 git clone https://github.com/LeGMula/AI-Readiness-Score.git
```
2️⃣ Open `AI_readiness.ipynb` in Jupyter or Google Colab.  
3️⃣ Run the analysis on **Compustat Retail Data**.  
4️⃣ Explore **AI Leader predictions & investment insights**.  

---  
