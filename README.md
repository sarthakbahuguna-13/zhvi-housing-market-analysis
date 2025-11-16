# 🏡 US Housing Market – State-Level Analysis (ZHVI)

This project performs an end-to-end exploratory data analysis (EDA) of the US housing market using Zillow's **Zillow Home Value Index (ZHVI)** at the **state level**.

Each row in the dataset represents a **month**, and each column represents the **average home value in a US state** for that month. Using this structure, the project explores:

- National housing trends over time  
- Differences between states (high vs low value)  
- Long-term growth winners  
- Recent year-over-year growth  
- Market volatility across states  

---

## 📂 Project Structure

```text
project-1-zhvi-state-eda/
│
├── data/
│   └── ZHVI.csv
│
├── notebook/
│   └── zhvi_state_eda.ipynb
│
├── images/
│   ├── national_avg_trend.png
│   ├── top_states_latest.png
│   ├── top_states_long_term_growth.png
│   ├── top_states_yoy_growth.png
│   └── most_volatile_states.png
│
└── report/
    └── housing_insights.pdf
