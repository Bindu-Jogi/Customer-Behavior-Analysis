
# 🛒 Customer Behavior Analysis

## 📌 Project Overview

This project demonstrates a **complete, company-level data analytics workflow** using a retail customer dataset. The goal was to analyze customer shopping behavior and generate actionable business insights by combining **Python, SQL, and PowerBI**, then present the results in a portfolio-ready format.

The project follows industry best practices, covering everything from **business problem definition** to **data cleaning, analysis, visualization, and reporting**.

---

## 🎯 Business Objective

A retail company wants to better understand customer purchasing behavior in order to:

* Improve sales performance
* Increase customer engagement and loyalty
* Optimize marketing and product strategies

## 🧩 Dataset Description

The dataset contains customer-level shopping information, including demographics, product details, and purchasing behavior.

**Key Features:**

* `customer_id` – Unique customer identifier
* `age`, `gender`, `location` – Customer demographics
* `item_purchased`, `category`, `size`, `color`, `season` – Product details
* `purchase_amount` – Amount spent
* `review_rating` – Customer feedback
* `subscription_status` – Subscription indicator
* `shipping_type`, `payment_method` – Transaction details
* `discount_applied` – Discount usage
* `previous_purchases` – Number of prior purchases
* `frequency_of_purchases` – Converted from text to numeric days

---

## 🧹 Data Cleaning & Feature Engineering (Python)

* Loaded and explored data using **pandas**
* Standardized column names using **snake_case**
* Handled missing `review_rating` values by imputing the **median rating within each product category**
* Removed redundant column (`promo_code_used`)
* Engineered new features:

  * **Age groups** (young adult, adult, middle-aged, senior)
  * **Numeric purchase frequency** from textual values

---

## 🗄️ SQL Analysis (MySQL)

The cleaned dataset was loaded into a PostgreSQL database and analyzed using SQL to answer real business questions.

**Key Analyses:**

* Revenue by gender
* Average spend by subscription status
* High-spending customers who use discounts
* Top-rated products by average review rating
* Shipping type impact on purchase amount
* Products with highest discount dependency
* Customer segmentation (new, returning, loyal)
* Top-selling products per category (using window functions)
* Subscription behavior among repeat buyers
* Revenue distribution by age group

---

## 📊 PowerBI Dashboard

An interactive PowerBI dashboard was created to communicate insights clearly to stakeholders.

**Dashboard Components:**

* KPI cards: total customers, average purchase amount, average review rating
* Donut chart: subscription status distribution
* Bar and column charts: revenue and sales by category and age group
* Slicers: gender, category, subscription status, shipping type

<img width="1375" height="772" alt="image" src="https://github.com/user-attachments/assets/1c0e18a4-88dc-4541-9940-1e473f1bfe3b" />
<img width="1379" height="853" alt="image" src="https://github.com/user-attachments/assets/c075091a-d459-47f2-bf70-00680d146ec4" />



The dashboard emphasizes **clarity, consistency, and executive-friendly design**.

---

## 📑 Reporting & Presentation

* Documented the full analysis process in a structured project report
* Created a concise, client-ready presentation summarizing key insights and recommendations
* Focused on **business storytelling**, not just technical output

---

## 🛠️ Tools & Technologies

* **Python:** pandas, numpy
* **SQL:** PostgreSQL, SQLAlchemy, psycopg2
* **Visualization:** PowerBI
* **Environment:** Jupyter Notebook
* **Version Control:** Git & GitHub

---

## 🚀 Key Learnings

* End-to-end analytics projects are essential for real-world data roles
* Context-aware data cleaning significantly improves insight quality
* SQL is critical for translating data into business answers
* Dashboards and presentations matter more than raw analysis for stakeholders
