# Global Macroeconomic Indicators Analysis (2000–2023)

## Project Overview
This project analyses key macroeconomic indicators — GDP growth rate and inflation 
rate — across five major economies (USA, China, UK, Germany, Japan) from 2000 to 2023, 
using Python and World Bank open data.

## Analytical Question
How have GDP growth and inflation evolved across major economies, and what patterns 
emerge around key global events such as the 2008 Financial Crisis and COVID-19?

## Target Audience
Economics and finance students; general readers interested in global economic trends.

## Data Source
- **Provider**: World Bank Open Data
- **API**: accessed via `wbdata` Python library
- **Indicators**: GDP Growth (NY.GDP.MKTP.KD.ZG), Inflation CPI (FP.CPI.TOTL.ZG)
- **Access date**: April 2026

## Project Structure
```
macro-economic-analysis/
├── macro_analysis.ipynb   # Main analysis notebook
├── requirements.txt       # Dependencies
├── figures/               # Output charts
└── README.md
```

## How to Run
1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open and run `macro_analysis.ipynb` in Jupyter Notebook or JupyterLab

## Key Findings
- China maintains the highest average GDP growth across the period
- All five economies contracted simultaneously in 2008 and 2020
- Post-2021 inflation surge is visible across all countries, with Germany and UK most affected
- No universal correlation between GDP growth and inflation exists across countries

## Technologies Used
- Python 3.x
- pandas, matplotlib, seaborn, wbdata
