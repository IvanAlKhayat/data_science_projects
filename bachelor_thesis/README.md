# Demographic and socio-economic data integration & analysis


## Overview
This notebook was created as part of my bachelor thesis preparation. The goal was to simulate data integration and preprocessing workflows inspired by real consulting projects involving ISTAT data.  
⚠️ Due to NDAs, the actual data and processing steps from the consulting company cannot be reproduced here. Instead, **simulated ISTAT-like data** was used, while the **core methodological idea** remains consistent.

## Steps
1. **Data Integration**
   - Merged multiple simulated datasets: demographic indicators, geographic data, education, tourism, and municipal codes.
   - Resolved key mismatches and harmonized codes across tables.

2. **Feature Engineering**
   - Aggregated population by civil status and age group.
   - Computed derived indicators such as average age.
   - Enriched municipalities with socio-economic and geographic attributes.

3. **Exploratory Analysis**
   - Created integrated datasets ready for clustering and predictive modeling.
   - Simulated clustering of requests and complaints to showcase downstream applications.
   -A Pearson correlation matrix was computed to quantify linear relationships between demographic and socio-economic variables, highlighting potential dependencies for further analysis


## Technologies
- Python, Jupyter Notebook  
- Libraries: `pandas`, `scikit-learn`

## Key Learning
The project demonstrated how **data integration and feature engineering** from heterogeneous sources can support advanced analytics. It also reflects the methodological foundations of my bachelor thesis, while respecting confidentiality of real consulting projects.
