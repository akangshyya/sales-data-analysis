# 🎁 End-to-End Sales Data Analysis Dashboard (Excel)

This project features a **comprehensive and interactive sales analysis dashboard** built using advanced Microsoft Excel features. The goal was to transform raw transactional data from **Ferns N Petals (FNP)**, a major online gifting retailer, into actionable business intelligence to drive strategic decisions.

---

## ✨ Project Highlights & Key Features

| Feature | Description | Technical Tools Used |
|---------|-------------|--------------------|
| **Data Engineering (ETL)** | Used Power Query Editor to ingest data from multiple sources, perform rigorous cleaning, shape columns, and apply necessary transformations. | Power Query, M Language |
| **Data Modeling** | Built a relational Star Schema model in Power Pivot, linking the Fact table (Orders) to Dimension tables (Customers, Products). | Power Pivot, Data Model |
| **KPI & Metrics Calculation** | Developed custom Key Performance Indicators (KPIs) and calculated fields, such as Total Revenue, Average Order Value, and Order-to-Delivery Time using DAX. | DAX (Data Analysis Expressions) |
| **Interactive Dashboard** | Designed a dynamic single-screen dashboard with Pivot Charts, Slicers, and Timelines to allow users to filter data in real-time. | Pivot Charts, Slicers, Timelines |

---

## 📈 Key Business Insights Delivered

The dashboard provides real-time answers to crucial business questions:

- **Sales Performance by Occasion:** Identified which festivals (e.g., Rakshabandhan, Diwali) generate the highest revenue and average customer spend.  
- **Monthly Trend Analysis:** Visualized revenue trends over time to forecast demand and optimize inventory.  
- **Top Revenue Drivers:** Pinpointed the Top 5 Products and Product Categories contributing the most to overall revenue.  
- **Customer Logistics:** Calculated the Average Delivery Time and analyzed order quantity's correlation with delivery duration.  
- **Geographic Focus:** Ranked the Top 10 Cities by order count to inform regional marketing efforts.  

---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `Sales_Dashboard_Final.xlsx` | The completed Excel project file, containing all Power Query steps, the Power Pivot data model, DAX formulas, and the final interactive dashboard. |
| `FNP_Executive_Summary.pdf` | A one-page strategic analysis report detailing key findings, conclusions, and data-driven recommendatio
| `dashboard_preview.png` | An image snapshot of the final interactive dashboard. |
| `customers.csv` | Contains customer demographics, including names, cities, contact information, and gender. |
| `orderes.csv` | The Fact Table containing every transaction detail: Order ID, Quantity, order/delivery dates, and location. |
| `products.csv` | Details for each product ID, including product name, category, price, and associated occasion. |

---

## 🛠️ Technology Stack

- **Primary Tool:** Microsoft Excel (Advanced)  
- **Data Preparation:** Power Query Editor  
- **Data Modeling:** Power Pivot  
- **Calculations:** DAX (Data Analysis Expressions)  

---

## 🚀 How to View the Project

1. **Clone the repository**:
    ```bash
    git clone https://github.com/akangshyya/sales-data-analysis.git
    ```
2. **Open the file**: Open `Sales_Dashboard_Final.xlsx` in Microsoft Excel.  
3. **Explore**: Interact with the Slicers (e.g., filter by Occasion) and Timelines (e.g., filter by month) to see the charts and KPIs update dynamically.  

---

⭐ If you found this project insightful, please consider **starring the repository**!
