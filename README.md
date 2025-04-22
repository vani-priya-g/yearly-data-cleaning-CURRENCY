# Yearly-data-cleaning-GOLD

**Author:** Vani Priya ([@vani-priya-g](https://github.com/vani-priya-g))  
**Last updated:** April 2025

## Overview

This repository contains a Jupyter Notebook (`clean_yearly_data.ipynb`) and associated raw & cleaned CSV files for annual currency exchange–rate data:

- **Raw data**  
  - `Yearly_Avg.csv`: Yearly average rates for major currencies  
  - `Yearly_EoP.csv`: Year–end (EoP) rates for major currencies  

- **Cleaned outputs**  
  - `Yearly_Avg_Cleaned.csv`  
  - `Yearly_EoP_Cleaned.csv`  

The notebook covers:
1. Loading raw CSVs  
2. Converting the **Date** column to datetime  
3. Stripping commas and converting numeric strings to floats  
4. Handling missing values (dropping rows with >50% NaNs)  
5. Exporting cleaned CSVs  

## Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/vani-priya-g/Yearly-data-cleaning-GOLD.git
   cd Yearly-data-cleaning-GOLD
