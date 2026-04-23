# Global Macroeconomic Indicators Analysis (2000–2023)

## Project Title
Global Macroeconomic Indicators Analysis (2000–2023): A Python-based study of GDP growth and inflation trends across major economies.

## Problem and Target Audience
This project investigates the evolution of key macroeconomic indicators—specifically GDP growth rate and inflation—across five major economies: the United States, China, the United Kingdom, Germany, and Japan, from 2000 to 2023. The primary goal is to identify significant patterns and divergences in these indicators over time, particularly in relation to major global economic events such as the 2008 Financial Crisis and the COVID-19 pandemic.

The target audience for this analysis includes economics and finance students, as well as general readers interested in understanding long-term global economic trends and their underlying dynamics.

## Data Source and Date
- **Provider**: World Bank Open Data
- **API**: accessed via `wbdata` Python library
- **Indicators**: GDP Growth (NY.GDP.MKTP.KD.ZG), Inflation CPI (FP.CPI.TOTL.ZG)
- **Access Date**: April 2026

## Python Methods Used
The project leveraged several Python libraries for data acquisition, processing, and visualization:
- The `wbdata` library was instrumental in fetching macroeconomic data directly from the World Bank API.
- `pandas` was used extensively for data cleaning, manipulation, and aggregation, including filtering data by year, handling missing values, and computing summary statistics.
- `matplotlib` and `seaborn` were employed to create informative plots such as line plots for trend analysis (GDP growth and inflation over time), heatmaps for comparative statistics of average values, and scatter plots to explore the relationship between GDP growth and inflation. Pearson correlation coefficients were also calculated to quantify the linear relationship between these two indicators for each country.

## Main Insights
- China consistently demonstrated the highest average GDP growth throughout the period, although its growth rate has gradually moderated.
- The 2008 Financial Crisis and the COVID-19 pandemic in 2020 both resulted in sharp, synchronized GDP contractions across all five economies, highlighting their interconnectedness.
- A significant post-2021 inflation surge was observed globally, likely driven by supply chain disruptions and fiscal stimulus. Germany and the UK experienced particularly high inflation during this period, while the US showed a relatively rapid inflation recovery.
- Interestingly, no strong universal correlation was found between GDP growth and inflation across all countries, suggesting that country-specific structural factors play a dominant role in their economic dynamics.

## How to Run
1.  Clone this repository:
    ```bash
    git clone https://github.com/YL051001/macro-economic-analysis.git
    cd macro-economic-analysis
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Open and run `macro_analysis.ipynb` in Jupyter Notebook or JupyterLab to reproduce the analysis and visualizations.

## Product / Video Link
*(To be updated with the demo video link once available)*

## Limitations and Improvements
**Limitations:**
- Data gaps were present for certain years, particularly concerning exchange rates, which could affect the completeness of the time series.
- The use of CPI as an inflation proxy might not fully capture the inflation experienced by businesses; the Producer Price Index (PPI) could be a valuable alternative.
- Official exchange rates may not always accurately reflect purchasing power or market dynamics.
- This analysis is primarily descriptive and does not establish causality between variables.

**Possible Improvements:**
- Expand the scope to include more countries for a broader comparative analysis.
- Incorporate advanced time-series forecasting models (e.g., ARIMA) for predictive insights.
- Integrate additional macroeconomic indicators such as PPI, interest rates, or unemployment rates to provide a more holistic view.
- Conduct a deeper dive into country-specific factors influencing GDP growth and inflation dynamics.

---

**Author**: Liang Ye (叶靓)
**Last Updated**: April 2026
