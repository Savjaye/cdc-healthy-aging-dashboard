# CDC Healthy Aging Interactive Dashboard

This project analyzes the [CDC Alzhaimer's Disease and Healthy Aging Dataset](https://data.cdc.gov/Healthy-Aging/Alzheimer-s-Disease-and-Healthy-Aging-Data/hfr9-rurv/about_data) to explore relationships bewtween lifestyle factors and subjective cognitive decline (SCD) among older adults in the United States. The analysis included data exploration + cleaning, long → wide reconstruction, and the creation of an interactive Tableau dashboard. 

**Interactive Dashboard:** 
**[View the Tableau Dashboard Here](https://public.tableau.com/shared/77GSGCHF9?:display_count=n&:origin=viz_share_link)

## Project Overview

The goal of this project is to:
- Identify trends in lifestyle and health indicators among older adults  
- Compare these indicators to reported subjective cognitive decline  
- Provide interactive visualizations for exploring state-level patterns across years  

The dataset originates from the CDC Behavioral Risk Factor Surveillance System (BRFSS) Healthy Aging dataset and is provided in long format.  
For visualization purposes, the dataset is transformed into both long and wide formats and filtered to retain variables relevant to SCD and lifestyle indicators.

## Directory Structure
cdc-healthy-aging-dashboard/
├── README.md
├── data/
│   ├── processed/                 # processed outputs
│   └── raw/                       # raw dataset goes here
├── notebooks/
│   └── 01-exploritory-analysis.ipynb    # annotated EDA + cleaning steps
└── tableau/                       # local Tableau files
    ├── cdc-scd-dashboard.twb
    ├── cdc-scd-dashboard.twbx
    ├── cdc-tableau-workbook.twb
    └── ~cdc-scd-dashboard__21988.twbr

## Reproducibility 

To reproduce this analysis 

1. download the [CDC Alzhaimer's Disease and Healthy Aging Dataset](https://data.cdc.gov/Healthy-Aging/Alzheimer-s-Disease-and-Healthy-Aging-Data/hfr9-rurv/about_data)
2. Install hte dependecies using 
```bash
pip install -r requirements.txt
```

## Contact 
If you have questions or want to build on this project, feel free to reach out: savannahjaye00@gmail.com

