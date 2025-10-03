# In Progress: Income Inequality, Education, Poverty, and Hate Crimes Analysis

## Overview

This project combines U.S. Census ACS data (2008–present) with FBI hate crime statistics to explore connections between:

- Income inequality (Gini Index)
- Educational attainment
- Poverty Rates
- Reported hate crimes by state and year

## Goals

- Fetch and clean ACS data (inequality + education)
- Collect FBI hate crime data
- Merge datasets into a single master table
- Analyze state-level trends and relationships over time

## Structure

- `analysis.ipynb` → step-by-step analysis
- `data/` → cleaned CSVs (Census + FBI + master dataset)
- `.env` → API key(s)
- `README.md` → project overview

## Next Steps

- Clean Data
- Visualize trends (time series, geographic maps)
- Explore correlations between inequality, education, and hate crimes
- Extend to county-level or demographic-level detail if available
  