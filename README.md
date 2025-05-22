# EDA Project: King County Housing Data

---

## Overview

This repository contains an exploratory data analysis (EDA) project focused on the King County housing market. The analysis is designed for a fictional client, **Amy Williams**, a seller with unique requirements. The project aims to uncover actionable insights and provide strategic recommendations based on property sales data from King County, USA.

---

## Project Scenario

**Client:**  
Amy Williams  
Seller  
_A Mafiosi, sells several central houses (top 10%) over time, needs average outskirt houses over time to hide from the FBI._

**Business Goal:**  
- Provide specific recommendations on how the market is developing for successful sales.
- Advise on where it is strategically best to buy, considering geographic and time-based information.
- Determine which area is best to move to, depending on the ratio of sales.

---

## Hypotheses

1. **Ratio of Sales:**  
   There is no significant difference between the ratio of central to outskirts property sales compared to the overall market ratio.

2. **Spatial Distribution:**  
   There is no significant difference in the spatial distribution pattern of outskirt properties compared to central properties.

3. **Timing of Sales:**  
   There is no significant difference in the time intervals between central property sales and outskirt property transactions compared to quarterly timing.

---

## Methodology

- **Defining Areas:**  
  - Central and outskirt properties are defined based on zip codes.
  - Central properties: Top 10% by value or sales volume.
  - Outskirt properties: Average properties outside the central definition.

- **Data Extraction & Processing:**  
  - Extract quarterly sales data over the last decade for both central and outskirt areas.
  - Study the distribution of property sales in both regions.
  - Calculate and compare the ratio of central to outskirt sales over the last 12 months.

- **Analysis Tools:**  
  - **Pandas** and **NumPy** for data manipulation.
  - **Matplotlib** and **Seaborn** for visualization.
  - **GeoPandas** and **shapely.geometry** for spatial analysis.

---

## Repository Structure

```
├── data/
│   └── king_county_housing.csv      # (Not uploaded to GitHub)
├── notebooks/
│   └── eda_king_county.ipynb        # Main EDA notebook
├── slides/
│   └── presentation.pdf             # High-level overview slides (PDF)
├── README.md                        # This file
```

---

## Key Insights

1. **Sales Ratio:**  
   Analysis of the ratio between central and outskirt property sales over time reveals trends that may indicate shifts in buyer preferences or market saturation.

2. **Geographical Patterns:**  
   Spatial analysis highlights clusters of high-value sales and identifies emerging neighborhoods in the outskirts that may offer strategic opportunities.

3. **Temporal Trends:**  
   Quarterly sales patterns show whether central or outskirt properties are more sensitive to seasonal or economic cycles.

---

## Recommendations for Amy Williams

1. **Strategic Relocation:**  
   Consider purchasing in outskirt areas with rising sales ratios, as these may offer better anonymity and future appreciation potential.

2. **Timing Sales:**  
   Align central property sales with quarters showing peak demand to maximize returns.

3. **Geographic Diversification:**  
   Diversify holdings by acquiring properties in multiple outskirt zip codes identified as up-and-coming, reducing risk and increasing flexibility.

---

## How to Use This Repository

1. **Explore the Data:**  
   - Review the `notebooks/eda_king_county.ipynb` for step-by-step analysis and visualizations.
   - Refer to `column_names.md` for clarification on dataset columns.

2. **View Results:**  
   - Check the `slides/presentation.pdf` for a concise summary of findings and recommendations.

3. **(Optional) Data Processing:**  
   - Use the script in `scripts/data_processing.py` for reproducible data cleaning and preparation.

---

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies with:
```
pip install pandas numpy matplotlib seaborn
```

---

## Notes

- The dataset is stored locally in the `data/` folder and is not uploaded to GitHub for privacy.
- All assumptions and definitions (e.g., what constitutes "central" or "outskirt" areas) are explicitly stated in the notebook and presentation.
- This project is for educational purposes and uses a fictional client scenario.

---

Happy exploring! 🚀# EDA Project: King County Housing Data
