# **☕ Coffee Sales: Data Standardization & Interactive Reporting Project**

This project covers the full process of taking raw coffee sales data and turning it into a clean, automated report in Excel. I connected separate tables for customers and products and built an interactive dashboard that makes it easy to track sales performance at a glance.

---

### **🏗️ Data Preparation & Standardization**
Before making the charts, I organized the background data so the entire system would work correctly:

* **`Connecting Tables`**: I used **XLOOKUP** and **INDEX/MATCH** to pull customer details and product prices into the main **Orders sheet**, which served as the master dataset for the project.
* **`Standardizing Data`**: I used **IF** statements to standardize shorthand codes (like changing 'M' to 'Medium' and 'Rob' to 'Robusta'), ensuring the data was consistent and easy to read.
* **`New Calculations`**: I created a formula to calculate total sales per order and ensured all pricing was formatted as currency.

---

### **📊 Automated Sales Reports**
I used **pivot tables** to summarize the data into three main areas for the dashboard:

* **`Sales Trends`**: A line chart that shows how different coffee types performed month-by-month.
* **`Top Countries`**: A bar chart showing which countries brought in the most revenue.
* **`Top Customers`**: A list identifying the 5 highest-spending customers.
* **`Interactive Filters`**: I added **Slicers** and a **Timeline** so anyone can filter the data by roast type, package size, or date without needing to edit the spreadsheet.
