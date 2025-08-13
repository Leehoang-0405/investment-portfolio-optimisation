# 📈 Investment Portfolio Optimisation  

## 🌟 Highlights  
- Real ASX stock market data used to simulate realistic investment scenarios.  
- Two optimisation models: **Linear Programming (LP)** for allocation and **Integer Linear Programming (ILP)** for asset selection.  
- Advanced constraint modelling to manage **risk**, ensure **sector diversification**, and meet business rules.  
- Sensitivity analysis for deeper insight into constraint impacts and decision trade-offs.  
- Clear, data-driven recommendations supported by Excel Solver outputs and visual reports.  

---

## ℹ️ Overview  
This project was completed as part of my **Decision Modelling coursework**.  
It focuses on **optimising an investment portfolio** using 4 years of live data from the **Australian Securities Exchange (ASX)** to maximise return while managing risk and enforcing diversification.  

Two optimisation approaches were developed:  
1. **Linear Programming (LP)** – Continuous allocation modelling.  
2. **Integer Linear Programming (ILP)** – Discrete asset selection with strict business rules.  

All modelling and analysis were performed using **Microsoft Excel Solver**, with results presented in a detailed **PowerPoint report**.  
---

## 📈 Key Components  

### Data Acquisition & Preparation  
- Selected **8 ASX-listed companies** across **4 sectors**: Healthcare, Technology, Communications, Financials.  
- Collected **Jan 2021 – Jan 2025** monthly closing prices.  
- Calculated **monthly returns**, **average return**, and **volatility** (standard deviation).  
- Classified assets into **low, medium, and high risk** tiers.  

### LP Model – Portfolio Allocation Optimisation  
**Objective:** Maximise expected return.  
**Constraints:**  
- High-risk exposure ≤ 15%  
- Low-risk assets must have the highest allocation  
- Minimum sector allocation: 15% (with one sector ≥ 20%)  
- Minimum 5% investment per asset  
- Custom diversification rule for realistic portfolios  

**Output:** Optimal allocation percentages + sensitivity analysis.  

### ILP Model – Asset Selection Optimisation  
**Objective:** Maximise expected return under discrete selection rules.  
**Constraints:**  
- Select exactly **5 assets**  
- All **4 sectors** represented  
- Max **1 high-risk** asset; min **2 low-risk** assets  
- High-risk allowed only if at least one medium-risk asset is selected  
- Custom business rule for realistic investment scenarios  

**Output:** Optimal asset selection using binary decision variables.  

---

## 💡 Business Value & Application  
This project demonstrates the use of **mathematical optimisation in financial decision-making**, directly applicable to:  
- Investment & portfolio analysis  
- Operations research  
- Decision science & strategy consulting  
- Risk management and asset allocation  

---

## 👤 Author  
**Ba Huy Hoang Le**  
📧 huyhoangle040502@gmail.com  

---

## 📜 Acknowledgement of AI Use  
Some text drafting, grammar checks, and structure suggestions were assisted by AI tools, with all final content reviewed and edited by me to ensure originality and accuracy.  
