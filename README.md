
# 🏦 Banking Analytics & Performance Dashboard

> **An end-to-end data analytics project exploring customer demographics, lending risk, and deposit behavior.**

This repository contains a complete data pipeline, from Python-based Exploratory Data Analysis (EDA) to a fully interactive Power BI dashboard. The goal of this project is to provide actionable financial insights into a portfolio of 3,000 retail and business banking clients.

---

## 🔗 Live Interactive Dashboard
> **[View the Live Power BI Dashboard Here](#) *(Replace `#` with your actual Power BI public web link)* **

---

## Dashboard Previews

### 1. Overview & Home
*A high-level snapshot of total clients, total loan portfolios, and deposit amounts categorized by gender and timeframe.*
![Home Page Overview](page1_home.png)

### 2. Loan Analysis
*In-depth breakdown of the $1.99bn loan portfolio, analyzing business lending vs. personal credit cards, and segmenting risk by income bands and nationality.*
![Loan Analysis View](page2_loan_analysis.png)

### 3. Deposit Analysis
*A granular look at $1.73bn in deposits, comparing checking accounts, savings accounts, and foreign currency accounts across different engagement timeframes.*
![Deposit Analysis View](page3_deposit_analysis.png)

### 4. Executive Summary
*A consolidated view of all core KPIs, including total fees, engagement accounts, and overall financial health for rapid executive decision-making.*
![Executive Summary View](page4_summary.png)

---

## 🛠️ Tech Stack & Tools

* **Exploratory Data Analysis (EDA):** Python (Jupyter Notebook)
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Business Intelligence:** Microsoft Power BI

---

## Repository Structure

```text
├── data/
│   └── Banking.csv                 # Raw dataset containing 3,000 customer records
├── eda/
│   └── BankEDA.ipynb               # Python notebook containing data cleaning and analysis
├── powerbi/
│   └── Banking Dashboard.pbix      # Interactive Power BI report file
├── page1_home.png                  # Dashboard screenshot
├── page2_loan_analysis.png         # Dashboard screenshot
├── page3_deposit_analysis.png      # Dashboard screenshot
├── page4_summary.png               # Dashboard screenshot
└── README.md                       # Project documentation
