# Supermarket Sales and Customer Analysis 


## Project Overview 

This project analyzes supermarket transaction data to understand sales performance, product performance, branch performance, customer spending behaviour, and payment preferences. The analysis uses Python and data visualization techniques to identify patterns that can support data-driven business decisions. 


## Business Objective 

The objective of this analysis is to evaluate supermarket sales and customer transaction patterns across branches, product lines, customer types, genders and payment methods. The findings can help identify sales trends and customer behaviour patterns that may support business decision making. 


## Business Questions 

- What is the total revenue generated during the analysis period? 
- Which branch generates the highest revenue? 
- How does revenue change over time? 
- Which Product lines generate the most revenue? 
- Which product lines sell the most units? 
- How does average spending differ between customer types? 
- Is there a difference in average transaction value between male and female customers? 
- Which payment methods are most commonly used? 


## Dataset 

The dataset contains 1,000 supermarket transactions recorded between January 1, 2019 and March 30, 2019. 

It includes information about:
- Branch and City 
- Customer type and gender 
- Product line 
- Unit price and quantity 
- Sales and gross income 
- Date and Time 
- Payment method 
- Customer rating 

Source: Kaggle - Supermarket Sales Dataset


## Tools and Skills 

- Python 
- Pandas - data cleaning, transformation, grouping, and analysis
- NumPy - numerical operations
- Matplotlib - data visualization 
- Seaborn - Statistical data visualization
- SciPy - Statistical testing (two-sample t-tests)
- Jupyter Notebook 


## Data Cleaning and Preparation 

The dataset was inspected and prepared for analysis: 

- Checked the dataset structure, data types, and summary statistics
- Checked for missing values and duplicate records 
- Converted the 'Date' column to datetime format 
- Verified numerical columns for invalid or suspicious values
- Checked for duplicate Invoice IDs
- Verified the relationship between Sales, Cost of goods sold, and gross income 
- Created a 'Month' feature from the transaction date for time based analysis 


## Analysis 

The analysis focused on: 

- Total revenue and revenue distribution across branches 
- Revenue contribution by product line 
- Units sold by product line 
- Average transaction value by customer type 
- Average transaction value by gender 
- Payment method usage 
- Monthly revenue patterns 
- Comparison of revenue and unit sales across product categories


## Key Insights 

- Giza generated the highest revenue among the three branches (110,568.71), while Alex (106,200.37) and Cairo (106,197.67) recorded nearly identical revenue. 

- Food and beverages generated the highest revenue among the product lines, while health and beauty recorded the lowest revenue contribution. 

- Electronic accessories recorded the highest unit sales, while food and beverages generated the highest revenue. The higher average unit price of food and beverages (56.01 vs 53.55) may partly explain the difference.

- Member customers had a higher average transaction value than Normal customers (335.74 vs 306.37). 

- Female customers had a higher average transaction value than male customers in this dataset (340.93 vs 299.06). This difference was confirmed statistically significant (p < 0.05) 

- Ewallet and Cash were the most frequently used payment methods, with credit cards accounting for fewer transactions.

- Revenue decreased from January to February and increased again in March.


## Limitations 

- The dataset covers transactions from January 1, 2019 to March 30, 2019, so it does not represent a full year of sales activity. 
- The dataset provides transaction-level sales information but does not include expenses beyond cost of goods sold, so net profit cannot be calculated. 
- The observed customer and gender spending differences represent patterns in this dataset and should not be interpreted as causal relationships. 


## Project Structure 

```text 
Supermarket-Sales-Customer-Analysis/
|
|-README.md
|-SuperMarket Analysis.csv
|-Supermarket_Sales_Customer_Analysis.ipynb
```

## How to Run 

1. Download or Clone this repository. 
2. Open `Supermarket_Sales_Customer_Analysis.ipynb` in Jupyter Notebook or VS Code. 
3. Make sure the `SuperMarket Analysis.csv` file is in the same folder as the notebook. 
4. Run the notebook cells from top to bottom. 

