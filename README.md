# 📉 Car Sales Analysis  

## 📌 Project Overview  
This project analyzes sales transaction data to identify the main causes of declining sales for an vehicales retail company. Apply Python-based analytics, analyse customer behavior, 
sales trends, and potential problems in the online purchasing process.  

## 🎯 Objectives  
- Identify trends and patterns contributing to declining online sales  
- Analyze key variables affecting sales performance  
- deploy statistical and machine learning techniques to find the problem  
- Provide actionable recommendations to improve online sales  

## 📂 Dataset  
- **Source**: Provided by the tutor 
- **Format**: CSV  
- **Key Features**:  
  - Order Number  
  - Quantity Ordered  
  - Price Each
  - Order Line Number
  - Sales
  - QTR_ID
  - MONTH_ID
  - YEAR_ID
  - Address Line1
  - Address Line2
  - City
  - State
  - Post Code
  - Country
  - Territory
  - Contact Last Name
  - Contact Fisrt Name
  - Deal Size

## 🔧 Technologies Used  
- **Python** (Jupyter Notebook)  
- **Libraries**:  
  - Data Manipulation: `pandas`, `numpy`  
  - Data Visualization: `matplotlib.pyplot`, `seaborn`  
  - Statistical Analysis: `scipy.stats`, `pearsonr`  
  - Machine Learning: `sklearn.linear_model` (Linear Regression, Ridge Regression), `sklearn.tree` (Decision Tree)  
  - Model Evaluation: `mean_squared_error`, `r2_score`  

## 📊 Analysis & Methodology  
1. **Data Preprocessing & Handling**  
   - Handled missing values and data inconsistencies  
   - Filtered and sorted relevant sales data  
   - Transformed categorical variables for analysis  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized trends in online vs. in-store sales  
   - Analyzed seasonal patterns and promotional effects  
   - Examined customer ratings and return rates  

3. **Inferential Statistics**  
   - Applied **Pearson correlation** to measure relationships between variables  
   - Conducted **linear and ridge regression** to identify key sales drivers  
   - Used **decision tree models** to understand customer behavior
     
4. **Key Findings & Insights**
   
In terms of reginal performance EMEA leads with 49.6% of total sales, driven by a diverse customer base across 12 countries.
America is next with 40%, largely dominated by the USA's population and purchasing power.
APAC is the lowest performance (12%), despite its larger population.
Country-Level Performance:

In terms of country level of performance USA is the top performer, contributing significantly to the Americas, with a total order value of $2.98 million.
Ireland and Philippines show the lowest performance, showing potential areas for strategic adjustments.

In terms of Vehicle Segment Popularity Classic cars lead in sales, followed by Vintage cars, with Motorcycles, Trucks, and Buses showing moderate sales.
Trains indicate the lowest sales performance.

In terms of Sales Trends and Seasonal Insights sales are highest in Q4, particularly November, indicating a seasonal demand spike.
2005 saw higher sales compared to 2003 and 2004, with significant activity in April and May of 2005.

In terms of Correlations strong positive correlations between SALES and PRICEEACH (0.66) and MSRP (0.64), suggesting that higher prices correlate with higher sales.
Large deal sizes (0.62) have the stronger positive impact on sales, while small deal sizes have a negative correlation (-0.74), illustrating lower sales from smaller orders.

Opportunities: Expand sales strategies in APAC and Ireland.
More focus on high-value product segments like Classic and Vintage cars.
Investigate and address December's sales decline through targeted promotions or pricing adjustments.


## 🛠 How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Shakilat10/Data_Collection_and_Analysis/blob/main/README.md
