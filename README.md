# Sales Data Visualization

## Project Overview
This project involves exploring and visualizing a sales dataset to derive insights into the sales trends over time and across different regions and product categories. The dataset was cleaned and preprocessed to handle missing values, ensure consistency, and then visualized to highlight various trends in the sales data.

## Dataset
The dataset used in this project is from a sales records file (sales_data.csv) which can be found at:
https://drive.google.com/file/d/1WvVLbY2CAcu8qpXMnXconDRHEuzpanGP/view?usp=drive_link

## Key Insights
Data Cleaning & Preprocessing
Handling Missing Values:
- Filled missing values in columns like STATE, TERRITORY, and POSTALCODE with placeholder values like 'Unknown' and '00000'. This was done to avoid introducing inaccuracies through mean or median imputation.
- ADDRESSLINE2 was ignored as it was deemed unnecessary for analysis.

Converting Data Types:
- The ORDERDATE column was converted into a datetime format for easier analysis.

Creating Additional Features:
- A new column, Month, was derived from the ORDERDATE column to group sales by month for time-based analysis.

## Data Aggregation & Visualization
- Monthly Sales: The total sales per month were aggregated and visualized with a line plot to show sales trends over time.

- Sales by Country: A bar plot displayed total sales across different countries, highlighting the key markets.

- Sales by Product Line: A bar plot visualized the distribution of sales across various product lines.

- Sales by Deal Size: A bar plot compared sales based on deal size to identify trends in small vs. large deals.

- Correlation Analysis: A heatmap showed the relationships between sales, quantity ordered, price, and MSRP.

- Sales vs. Quantity Ordered: A scatter plot was created to explore how sales correlate with the quantity of products ordered.

- Product Category vs. Deal Size: A stacked bar plot visualized the sales distribution across different product categories and deal sizes.

## Tools and Libraries Used
- Pandas
- Matplotlib
- Seaborn
- Google Colab
