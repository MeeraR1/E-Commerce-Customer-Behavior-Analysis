#   E-commerce Customer Behavior Analysis Dashboard

A comprehensive data visualization project focusing on key metrics, sales performance, and consumer habits within an e-commerce ecosystem.

### **  Project Overview**

This repository contains the visual results of an **E-commerce Customer Behavior Analysis** project. The project utilizes data visualization to provide actionable insights into customer purchasing patterns, order metrics, revenue streams, and key performance indicators (KPIs) across various dimensions.

The analysis addresses three core areas:

1. **Revenue Performance:** Total revenue, profit margins, and sales trends over time.
2. **Customer Segmentation:** Analysis by age, gender, and geographical location (Cities).
3. **Operational Metrics:** Average order value, average rating, and order distribution by device type and payment method.

---
**Note on Methodology:** A crucial step in this analysis involved **data enrichment**. The original dataset lacked a direct **Cost Price** column, which was engineered and added to enable the accurate calculation of the **Profit Margin** metric seen in the dashboard.
### **  Key Metrics and Insights**

The visualizations reveal significant findings critical for business strategy:

| Metric Group | Key Visualizations | Notable Insights |
| :--- | :--- | :--- |
| **Financial & Product** | Total Revenue by Product Category, Discount Amount by Product Category, Total Revenue by Month | **Electronics** is the undisputed top revenue generator. Revenue peaks occur in **January**, **February** and **March**. |
| **Customer Behavior** | Total Revenue by Age (bins), Total Revenue by Gender, Total Revenue by Returning Customer | The **20-39 age group** contributes the highest revenue. **Returning customers** account for over **59%** of the total revenue, highlighting the importance of retention.|
| **Operational Efficiency** | Average Rating by Delivery Time, No of Orders by Device Type, Total Revenue by Payment Method | **Cash on Delivery** and **Credit Card** are the dominant payment methods. Most orders originate from **Mobile** devices (2.8K orders). |

---

### **🛠️ Data Methodology**

This section outlines the steps taken to prepare and enhance the dataset before visualization:

* **Data Sourcing & Cleaning:** Standard cleaning procedures were applied to ensure data quality and consistency.
* **Data Enrichment (Feature Engineering):** The original data source **lacked a direct Cost Price column**. To calculate the crucial **Profit Margin** KPI, a **simulated/derived Cost Price column** was generated. 
* **Data Binning:** Continuous variables, specifically **Customer Age** and **Session Duration Minutes**, were converted into discrete **bins** to facilitate clearer trend visualization and customer segmentation analysis.

### **  Technologies Used**

This project showcases the analytical capabilities of a modern data visualization platform.

* **Tool Used:** Microsoft Power BI , Power Query, Excel, DA
* **Data Source:** https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr


---

### **  Visual Assets and Structure**

The screenshots of the dashboard are categorized for easy review:

* `/Images`
    * `Page1.jpg`: Main KPI summary (Revenue, Profit Margin, AOV, Average Rating) and high-level trends.
* `Page2.jpg`: Focus on regional performance (Revenue by City), detailed product/discount analysis, Total Revenue by Returning customer and Total quantity sold by session duration minutes in bins.
    * `Page3.jpg`: Focus on order logistics (Device Type, Delivery Rating) and payment methods, orders by product category and gender.
    

---

### **  Contact**

For questions, feedback, or collaborations related to data analysis and e-commerce insights, please reach out!

* **meerasoorya96@gmail.com**

