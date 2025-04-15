
# Description

This project focuses on analyzing chemicals in cosmetic products to uncover trends in ingredient usage, reporting practices, and brand-specific patterns over time. The goal was to examine how chemical disclosures in cosmetics evolved and identify key patterns related to product types, chemical names, brands participating in reporting, and reporting timelines.


## Data Source
The dataset used in this analysis comes from the California Safe Cosmetics Program (CSCP) under the California Department of Public Health. It tracks cosmetic products and their chemical components reported to the CSCP between 2009 and 2020.


## Overview of the Dataset
- Contains 114,635 rows and 22 columns
- Includes data on chemical names, brands, product categories, and reporting dates
- Link ('https://s3.amazonaws.com/og-production-open-data-chelseama-892364687672/resources/57da6c9a-41a7-44b0-ab8d-815ff2cd5913/cscpopendata.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJJIENTAPKHZMIPXQ%2F20250415%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250415T225453Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=64dff276366e61a2fa146f987f5e5e0bcded0b6dc5a0a7700cade7c7d8d46a17')
  
## Data Preparation & Tools
 - Python (Pandas, NumPy, Matplotlib, Seaborn) was used for data manipulation, cleaning, and visualization.
- Converted date-related columns to datetime format using the to_datetime method.
- Renamed columns for improved readability and consistency.
- Inspected data structure and identified missing values in CSF_ID and CSF columns; these were tied to registration numbers and considered not relevant for analysis, so they were left unchanged.
- Focused the analysis on chemical names, brands, product types, and dates to draw meaningful insights from the dataset.
- Google Colab was used to document and present the entire analysis interactively
## Key Analysis Questions
1. What are the most commonly reported chemicals in cosmetic products?
2. Which brands frequently report hazardous ingredients?
3. How are toxic chemicals distributed across different product categories?
4. How have chemical reports changed over the past decade (2009–2019)?
5. What is the overall trend in hazardous chemical reporting?
