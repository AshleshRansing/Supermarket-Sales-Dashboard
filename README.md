# Supermarket-Sales-Dashboard
Power BI Dashboard


📌 **Project Overview**

This dataset provides synthetic yet realistic sales transaction data from a supermarket. It's designed to help you build interactive dashboards and perform exploratory data analysis on various dimensions like product categories, branches, payment methods, and customer behavior.



📁 **Dataset File**

 **Filename**: `Supermarket_Sales.xlsx`
 **Rows**: \~250–300
 **Format**: Excel (.xlsx)



📊 **Dataset Columns**

| Column Name      | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| Invoice ID       | Unique invoice code per transaction                             |
| Date             | Date of transaction                                             |
| Branch           | Supermarket branch (e.g., A, B, C)                              |
| City             | City of the branch (e.g., Mumbai, Delhi, etc.)                  |
| Customer Type    | New or Returning customer                                       |
| Gender           | Gender of the customer                                          |
| Product Category | Category of the product sold (e.g., Food, Electronics, Fashion) |
| Product Name     | Specific product name                                           |
| Unit Price       | Price per unit of product                                       |
| Quantity         | Number of units purchased                                       |
| Total Sales      | Total = Unit Price × Quantity                                   |
| Payment Method   | Payment mode used (Cash, Credit Card, UPI, etc.)                |
| VAT (5%)         | Tax applied on total sales                                      |
| Rating           | Customer satisfaction rating (1–10)                             |


💡 **Usage Ideas**

* Build Power BI / Tableau dashboards to monitor daily and monthly sales trends
* Analyze which product categories drive the most revenue
* Discover peak sales days or hours using time-series analysis
* Understand customer satisfaction through rating averages per branch or category
* Compare performance across multiple supermarket branches


🛠️ **Tools You Can Use**

 **Excel**: Pivot Tables, Power Query, Dashboards
 **Power BI / Tableau**: For full-scale dashboards and visual storytelling
 **Python**: Pandas, Matplotlib, Seaborn for analysis and visuals


### 📈 Key Insights You Can Derive

1. **Branch Performance**

   * Identify top-performing branches by total sales or quantity sold.
   * Compare average transaction value between different cities.

2. **Product Insights**

   * Highlight best-selling product categories or individual products.
   * Analyze profit contributions by category (based on Total Sales and VAT).

3. **Customer Behavior**

   * Compare behavior between new and returning customers (e.g., do returning customers spend more?).
   * Look at gender-based buying patterns.

4. **Payment Trends**

   * Identify most-used payment methods—helps guide POS or fintech integrations.
   * Correlate payment methods with customer satisfaction ratings.

5. **Sales by Time**

   * Understand daily/weekly trends for promotions and inventory management.
   * Detect seasonal buying behavior or peak periods.

6. **Customer Satisfaction Analysis**

   * Use the rating column to determine satisfaction per branch or category.
   * Cross-reference rating with product or payment type to find issues.


