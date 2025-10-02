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

- No strong linear correlation between renewable energy percentage and CO₂ emissions globally.
- Developed nations have higher per capita emissions, but developing nations show signs of increases.
- Forest area and extreme weather events show weak linear relationships, suggesting complex climate dynamics.
- Post-2015 (Paris Agreement) period shows modest increases in renewables but no clear CO₂ reduction trend globally.
- Regional disparities suggest targeted policy approaches may be more effective than global one-size-fits-all solutions.

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
