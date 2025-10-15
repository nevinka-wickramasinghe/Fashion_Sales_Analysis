#
# Fashion Sales Analysis – Customer & Sales Insights


## Project Overview

This project is an **exploratory data analysis** (EDA) of a fashion retail dataset, focused on uncovering insights about customer behavior, sales trends, product performance, and store operations. The goal was to **transform raw transactional data into actionable insights** to support decision-making in retail management.

The analysis covers:

- Sales trends and forecasts
- Customer purchasing patterns
- Product category performance
- Payment behavior
- Store performance across regions

Additionally, regression models were applied to forecast future sales trends.

![Fashion Sales Analysis Overview](https://github.com/nevinka-wickramasinghe/Fashion_Sales_Analysis/blob/main/overview.webp)

## Problem Statement

Retail businesses often face challenges in understanding:

- How different **customer segments** contribute to revenue
- Which **products and categories** drive sales
- **Seasonal and geographic sales trends**
- Customer **payment behavior** and **discount impact**

This project addresses these challenges by analyzing historical sales data to answer key business questions and provide insights for future planning.

The dataset was sourced from Kaggle. Link: https://www.kaggle.com/datasets/ricgomes/global-fashion-retail-stores-dataset?resource


## Data Cleaning & Preparation

The raw dataset required extensive cleaning to ensure accuracy and usability:

- **Missing values**: Identified and imputed or removed incomplete records  
- **Duplicate entries**: Detected and removed repeated transactions  
- **Data type corrections**: Converted dates, numeric fields, and categorical data for proper analysis  
- **Derived metrics**: Calculated additional fields like total revenue per transaction, average discount, and sales per customer  
- **Outlier detection**: Identified and handled extreme values to prevent skewed analysis  
- **Feature engineering**: Created new variables such as quarterly sales performance, payment trends, and product popularity scores  

The cleaned dataset provided a robust foundation for advanced **EDA** and predictive modeling.


# Exploratory Data Analysis (EDA)

Using **Python, Pandas, Seaborn, and Matplotlib**, a deep dive into the data was performed to uncover trends and patterns:

- **Customer insights**: Gender-wise sales distribution, age vs. spending trends, and payment behavior (cash, credit, other)  
- **Product performance**: Sales by category, top-selling items, and impact of discounts on purchase behavior  
- **Store & regional analysis**: Quarterly performance, sales distribution across countries, and top-performing stores  
- **Revenue & discount analysis**: Total revenue, average discount, total customers, and total stores per region  
- **Trend analysis & forecasting**: Regression models to predict future sales trends and seasonal behavior  

> ⚡ **Additional insights**: Beyond the key visualizations summarized here, numerous other trends, correlations, and patterns were explored in the **Jupyter Notebook**, providing a comprehensive understanding of the dataset.


# Key Insights

- Clear **gender-based differences** in purchasing behavior  
- Certain **product categories consistently outperform others**, with predictable seasonal trends  
- **Payment method patterns** reveal customer preferences for cash vs. credit transactions  
- Regional and **store-level performance varies**, highlighting opportunities for targeted marketing  
- Regression-based **sales forecasts** provide a basis for future planning and inventory optimization

