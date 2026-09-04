# Seasonal Agriculture Performance Analysis

A data analytics project examining how agricultural performance — yield, profit, resource usage, and environmental conditions — varies across seasons in India. Built as a Major Project for the **VOIS AICTE Batch 1 2026–2027** program.

## 📌 Overview

Agricultural outcomes are shaped by seasonal variation in rainfall, temperature, soil conditions, and resource availability. This project analyzes a dataset of **4,000 farm records** across **8 Indian states**, **8 crops**, and **3 seasons** (Kharif, Rabi, Zaid) to uncover meaningful seasonal patterns, trends, and relationships — and translate them into evidence-based recommendations for agricultural planning.

## ❓ Problem Statement

Raw agricultural data does not clearly explain how performance changes across seasons or what patterns exist. This project investigates seasonal differences in agricultural performance by identifying trends, relationships, and variations within the dataset — rather than performing a generic, unfocused analysis.

## 📂 Dataset

`seasonal_agriculture_performance_dataset.csv` — 4,000 rows × 28 columns, covering:

| Category | Columns |
|---|---|
| **Identifiers** | Farm_ID, State, District, Crop, Season |
| **Environmental** | Rainfall_mm, Avg_Temperature_C, Humidity_pct, Sunlight_Hours_Day, Soil_pH, Soil_Moisture_pct |
| **Resources** | Nitrogen/Phosphorus/Potassium_kg_ha, Irrigation_Method, Fertilizer_kg_ha, Pesticide_Litre_ha, Water_Used_m3 |
| **Production** | Farm_Area_Hectares, Seed_Quality_Score, Yield_Tonnes_Ha, Production_Tonnes |
| **Economics** | Market_Price_INR_Tonne, Total_Cost_INR, Revenue_INR, Profit_INR, Water_Efficiency_t_per_1000m3 |
| **Risk** | Disease_Pest_Risk_pct |

## 🎯 Objectives

- Clean and prepare the seasonal agriculture dataset
- Compare yield, profit, and production across Kharif, Rabi, and Zaid seasons
- Examine how environmental conditions and resource usage shift by season
- Identify crop-wise and region-wise seasonal performance patterns
- Test statistical significance of seasonal differences (ANOVA)
- Derive evidence-based recommendations for seasonal agricultural planning

## 🛠️ Tools & Technologies

- **Python** — Pandas, NumPy (data cleaning & analysis)
- **Matplotlib**, **Seaborn** — data visualization
- **SciPy** — statistical testing (ANOVA)
- **Google Colab / Jupyter Notebook** — development environment

## 📊 Analysis Performed

1. Data cleaning & preparation (missing values, duplicates, derived metrics)
2. Seasonal distribution overview
3. Seasonal performance comparison (yield & profit) with ANOVA significance testing
4. Environmental condition analysis across seasons
5. Resource usage & irrigation efficiency analysis
6. Crop-wise seasonal behavior & profitability
7. Economic analysis (cost, revenue, profit margins, loss-making farms)
8. Regional (state-wise) comparison across seasons
9. Disease & pest risk analysis
10. Full correlation analysis across all numeric variables

## 📁 Repository Structure

```
├── Seasonal_Agriculture_Performance_Analysis.ipynb   # Main analysis notebook
├── seasonal_agriculture_performance_dataset.csv      # Dataset
├── Seasonal_Agriculture_Performance_Analysis_PPT.pptx # Project presentation
└── README.md
```

## 🚀 How to Run

1. Clone this repository or download the files
2. Open `Seasonal_Agriculture_Performance_Analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
3. Upload `seasonal_agriculture_performance_dataset.csv` when prompted (first cell)
4. Run all cells in order

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## 🔑 Key Findings

*(To be filled in after reviewing your notebook output — e.g. best/worst performing season, most profitable crop-season combination, strongest yield driver, etc.)*

## 🔮 Future Scope

- Build predictive models to forecast seasonal yield and profit
- Integrate real-time weather and market price data
- Develop a district-level crop and irrigation recommendation system
- Study the long-term impact of climate change on seasonal patterns

## 🎓 Certification

This project was completed as part of the **VOIS (Vodafone Idea Foundation) x Edunet Foundation** Data Visualization course, AICTE Batch 1 2026–2027.

## 👤 Author

**Madhavan Reddiar**
B.Sc Information Technology, SIES College
[GitHub](https://github.com/madhavanreddiyar)
