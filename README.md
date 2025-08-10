# Coffee-Shop-Sales-Profitability-Analysis

<img width="1038" height="664" alt="image" src="https://github.com/user-attachments/assets/2c86c5ce-88db-4bc5-ab82-c118faee9156" />


## 1. Project Overview
This project presents a comprehensive, end-to-end data analysis of a coffee shop's sales data. The primary objective was to move beyond surface-level revenue metrics to uncover the core drivers of profitability. The analysis involves a full data science workflow:

*   **Data Cleaning & Processing:** Using Python with the `pandas` library to clean and prepare raw sales data for analysis.
*   **Exploratory Data Analysis (EDA):** Visualizing data with `matplotlib` and `seaborn` to identify key trends in product sales, store performance, and customer behavior over time.
*   **Profitability Modeling:** Building a predictive model with `scikit-learn` to determine the most influential factors affecting profit.
*   **Interactive Dashboarding:** Creating a dynamic, user-friendly dashboard in Tableau to present the findings to non-technical stakeholders and empower data-driven decision-making.

The final output is not just a collection of charts, but a set of actionable business strategies grounded in data, designed to boost profit margins and mitigate losses.

## 2. Project Objectives
*   To clean and validate the provided sales dataset to ensure analytical accuracy.
*   To perform a detailed profit/loss analysis to identify the most and least profitable products.
*   To utilize predictive modeling to understand the key factors contributing to profitability.
*   To develop actionable strategies to increase profit margins and mitigate losses.
*   To consolidate all findings into an interactive business intelligence dashboard.

## 3. Tools & Libraries Used
*   **Programming Language:** Python 3
*   **Python Libraries:**
    *   `pandas`: For data manipulation and cleaning.
    *   `numpy`: For numerical operations.
    *   `matplotlib` & `seaborn`: For data visualization.
    *   `scikit-learn`: For predictive modeling (Random Forest Regressor).
    *   `google.colab`: For running the Python notebook in a cloud environment.
*   **Business Intelligence Tool:** Tableau Desktop

## 4. Key Findings & Insights

The analysis yielded several critical insights that can directly inform business strategy:

*   **Product Profitability:** Specialty coffees and teas are the primary profit drivers, contributing significantly more to the bottom line than baked goods, some of which have very low profit margins.
*   **Store Performance:** There is a clear performance disparity between store locations, with the Hell's Kitchen and Astoria branches generating the majority of the total revenue.
*   **Peak Operational Hours:** Sales data shows a consistent and significant peak in customer traffic and revenue between 8 AM and 11 AM daily.
*   **Key Profit Drivers:** The predictive model confirmed that `unit_price`, `transaction_qty`, and `product_category` are the most important factors in determining a transaction's profitability.

## 5. Actionable Recommendations

Based on the analysis, the following strategies are recommended to enhance profitability:

1.  **Focus Marketing on Top Products:** Launch targeted marketing campaigns and in-store promotions for the top 5 most profitable products to maximize sales of high-margin items.
2.  **Optimize Staffing for Peak Hours:** Adjust staff schedules to ensure maximum coverage during the proven 8-11 AM rush, improving service speed and capturing all potential revenue.
3.  **Re-evaluate Underperforming Products:** Conduct a pricing and cost review for the 5 least profitable items. Consider bundling them with best-sellers or replacing them on the menu if they remain unprofitable.
4.  **Replicate Success:** Analyze the operational strategies, layout, and local marketing of the top-performing stores (Hell's Kitchen, Astoria) and apply these learnings to other locations.

## 6. How to View the Interactive Dashboard

The primary deliverable of this project is the interactive Tableau dashboard. To view and interact with it, please follow these steps:

1.  **Download the Tableau Workbook:** Download the `Coffee_Shop_Sales_Dashboard.twbx` file from this repository.
2.  **Install Tableau:** If you do not have Tableau, you can download the free [Tableau Reader](https://www.tableau.com/products/reader) to open the file.
3.  **Explore:** Open the `.twbx` file. You can now click on any product, store, or data point to filter the entire dashboard and explore the data for yourself.

## Author
Izaz khan || Artificial Intelligence
