# E-Commerce Data Analytics Project

This project analyzes over 99,000 sales transactions from an e-commerce platform in Brazil (Olist). It covers the full data process: cleaning raw data with Python, managing and querying data in MySQL, and building an interactive dashboard in Power BI.

---

## 📸 Dashboard Preview

![Dashboard Screenshot](dashboard/dashboard_preview.png)

---

## 🛠️ Tools Used

* **Python:** Pandas, SQLAlchemy (Data cleaning & loading into MySQL)
* **Database:** MySQL Workbench (SQL queries)
* **Visualization:** Power BI Desktop (Dashboard & DAX formulas)

---

## 💡 Key Results & Findings

* **Total Delivered Sales:** $13.22M+ across 96K+ delivered orders.
* **Average Order Value (AOV):** $136.68 per order.
* **Top Categories:** `health_beauty`, `watches_gifts`, and `bed_bath_table` made up over 30% of total revenue.
* **Top Region:** São Paulo (`SP`) generated the highest order volume and sales.

---

## 📁 Files in This Repository

* `01_etl_pipeline.ipynb` – Python notebook for loading and cleaning the CSV datasets.
* `02_analytics_queries.sql` – SQL file containing queries for revenue growth and category analysis.
* `olist_dashboard.pbix` – Power BI dashboard file.
* `dashboard_preview.png` – Screenshot of the final dashboard.

---

## 🚀 How to Run

1. Open `01_etl_pipeline.ipynb` in Jupyter Notebook, add your MySQL password, and run the cells to upload the data into your MySQL server.
2. Open `02_analytics_queries.sql` in MySQL Workbench to run the SQL calculations.
3. Open `olist_dashboard.pbix` in Power BI Desktop to view or interact with the dashboard.
