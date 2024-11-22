# T-Shirt & Hoodie Sales Data Analysis and Visualization

## Project Overview

This project analyzes t-shirt and hoodie sales data using three datasets: **Customer Data**, **Sales Data**, and **Product Data**. The goal of the analysis was to uncover trends in sales performance, customer behavior, and product profitability. By cleaning and transforming the data using **SQL** and **Python**, and visualizing insights with **Tableau**, I identified actionable business recommendations to optimize profitability and guide strategic decisions.

---

## Datasets

The project integrates data from the following sources:
1. **Customer Data**: Details about customers, including demographics and membership status.
2. **Sales Data**: Records of individual sales transactions, including date, item, quantity, price, and customer ID.
3. **Product Data**: Information about product attributes such as type (e.g., shirt or hoodie), size, color, material, and price.

---

## Workflow and Tools Used

### 1. **Data Cleaning and Transformation**

#### SQL
- Removed duplicates and handled missing values to ensure data integrity.
- Standardized and normalized data fields (e.g., consistent date formats and price representations).
- Joined datasets:
  - **Sales Data** and **Product Data** were merged based on a shared key to create a unified dataset for analysis.
<img width="1440" alt="Screenshot 2024-11-22 at 7 03 58 AM" src="https://github.com/user-attachments/assets/49825acb-abd6-4ac7-96ed-a1e9da5c92d2">

#### Python & Pandas
- Post-SQL, used Python for further data transformation and analysis:
  - Grouped and aggregated data to identify trends in sales and customer preferences.
  - Calculated key metrics such as:
    - **Profitability by product type** (e.g., shirts vs. hoodies).
    - **Customer purchasing behavior**, including rewards membership impact.
    - **Return and exchange rates** by product.
    - Revenue breakdown by size, material, and color.
  - Derived insights on profitability relative to production costs and base prices.
<img width="1440" alt="Screenshot 2024-11-22 at 7 30 03 AM" src="https://github.com/user-attachments/assets/99b9c3fa-c8f9-40d7-8e73-437f8587a8bc">

---

### 2. **Data Analysis & Insights**

Using the cleaned data, I uncovered several valuable insights:

1. **Top Products**:
   - Identified the most profitable items based on sales trends, factoring in type, color, material, and size.

2. **Customer Behavior**:
   - Compared purchasing patterns of rewards members versus non-members.
   - Identified customers with the highest lifetime value to target retention efforts.

3. **Product Performance**:
   - Analyzed the profitability of products relative to their base prices and production volumes.
   - Discovered product categories (e.g., materials or colors) that performed better based on revenue and customer preferences.

4. **Returns & Exchanges**:
   - Highlighted products with the highest return/exchange rates, offering insights into potential quality or satisfaction issues.

---

 3. **Data Visualization**

#### Tableau Dashboards
I created an interactive Tableau dashboard to visualize the analysis, including:
- **Sales Performance**:
  - Profitability by product type, size, color, and material.
  - Trends in revenue generation by category.
- **Customer Insights**:
  - Purchasing patterns and rewards membership analysis.
  - Customer segmentation by behavior and value.
- **Product Returns/Exchanges**:
  - Visualizations highlighting frequently returned items and possible causes.
- **Profitability Metrics**:
  - Comparative analysis of product profitability relative to base prices.

---<img width="1440" alt="Screenshot 2024-11-22 at 7 02 25 AM" src="https://github.com/user-attachments/assets/fb74a1d7-94e8-4cb0-bcbb-02759744ed04">


## Tools & Technologies Used

- **SQL**: Data cleaning, transformation, and joining datasets.
- **Python (Pandas, Numpy, Matplotlib)**: Exploratory data analysis, grouping, and calculating custom metrics.
- **Tableau**: Visualization and creation of interactive dashboards.
- **Excel**: Quick cross-checks and summaries.
- **Jupyter Notebooks**: Data exploration and analysis scripting.

---

## Key Features of the Project

- Integrated multiple datasets to provide a holistic view of sales performance and customer behavior.
- Created calculated metrics and insights such as:
  - Profit per unit.
  - Profit as a percentage of base price.
  - Customer loyalty trends.
- Built interactive Tableau dashboards to deliver actionable insights for stakeholders.

---

## File Structure

