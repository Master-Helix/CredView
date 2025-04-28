# CredView
Created an interactive **Power BI dashboard** that provides deep insights into credit card usage patterns, spending, and financial trends.

---

## 🔧 Tech Stack

- **Database**: PostgreSQL
- **Data Visualization**: Power BI
- **Data Export**: Microsoft Excel
- **Data Query Language**: SQL
- **Other Skills**: DAX Queries

---

## ⚙️ Project Setup

1. **Database Setup (PostgreSQL)**  
   - Create a PostgreSQL database for Credit Card data.
   - Upload transactional and customer datasets using `.csv` files or SQL insert scripts.
   - Tables Example:
     - `customer.csv`
     - `credit_card`
   - Performed data cleaning and transformations via SQL queries.
   - Performed addition of data in real-time with the data files labelled as `cc_add.csv` and `cust_add.csv`

2. **Connect PostgreSQL to Power BI**  
   - Use the **PostgreSQL connector** inside Power BI.
   - Import necessary tables and views.
   - Perform additional modeling (relationships, calculated columns, and measures) along with **DAX Queries** to create new columns and generate valuable insights.

3. **Build Power BI Dashboard**  
   - Create custom visuals like:
     - KPI Cards (e.g., Total Spend, Transaction Value, Total Revenue, Average Customer Satisfaction Score)
     - Customer Segmentation
     - Credit Utilization by Card Type

4. **Export Data to Excel**  
   - Export processed and visualized data tables to Excel via Power BI options.
   - Share reports for non-Power BI users.

---

## 📊 Key Insights

- Revenue increased by **28.8%**
- Overall revenue is **57M**
- Total interest is **8M**
- Total transaction amount is **46M**
- Male customers are contributing more in revenue, **31M, female 26M**
- Blue & Silver credit cards are contributing to **93%** of overall transactions
- TX, NY & CA are contributing to **68%**
- Overall Activation rate is **57.5%**
- Overall Delinquent rate is **6.06%**

---

## 🚀 Future Improvements

- Integrate real-time data refresh using scheduled PostgreSQL connections.
- Build a mobile-optimized version of the dashboard.
- Add predictive analytics (e.g., churn prediction based on spend patterns).

---

# 
**If you like this project, feel free to ⭐ the repository and connect!**
