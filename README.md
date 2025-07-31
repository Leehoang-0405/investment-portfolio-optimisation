# Investment Portfolio Optimisation
A decision modelling project applying LP and ILP techniques to construct a diversified, risk-controlled ASX portfolio using historical return data.
Investment Portfolio Optimisation using Decision Modelling

Project Overview

This project focuses on optimising an investment portfolio using advanced decision modelling techniques, leveraging four years of live stock market data from the Australian Securities Exchange (ASX). The goal was to develop robust, data-driven models that maximise return while managing risk and enforcing diversification across sectors.

Two optimisation approaches were implemented:

- Linear Programming (LP) for continuous allocation modelling
- Integer Linear Programming (ILP) for discrete asset selection under strict constraints

All modelling and analysis were performed using Microsoft Excel Solver, with results consolidated and visualised in a comprehensive PowerPoint report.

Business Value and Application

This project simulates a real-world financial portfolio challenge: how to allocate capital across multiple assets while meeting business rules related to risk, return, and diversification.

The skills and methods demonstrated here are directly applicable to roles in:
- Financial and investment analysis
- Operations research
- Decision science and business strategy
- Data-driven consulting

Key Components
Data Acquisition & Preparation
- Selected 8 publicly listed ASX companies across 4 distinct sectors: Healthcare, Technology, Communications, and Financials
- Collected 4 years of monthly stock closing prices (Jan 2021 – Jan 2025)
- Computed monthly returns, average return, and volatility (standard deviation) for each asset
- Classified each asset into one of three risk tiers (low, medium, high)

LP Model – Portfolio Allocation Optimisation

Objective: Maximise expected return

Constraints:
- High-risk exposure ≤ 15%
- Low-risk investments must have the highest allocation
- Minimum sector allocation: 15% (one sector ≥ 20%)
- Minimum 5% investment per asset
- Custom constraint to ensure realistic, diversified portfolios

Output: Optimal portfolio allocation by percentage
Analysis: Full sensitivity analysis (binding constraints, shadow prices, reduced costs)

ILP Model – Asset Selection Optimisation

Objective: Maximise expected return under discrete selection rules

Constraints:
- Select exactly 5 assets
- All 4 sectors must be represented
- Max 1 asset from high-risk category; min 2 from low-risk
- A high-risk asset can only be included if at least one medium-risk asset is also selected
- Custom rule to reflect a realistic investment scenario

Output: Optimised asset selection with binary inclusion logic

Visual Report & Presentation
- Conceptual diagrams of each model
- Mathematical formulations of LP and ILP logic
- Excel outputs, charts, and summary tables
- Strategic interpretation of results, trade-offs, and recommendations

Deliverables
Portfolio_Optimisation.xlsx – Data preparation, LP and ILP models, solver setup, and sensitivity analysis

Investment_Optimisation_Report.pptx – Visual summary of approach, results, and recommendations

Tools & Techniques
- Excel Solver (LP & ILP)
- Financial return and risk modelling
- Sensitivity analysis and constraint interpretation
- Portfolio construction and optimisation strategy
- Visual storytelling with PowerPoint

Highlights
- Real financial data used to simulate investment scenarios
- Advanced constraint modelling in Excel (including sector and risk diversification)
- Clear, data-driven decision support based on optimisation results
- Practical understanding of capital allocation under uncertainty



