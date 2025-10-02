# Global Climate Analytics - Deep Data Hackathon 2.0 (Round 1)

## Project Overview

This project presents an exploratory data analysis (EDA) of global climate indicators from 2000 to 2023 using the dataset provided for the Deep Data Hackathon 2.0 Round 1.  
We analyze key variables including CO₂ emissions, renewable energy adoption, forest area, extreme weather events, temperature, sea level rise, and rainfall across multiple countries and regions.

Our goal is to uncover hidden patterns, trends, and meaningful relationships in these environmental indicators to inform climate-related policy recommendations.

---

## Dataset
Dataset Link - https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset

- The dataset contains annual climate and environmental statistics across 50+ countries from 2000 to 2023.
- Key variables studied:
  - CO₂ Emissions (Tons/Capita)
  - Renewable Energy (%)
  - Forest Area (%)
  - Extreme Weather Events
  - Average Temperature (°C)
  - Sea Level Rise (mm)
  - Rainfall (mm)
  - Population

---

## Analysis Approach

- Data cleaning and manipulation were performed in Python (Pandas).
- Statistical exploration including pairwise and partial correlations, multivariate regressions.
- Time series analyses to compare trends, including pre- vs. post-2015 breakdown.
- Group comparisons between developed and developing countries.
- Visualization of results were created using Matplotlib and Seaborn.
- Interactive dashboard created in Microsoft Power BI for dynamic data exploration.
- PowerPoint presentation summarizes key insights and policy implications.

---

## Project Structure

- `climate_change_dataset.csv`: Raw dataset used for analysis.
- `climate_change_eda.ipynb`: Jupyter notebook containing all EDA code, visualizations, and statistical tests.
- `Climate Change Policy Dashboard DeepData Hackathon`: Power BI interactive dashboard file.
- `Presentation.pptx`: PowerPoint slides highlighting project overview, findings, and recommendations.
- `README.md`: This file.
- `requirements.txt`: Python environment dependencies.

---

## Key Insights

1. **Limited Direct Effects of Single Variables**  
   - Simple linear relationships between CO₂ emissions, renewable energy adoption, forest area, and climate impact indicators (temperature, extreme weather, sea level rise) are very weak or statistically insignificant globally.  
   - This indicates that the complex dynamics of climate change cannot be captured by looking at individual variables in isolation due to confounding and interacting influences.

2. **Divergent Emission Trends by Development Status**  
   - Developed countries generally maintain higher per capita CO₂ emissions, though recent years show variability.  
   - Developing countries exhibit lower per capita emissions on average but demonstrate stronger upward trends reflecting rapid industrialization and energy growth.  
   - The narrowing gap highlights urgent global equity and technological transfer considerations.

3. **Post-2015 Acceleration in Renewables with Limited Emission Reduction**  
   - Post-Paris Agreement (2015) data shows increased renewable energy share worldwide. Still, CO₂ emissions have not correspondingly declined—suggesting a time lag, insufficient scale, or offsetting economic factors.  
   - Effective climate action requires coupling renewable adoption with aggressive decarbonization and conservation policies.

4. **Forest Cover's Role in Climate Impacts is Complex**  
   - Forest area shows almost no direct linear correlation with extreme weather frequency, implying that forest cover alone is not a reliable indicator of climatic risk at the country level.  
   - Localized studies and multivariate approaches are needed to better understand forest-related climate resilience factors.

5. **Strong Regional Disparities Call for Tailored Policies**  
   - Regional analysis reveals North America and Asia dominate in emissions per capita, while Europe leads in renewable energy adoption, underscoring varied national priorities and capabilities.  
   - Climate policies must account for regional socioeconomic realities rather than applying uniform global prescriptions.

---

## How to Run

1. Setup Python environment: pip install -r requirements.txt
2. Open and run `climate_change_eda.ipynb` in Jupyter Notebook, JupyterLab, VSCode, Google Colab, etc.
3. Explore the Power BI dashboard to interactively analyze regional and temporal trends.
4. Reference the PowerPoint presentation for a narrative overview and recommendations.

---

## Tools & Libraries

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels, Scipy  
- Power BI Desktop  
- Microsoft PowerPoint  

---

## Authors

- Gurneesh Singh Banga
- Aaradhya
- Aditya Gaur
- Anu Sharma

---
