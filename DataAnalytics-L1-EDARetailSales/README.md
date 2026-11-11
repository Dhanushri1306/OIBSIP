# Exploratory Data Analysis on Retail Sales Data

## Internship

Oasis Infobyte Internship – Data Analytics

## Task

Level 1 – Task 1: Exploratory Data Analysis on Retail Sales Data

## Objective

Perform Exploratory Data Analysis (EDA) on an e-commerce retail dataset to identify sales patterns, customer behaviour trends, product performance, revenue distribution and actionable business insights.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Description

The project uses the Indian E-Commerce Customer & Order Intelligence Dataset, obtained from Kaggle.

The dataset contains five files used in this analysis:

- `customers.csv` – Customer demographic and purchasing information.
- `products.csv` – Product details, categories and pricing information.
- `orders.csv` – Order dates, statuses and related information.
- `order_items.csv` – Product quantities, revenue, costs and profit.
- `data_dictionary.csv` – Dataset column descriptions.

The dataset covers the period from January 2023 to December 2025.

Note: The dataset is synthetic and does not represent actual customer transactions or real Indian e-commerce market behaviour.

## Project Structure

- `dataset/` – Dataset CSV files and original dataset documentation.
- `screenshots/` – Project visualisations and output screenshots.
- `retail_sales_eda.ipynb` – Complete exploratory data analysis notebook.
- `README.md` – Project documentation.

## Analysis Performed

1. Data Loading and Initial Inspection – Examined dataset dimensions, column data types and missing values.
2. Descriptive Statistical Analysis – Calculated mean, median, mode and standard deviation for numerical variables.
3. Time Series Analysis – Analysed monthly and quarterly gross revenue trends using line charts.
4. Customer Demographics – Examined customer age-group distribution and gender breakdown.
5. Product Analysis – Identified the top 10 best-selling products and analysed revenue by product category.
6. Correlation Analysis – Used a correlation matrix and heatmap to examine relationships between numerical variables.
7. Additional Visualization – Analysed total profit across product categories to identify differences in profitability.

## Key Findings

- The dataset contains 25,000 customers, 550 products, 100,000 orders and 254,331 order items.
- The highest monthly gross revenue was recorded in December 2025.
- Customers aged 25–34 form the largest age group.
- Chanda Deluxe Winter Wear was the best-selling product, with 14,178 units sold in delivered orders.
- Electronics generated the highest category-wise gross revenue, approximately ₹99.43 crore.
- Fashion generated the highest total profit, approximately ₹3.75 crore.
- Electronics generated the highest revenue but ranked seventh in total profit.
- A negative correlation of approximately -0.33 was observed between item discount percentage and profit.

## Business Recommendations

- Prioritise high-profit categories such as Fashion, Home & Kitchen and Footwear.
- Review pricing, supplier costs and discount strategies to improve Electronics profitability.
- Develop targeted marketing campaigns for the largest customer segment.
- Monitor inventory levels of the best-selling products.
- Investigate seasonal sales patterns to improve inventory and promotional planning.

## Conclusion

The project successfully explored customer demographics, sales trends, product performance, category-wise revenue and profitability. The findings highlight the importance of considering both revenue and profit when making business decisions. The analysis provides useful insights for inventory planning, pricing strategies, customer targeting and business performance improvement.

## How to Run the Project

1. Install Python and Visual Studio Code.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn jupyter ipykernel`

3. Open the project folder in Visual Studio Code.
4. Open `retail_sales_eda.ipynb`.
5. Select a Python kernel.
6. Run all notebook cells to reproduce the analysis and visualisations.

## Dataset Source

Indian E-Commerce Customer & Order Intelligence Dataset – Kaggle.

The dataset is released under the CC0 1.0 Public Domain Dedication, as specified in its original documentation.