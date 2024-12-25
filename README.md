# FashionHub Data Analysis

## Project Overview
This project analyzes sales data for FashionHub, a clothing store, with a focus on cleaning, transforming, and visualizing the data. The final deliverables include cleaned datasets, a new `Age Group` column, and interactive dashboards that provide actionable insights for decision-making.

---

## Key Steps in the Analysis

### 1. Data Cleaning
- **Gender Column:**
  - Corrected inconsistent entries:
    - `w` converted to `Women`
    - `m` converted to `Men`
- **Quantity Column:**
  - Standardized inconsistent values:
    - `1` was replaced with `one`
    - `two` was replaced with `2`
- Verified and rectified missing or erroneous data for all columns.

### 2. Data Transformation
- **Age Grouping:**
  - Added a new column `Age Group` using the formula:
    ```excel
    =IF(E2>50,"Senior",IF(AND(E2<=50,E2>=30),"Adult","Teenager"))
    ```
  - Classified individuals into:
    - `Senior` (Age > 50)
    - `Adult` (30 ≤ Age ≤ 50)
    - `Teenager` (Age < 30)

### 3. Pivot Tables and Dashboards
- Created pivot tables to compare:
  - **Orders and Sales by Month**
  - **Orders and Sales by Channel**
  - **Orders by Age and Gender**
- Designed interactive pivot charts and dashboards:
  - **Top 5 Sales States**
  - **Sales Distribution by Gender**
  - **Order Status Overview**
  - **Sales Contribution by Channels**
  - **Orders vs Sales Trends**
  - **Orders Breakdown by Age and Gender**

---

## Insights from the Dashboards

1. **Sales by States:**
   - The top-performing states are:
     - **Maharashtra** with the highest sales.
     - **Karnataka** and **Tamil Nadu** follow closely.

2. **Sales by Channels:**
   - **Amazon** is the top sales channel, contributing 35% of total sales.
   - Other major contributors:
     - **Flipkart (22%)**
     - **Myntra (23%)**
     - **Nalli and Meesho (5% each)**

3. **Order Status:**
   - A majority (92%) of orders were **delivered** successfully.
   - Refunds, returns, and cancellations collectively accounted for only 8% of orders.

4. **Sales by Gender:**
   - Women account for 64% of sales, significantly outpacing men at 36%.

5. **Orders vs Sales Trends:**
   - Orders and sales peaked in the early months of the year (e.g., March-April).
   - A gradual decline in orders was observed toward the year-end (e.g., September-December).

6. **Orders by Age and Gender:**
   - **Adults** (30–50 years) form the largest customer segment:
     - 35% of total orders (Women dominate this category).
   - **Teenagers** and **Seniors** contribute less but show a balanced gender distribution.

---

## Tools and Techniques
- **Microsoft Excel** for data cleaning, transformation, and visualization.
- **Pivot Tables and Charts** for summarizing and visualizing key metrics.
- **Dashboards** for presenting insights interactively.

---

## Usage
1. Open the cleaned dataset or dashboards in the Excel file.
2. Use slicers to filter by:
   - **Month**
   - **Sales Channel**
   - **Product Category**
3. Analyze performance by viewing interactive visualizations of sales, orders, and demographics.

---

## Recommendations for FashionHub
- **Focus on Amazon** to drive sales further, as it’s the leading sales channel.
- **Target Women** in marketing campaigns, given their higher contribution to sales.
- **Promote in Maharashtra** and other high-performing states while exploring strategies for underperforming regions.
- **Expand offerings for Adults,** the largest customer segment.

---

