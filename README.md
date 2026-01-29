# AI4-GOVERN
AI4Govern is a hackathon project developed for the NIRU AI Hackathon, focused on building an intelligent dashboard that flags potential governance and financial risks in public projects. The MVP leverages historical public contract award data from Kenya to identify high-risk contracts based on value concentration and supplier patterns.


# AI4Govern – Intelligent Dashboard for Public Project Risk Analysis

## Overview

AI4Govern is an AI-driven governance analytics project developed as part of the **NIRU AI Hackathon**. The project focuses on demonstrating how data science and machine learning can be used to enhance **transparency, accountability, and early risk detection** in public sector projects.

The MVP analyzes historical public procurement and contract award data from Kenya to identify potential governance and financial risk patterns, and presents these insights through an interactive dashboard.



## Problem Statement

Public sector projects often face challenges such as cost overruns, delays, and limited transparency. Oversight bodies typically rely on manual reviews and retrospective audits, which can delay intervention.

There is a need for **data-driven tools** that can flag high-risk projects early, enabling better prioritization, monitoring, and accountability.



## Project Objective

The objective of AI4Govern is to:

* Analyze historical public contract award data
* Identify risk signals associated with large and repetitive procurement contracts
* Classify projects into risk levels (Low, Medium, High)
* Provide a simple, explainable dashboard to support oversight and decision-making



## Data Source

The MVP uses historical **World Bank Contract Awards – Investment Project Financing** data for Kenya.

Key characteristics of the dataset:

* Fiscal Years: 2020 onwards
* Records: Thousands of contract awards
* Core variables include contract value, supplier, procurement method, sector, and award date

Note: The MVP relies on historical data to learn governance risk patterns that remain relevant for future and ongoing projects.



## Methodology (In Progress)

The project follows these steps:

1. Data cleaning and preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering (e.g., contract value percentiles, repeat supplier indicators)
4. Risk labeling using rule-based logic
5. Machine learning modeling for risk classification
6. Visualization and dashboard development

This repository currently focuses on **analysis and modeling**, with the dashboard implemented separately.



## Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Google Colab (analysis & modeling)
* Streamlit (dashboard)
* GitHub (version control)



## Current Status

* [x] Dataset acquisition
* [x] Initial exploratory data analysis
* [x] Data cleaning and feature engineering
* [x] Model training and evaluation
* [ ] Dashboard development




## Expected Impact

AI4Govern demonstrates how AI-driven analytics can:

* Improve visibility into public spending
* Highlight high-risk contracts for early intervention
* Support evidence-based oversight and governance decisions



## Author

**Murugi**



## License

This project is developed for educational and hackathon purposes.
