# Walmart-Analysis-_SQL-Server



## 📊 Project Overview

This project analyzes Walmart sales data using SQL Server to uncover key business insights such as payment trends, customer preferences, product performance, and revenue changes across branches and years.



## 🎯 Objectives

The main goals of this analysis are to:

Understand customer purchasing behavior.

Identify top-performing categories and branches.

Analyze sales patterns by time, day, and payment method.

Measure branch performance across years.

Provide actionable insights to support decision-making.



## 🧩 Dataset Description

The dataset contains Walmart sales transaction records, including:

Invoice ID

Branch & City

Category

Quantity & Total Sales

Payment Method

Date & Time

Rating

Profit

---

## 🧹 Data Cleaning & Preparation

Before performing any analysis, several cleaning and preparation steps were applied to ensure data accuracy and consistency



**🧩 1. Data Inspection** : Previewed the first few rows to understand the dataset structure and column types.


---

**🔍 2. Checking for Missing Values**: Detected any null or missing values across key fields.


---

**🧼 3. Removing Empty or Invalid Records** : Deleted rows with missing price and quantity values.


---

**📋 4. Detecting Duplicate Records** : Identified duplicate invoices.


---

**🧾 5. Counting Total Duplicate Entries** : Calculated the total number of duplicate records.


---

**🧹 6. Removing Duplicate Rows** :  Removed exact duplicate records using the ROW_NUMBER() method.


---

**💰 7. Creating and Updating Calculated Columns** :  Added calculated columns for Total Sales and Profit for further analysis.




---




## 🧠 Key SQL Questions & Insights

1️⃣ **Payment Methods** : Shows the number of transactions and items sold for each payment method.


---

2️⃣ **Highest-Rated Category per Branch** : Identifies which category received the highest average rating in each branch.


---

3️⃣ **Busiest Day of the Week per Branch** : Finds which day has the highest number of transactions per branch.


---

4️⃣ **Ratings by City and Category** : Shows rating distribution for each category in every city.


---

5️⃣ **Profit by Category** : Ranks product categories by total profit.


---

6️⃣**Most Frequent Payment Method per Branch** : Finds the most commonly used payment method in each branch.


---

7️⃣ **Transactions by Shift (Morning, Afternoon, Evening)** : Analyzes sales distribution across different times of day.


---

8️⃣ **Branches with Decreased Revenue (2022 vs 2023)** : Identifies branches that experienced a revenue decline year-over-year

