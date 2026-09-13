# E-Commerce Data Analysis

## Business Insights & Action Plan

---

## 1. Project Overview

This project analyzes an e-commerce business using SQL to understand:

* Revenue and sales performance
* Product and category performance
* Customer behavior
* Retention and churn
* Purchase patterns
* Operational performance

The analysis covers **52 business questions** and converts SQL findings into practical business recommendations.

**Approach:**
**Business Question → SQL Analysis → Finding → Business Insight → Action**

---

## 2. Business Objectives

The analysis focused on:

* Measuring revenue, orders and Average Order Value
* Identifying high-performing cities, products and categories
* Understanding customer and repeat-purchase behavior
* Identifying high-value and churn-risk customers
* Analyzing customer retention and RFM segments
* Understanding order cancellations
* Identifying growth opportunities and business risks

---

## 3. Dataset & Methodology

The project uses four main tables:

* **Customers** – customer details, city and gender
* **Orders** – order date, customer and order status
* **Order Items** – quantity and unit price
* **Products** – product and category information

### SQL Techniques Used

* Joins
* GROUP BY & HAVING
* Aggregate Functions
* CASE Statements
* CTEs
* Subqueries
* Window Functions
* LAG / LEAD
* DENSE_RANK
* Date Functions
* DATEDIFF
* Customer Segmentation
* RFM Analysis

---

# 4. Overall Business Performance

| KPI                 |   Result |
| ------------------- | -------: |
| Total Revenue       | ₹3.96 Cr |
| Total Orders        |    2,000 |
| Customers           |       90 |
| Products            |       38 |
| Average Order Value |  ₹19,777 |
| Repeat Customers    |       80 |
| Orders > ₹10,000    |    1,066 |
| Churn Rate          |       5% |
| Cancellation Rate   |      12% |

### Key Finding

The business generates strong revenue with a high-value order pattern and strong repeat-purchase behavior.

### Action

Focus on **customer retention, high-value customers, upselling and cross-selling** rather than relying only on new customer acquisition.

---

# 5. Sales & Revenue Analysis

### Key Findings

* **June 2026** generated the highest monthly revenue: **₹51.71 lakh**
* **Delhi** generated the highest city revenue: **₹54.35 lakh**
* **Electronics** contributed **63.77% of total revenue**
* **Smartphone X12** contributed **22.77% of total revenue**
* Smartphone X12 generated approximately **₹90.06 lakh**
* Male customers generated slightly higher revenue than female customers

### Recommended Actions

* Analyze what drove the June revenue peak and replicate successful strategies
* Use Delhi as a benchmark for lower-performing cities
* Protect Electronics inventory and availability
* Promote complementary products around Smartphone X12
* Use customer segments for personalized campaigns

---

# 6. Product & Category Analysis

### Key Findings

**Top-Selling Product**

* Smartphone X12 – **474 units**
* Followed by Fiction Novel Pack and Badminton Racket

**Category Performance**

* Electronics – **₹2.52 Cr**
* Books – **₹5.92 lakh**

**Fastest-Growing Category**

* Books – **31.85% average monthly growth**

**Highest Revenue Product**

* Smartphone X12 – **₹90.06 lakh**

**Lowest Revenue Product**

* Self-Help Bestseller – **₹1.36 lakh**

**Frequently Purchased Together**

* Mechanical Keyboard + Fiction Novel Pack

### Recommended Actions

* Maintain inventory for high-demand products
* Create bundles around frequently purchased products
* Improve visibility of low-performing products
* Test promotions for weaker categories
* Invest selectively in Books because of its strong growth

---

# 7. Customer Analysis

### Key Findings

* **80 customers** made repeat purchases
* **Rahul Iyer** was the highest-value customer with **₹16.74 lakh** spend
* Most customers purchased from multiple categories
* **January 2025** had the highest new customer acquisition with **19 customers**

### Recommended Actions

* Create a VIP segment for high-value customers
* Use loyalty rewards and personalized offers
* Build cross-category recommendations
* Analyze what drove January's acquisition spike
* Replicate successful acquisition strategies

---

# 8. Purchase & Retention Analysis

### Key Findings

