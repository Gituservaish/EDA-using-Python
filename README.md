## Exploratory Data Analysis-using-Python

### Project Overview

In This project we performed Exploratory Data Ananlysis on festival sales data of an e-commerce company over the past year. By analyzing various aspects of the sales data, we try to suggest store to improve customer experience by Analyzing the statistics of sales and help to increase revenue.

### Data Sources

The primary dataset used for this analysis is "Diwali sales analysis.csv" file obtained from youtube source, containing information about each category and various stats of a company.

### Tools

- Python - jupyter notebook.
- python libraries - numpy, pandas, matplotlib, seaborn.

### Operations performed

- Data cleansing - data inspection, removal of empty/blank cells,duplicates and null values.
- Exploratory data analysis - analyzed data based on different category and cases and products.

### Exploratory Data Analysis (EDA)

EDA involved exploring the sales data to answer key questions, such as:
1. which state made top sales?
2. which product category was sold the most?
3. which gender made most of the sales?

### Data Analysis

```python
# import python libraries

import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt # visualizing data
%matplotlib inline
import seaborn as sns
```

```python
# plotting a bar chart for Gender and it's count

ax = sns.countplot(x = 'Gender',data = df)

for bars in ax.containers:
    ax.bar_label(bars)
```


### Insights/Findings

1. Most of the orders & total sales/amount are from Uttar Pradesh, Maharashtra and Karnataka respectively.
2. Maximum of the buyers are of age group between 26-35 yrs female.
3. Largest of buyers are working in IT, Healthcare and Aviation sector.
4. Highest sold products are from Food, Clothing and Electronics category.
5. Purchasing power of females are greater than men.


### Recommendations
Based on the Analysis, we following suggestions/actions can be inferred :
- Target Married women customers of age group 26-35 yrs from UP, Maharastra and Karnataka working in IT, Healthcare and Aviation. Who are more likely to buy products from Food, Clothing and Electronics category.
