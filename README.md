# 🛍️ Amazing Mart Sales Insights Dashboard

## 📊 Project Overview

This project analyzes **Amazing Mart's** order data from **January 2011 to November 2013** using **Tableau**. The dashboard provides clear, interactive visualizations to understand order trends, shipping preferences, delivery times, and regional performance.

---

## 🧩 Problem Statement

To explore and analyze Amazing Mart's customer order data and uncover trends across time, geography, and customer segments. The aim is to generate business insights that support better operational decisions and enhance delivery performance.

---

## 📁 Dataset Description

- **Order ID** – Unique order reference  
- **Order Date** – Date order was placed  
- **Ship Date** – Date order was shipped  
- **Customer Name** – Customer’s name  
- **Segment** – Customer segment (Consumer, Corporate, Home Office)  
- **Country / State / City / Region** – Geographic details of customer  
- **Ship Mode** – Shipping method (Economy, Priority, etc.)  
- **Calculated Field**:  
  - `Delivery Time = Ship Date - Order Date`

---

## 🛠️ Steps Followed

- ✅ **Data Import & Cleaning** – Loaded the dataset in Tableau and cleaned formats  
- ⏱ **Calculated Field** – Created `Delivery Time` column  
- 📍 **Geographic Hierarchy** – Built Country → State → Region → City  
- 📈 **Trend Analysis** – Monthly and quarterly order trends visualized  
- 🗺 **Filled Maps** – For region-wise state count and delivery time by country  
- 📊 **Bar Charts & Pie Charts** – Used for shipping segment comparison and quarterly order analysis

---

## 📸 Dashboard Preview

![Amazing Mart Dashboard](https://github.com/pabbasathwik/Amazing-Mart-Order-Sales-Dashboard/blob/main/Amazing%20Mart%20Order%20Dashboard.png)

---

## 💡 Key Insights

- 📅 **Monthly Orders**: Peaked at **127** in July 2012, lowest at **35** in Jan 2011  
- 📆 **Quarterly Trends**:  
  - **Q3** has the highest order volume (**1,279 orders**)  
  - **Q1** has the least (**725 orders**)  
- 🚚 **Shipping Preference**:  
  - **Economy** is the most used shipping mode  
  - **Consumers** dominate all shipping modes
- 🌍 **Geographic Insights**:  
  - Maps show delivery time varies by country  
  - Regional map highlights the number of states per region  
- ⏱ **Average Delivery Time**: Calculated and formatted to 1 decimal precision

---

## ✅ Recommendations

1. **Optimize Shipping**  
   - Focus on standardizing delivery times in high-delay regions  
2. **Segment-Based Promotions**  
   - Target *Corporate* and *Home Office* segments with incentives  
3. **Quarterly Strategy Planning**  
   - Leverage Q3 for new product launches and marketing pushes  

---

## 📁 Files Included

- `Amazing Mart Order Dashboard.twbx` – Tableau Dashboard  
- `Amazing Mart Orders.dataset.xlsx` – Cleaned dataset  
- `Amazing Mart Order Dashboard.png` – Dashboard image  

---

## 🙋‍♂️ About Me

I'm **Sathwik Pabba**, a Data Analyst with strong skills in **Tableau**, **Power BI**, **SQL**, **Python**, **Pandas**, **NumPy**, **MongoDB**, and **Excel**. I enjoy working with real-world datasets to build dashboards and derive actionable insights.

🔗 [GitHub Profile](https://github.com/pabbasathwik)

---

## 📣 Connect with Me

- 💼 [LinkedIn](https://linkedin.com/in/sathwikpabba)  
- 📧 Email: [sathwikpabba18@gmail.com](mailto:sathwikpabba18@gmail.com)

If you found this project helpful, ⭐ star the repo and explore my other dashboards and analysis projects on GitHub!

> “Without data, you're just another person with an opinion.” – W. Edwards Deming 📊