* Average repurchase gap: **23–24 days**
* Monthly active customers increased from **19 in Jan 2025 to 63 in Jul 2026**
* July 2026 active customers grew approximately **125% YoY**
* Approximately **13–14 customers** were identified as churn-risk
* Customer churn rate: **5%**

### Recommended Actions

* Trigger personalized reminders around the 23–24 day repurchase window
* Prioritize high-value churn-risk customers
* Build automated reactivation campaigns
* Continue monitoring monthly active customers
* Strengthen loyalty and retention programs

---

# 9. RFM Analysis

RFM was used to segment customers based on:

* **Recency** – How recently they purchased
* **Frequency** – How often they purchased
* **Monetary** – How much they spent

### Key Segments & Actions

| Segment            | Action                               |
| ------------------ | ------------------------------------ |
| High-Value / Loyal | VIP rewards & exclusive offers       |
| Potential Loyal    | Encourage next purchase              |
| At-Risk            | Re-engagement campaigns              |
| High-Value At-Risk | High-priority personalized retention |
| New Customers      | Encourage second purchase            |

---

# 10. Operational Performance

### Finding

**12% of orders were cancelled.**

### Business Problem

The cancellation rate is significant and may indicate issues related to inventory, payment, delivery or customer cancellations.

### Recommended Actions

Analyze cancellations by:

* Product
* Category
* City
* Order value
* Customer type
* Time period
* Cancellation reason

The goal should be to identify and fix the **root cause**, rather than only monitoring the cancellation rate.

---

# 11. Major Business Problems & Opportunities

| Business Issue                  | Recommended Action                                |
| ------------------------------- | ------------------------------------------------- |
| Electronics = 63.77% revenue    | Diversify revenue across categories               |
| Smartphone X12 = 22.77% revenue | Protect inventory and create complementary offers |
| 13–14 churn-risk customers      | Launch targeted reactivation                      |
| 12% cancellation rate           | Identify and fix cancellation causes              |
| New customer acquisition slowed | Replicate successful acquisition strategies       |
| Books = ₹5.92L revenue          | Test targeted growth initiatives                  |
| Repurchase cycle = 23–24 days   | Use time-based retention campaigns                |

---

# 12. Priority Action Plan

### High Priority

1. Reduce order cancellations by identifying root causes.
2. Retain high-value and churn-risk customers.
3. Protect inventory for Electronics and Smartphone X12.
4. Strengthen repeat-purchase and loyalty strategies.

### Medium Priority

5. Use the 23–24 day repurchase cycle for targeted reminders.
6. Diversify revenue beyond Electronics.
7. Test growth initiatives for Books.
8. Replicate successful customer acquisition strategies.

---

# 13. Recommended KPI Dashboard

### Revenue

* Total Revenue
* Monthly Revenue
* MoM Growth
* Average Order Value
* Revenue by City
* Revenue by Category
* Revenue by Product

### Customer

* New Customers
* Returning Customers
* Repeat Purchase Rate
* Monthly Active Customers
* Churn Rate
* Churn-Risk Customers
* Customer Lifetime Value

### Product

* Units Sold
* Top Products
* Low-Performing Products
* Category Revenue
* Category Growth

### Operations

* Total Orders
* Delivered Orders
* Cancelled Orders
* Cancellation Rate
* High-Value Orders

---

# 14. Conclusion

The analysis shows that the business has:

* Strong revenue performance
* High Average Order Value
* Strong repeat-purchase behavior
* Growing customer activity
* Strong Electronics performance
* Significant high-value customers

At the same time, the major opportunities are:

* Reducing dependence on Electronics and Smartphone X12
* Improving new customer acquisition consistency
* Retaining churn-risk customers
* Using repurchase timing for retention
* Growing promising categories such as Books
* Reducing the 12% cancellation rate

Overall, this project demonstrates how SQL can be used to move from **raw transactional data to business insights, problem identification and actionable recommendations**.

---

## 15. Project Files

* `ecommerce_SQL_Data_Analysis.sql` – SQL queries, business questions and analysis
* `E-Commerce Business Questions.pdf` – Business questions
* `Business_Insights_and_Action_Plan.md` – Consolidated findings and recommendations

---

**Analytics:** Revenue Analysis, Customer Analysis, Product Analysis, Retention, Churn, RFM, Operational Analysis, Business Recommendations
