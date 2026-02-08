# 📊 E-commerce Sales & Fulfilment Analytics Dashboard (Power BI)

## 📌 Project Overview

This project is an interactive **Power BI dashboard** designed to analyze e-commerce order performance across **product categories, shipping states, fulfilment type, courier status, service levels, size demand, and monthly trends**.

The dashboard enables quick business insights into:

* Top-selling categories and SKUs
* High-revenue shipping regions
* Shipping pipeline performance (Shipped, Unshipped, Cancelled, Returned, etc.)
* Revenue loss due to operational issues
* Size-level demand patterns for inventory planning 

---

## 🗂 Dataset Description

The dataset contains transactional order-level information with key fields such as:

* **Order Details:** Order ID, Date, Qty, Amount, currency
* **Product Info:** Category, Style, SKU, Size, ASIN
* **Shipping Info:** ship-city, ship-state, ship-postal-code, ship-country
* **Operations:** Status, Courier Status, ship-service-level
* **Business Channels:** Fulfilment, Sales Channel, fulfilled-by
* **Promotion & Segment:** promotion-ids, B2B

---

## 🎯 Key KPIs Tracked

The dashboard focuses on business-critical KPIs such as:

* **Total Orders (Category Count)**
* **Total Revenue (Sum of Amount)**
* **Monthly Revenue Trend**
* **Monthly Order Trend**
* **Shipped % vs Unshipped %**
* **Cancellation Volume**
* **Revenue Loss by Issue Type**
* **Top Revenue States**
* **Top Categories by Order Volume**
* **Service Level Performance (Standard vs Expedited)**
* **Size-wise Demand Distribution** 

---

## 📈 Dashboard Pages / Visuals Included

The report includes the following analysis views:

### 1) **Category Performance**

* Orders by Category

  * Set (48K), Kurta (47K), Western Dress (14K), Top (10K), Ethnic Dress (1K) 

### 2) **State-wise Sales & Order Status**

* State-wise Sales (Revenue)

  * Maharashtra (12.9M), Karnataka (10.2M) as top states 
* State-wise Order Status Distribution (Shipped vs Unshipped)

### 3) **Shipping Status Overview**

* Overall shipping pipeline breakdown

  * Shipped (63.72%) as majority status 

### 4) **Fulfilment Analysis**

* Fulfilment Type Distribution

  * Amazon (73.46%) vs Merchant (26.54%) 

### 5) **Monthly Trends**

* Monthly Sales Trend (Top 4 Categories)
* Monthly Sales Trend (Low-Sales Categories)
* Monthly Order Trend by Category
* Monthly Shipment Status Trend (Cancelled/Shipped/Unshipped) 

### 6) **Service Level Performance**

* State-wise Revenue by Shipping Service Level (Standard vs Expedited) 

### 7) **Operational Issue Analysis**

* Revenue Loss by Order Issue Type
  (Cancelled, Returned to Seller, Returning to Seller, Rejected by Buyer, Lost in Transit, Damaged) 

### 8) **Size-based Insights**

* Shipping Status Distribution by Size
* Size Demand by Category (M/L/XL/XXL dominating) 

---

## 🔍 Key Insights (Findings)

* **Set and Kurta** are the strongest demand-driving categories, contributing the highest order volume. 
* **Maharashtra and Karnataka** are the top revenue-generating states, making them high-priority regions for operations and inventory. 
* The fulfilment model is dominated by **Amazon fulfilment (73.46%)**, indicating reliance on platform logistics. 
* Shipping pipeline analysis shows the majority of orders are shipped, but cancellations and returns contribute noticeable revenue loss. 
* Standard sizes **M/L/XL/XXL** account for most demand, supporting inventory optimization decisions. 

---

## 🛠 Tools & Skills Used

* **Power BI**
* **Power Query (ETL)**
* **DAX**
* Data Cleaning & Filtering
* Data Modeling
* KPI Reporting
* Business Analytics
* Dashboard Design & Visualization

---

## 🚀 Business Recommendations

* Prioritize stock and marketing focus on **Set and Kurta** categories.
* Strengthen fulfilment operations in top states (**Maharashtra, Karnataka, Telangana, UP, Tamil Nadu**) to reduce unshipped/cancelled orders.
* Use size-level demand insights to optimize inventory for **M/L/XL/XXL** and reduce overstock for low-demand sizes.
* Track cancellation and return reasons for operational improvement and revenue protection. 

