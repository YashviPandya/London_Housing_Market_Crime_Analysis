# 🏙️ London Housing Market & Crime Analysis (2000–2023)

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Business Question
> **Which London boroughs offer the best balance of housing affordability and safety for first-time buyers and property investors — and how has this changed over the past 23 years?**

Urban planners, property investors, and policy-makers often rely on fragmented data. This project combines 23 years of housing price data with crime statistics to produce a unified view that supports smarter investment and planning decisions.

---

## 📊 Project Overview

This project analyses **23 years of London housing and crime data** to uncover patterns between property values and crime rates across all 33 London boroughs. Using Python, I built a data pipeline that integrates multiple public datasets, cleans and transforms them, and produces visualisations that highlight actionable trends.

**Tools Used:** Python (Pandas, Matplotlib, Seaborn, Plotly) · Jupyter Notebook · ONS Housing Data · Metropolitan Police Crime Data

---

## 🔍 Key Findings

- **Boroughs with the steepest price growth (2000–2023):** Hackney, Waltham Forest, and Lewisham saw 400%+ price increases — driven partly by crime reduction and gentrification
- **Inverse crime-price relationship:** Boroughs with sustained crime reduction (e.g. Tower Hamlets, Southwark) showed above-average price appreciation over the following 3–5 years, suggesting crime data can act as a **leading indicator** for property investment
- **Emerging safe-affordable zones:** As of 2023, Barking & Dagenham and Havering offer the strongest affordability-to-safety ratio for first-time buyers
- **Central London paradox:** Westminster and Kensington maintain high prices despite above-average crime, indicating that for prime property, location prestige overrides crime sensitivity

---

## 💡 Business Recommendation

Based on this analysis:

1. **For property investors:** Boroughs showing a 3-year declining crime trend with below-median house prices (currently Croydon South, Sutton) represent the strongest near-term appreciation opportunity
2. **For urban planners:** Crime reduction investment in outer East London boroughs could accelerate housing market recovery and reduce price inequality
3. **For first-time buyers:** Barking & Dagenham and Havering deliver the best affordability-safety trade-off in the current market

---

## 📁 Repository Structure

```
├── data/
│   ├── housing_prices_london.csv
│   └── crime_data_london.csv
├── notebooks/
│   └── london_housing_crime_analysis.ipynb
├── visuals/
│   └── borough_heatmap.png
└── README.md
```

---

## 🚀 How to Run

```bash
git clone https://github.com/YashviPandya/London_Housing_Market_Crime_Analysis
pip install pandas matplotlib seaborn plotly
jupyter notebook notebooks/london_housing_crime_analysis.ipynb
```

---

## 📬 Contact
**Yashvi Pandya** · [LinkedIn](http://www.linkedin.com/in/yashvipandya) · MSc Data Analytics, BPP University
