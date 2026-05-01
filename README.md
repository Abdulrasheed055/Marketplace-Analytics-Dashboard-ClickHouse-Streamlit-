#  Marketplace Analytics Dashboard (ClickHouse + Streamlit)

##  Project Overview
This project is a full end-to-end **data analytics system** built to analyze digital marketplace transactions. It simulates a real-world e-commerce platform (games, software, subscriptions, and gift cards) and provides business insights using **ClickHouse, Python, and Streamlit**.

The system transforms raw transaction data into an interactive analytics dashboard for decision-making.

---

##  Business Objective
To analyze marketplace transaction data in order to:
- Understand revenue performance
- Identify top-performing products and sellers
- Evaluate category profitability
- Analyze regional sales distribution
- Support data-driven business decisions

---

## 🏗️ Tech Stack
- **Python (Pandas)** – Data processing & analysis  
- **ClickHouse Cloud** – High-performance analytical database  
- **SQL** – Data querying and aggregation  
- **Streamlit** – Interactive dashboard  
- **Plotly** – Data visualization  

---

## 📂 Dataset Overview
The dataset contains marketplace transactions with the following columns:

- transaction_id  
- user_id  
- product_id  
- seller_id  
- category  
- price  
- region  
- status  
- transaction_date  

---

## Key Business Insights

### 💰 Total Revenue
**$205,894.75**

---

### 🔥 Top Products by Revenue

| Product ID | Revenue |
|------------|---------|
| 115        | 2,333.38 |
| 96         | 2,050.00 |
| 104        | 2,041.97 |

---

### 🏪 Top Sellers

| Seller ID | Revenue |
|------------|---------|
| 10         | 5,782.14 |
| 29         | 5,555.69 |
| 48         | 5,413.17 |
| 33         | 5,322.97 |

---

### 📦 Category Performance

| Category        | Revenue |
|----------------|---------|
| Gift Card      | 53,244.07 |
| Games          | 53,035.75 |
| Software       | 50,812.33 |
| Subscription   | 48,802.64 |

---

### 🌍 Revenue by Region

| Region   | Revenue |
|----------|---------|
| Congo    | 2,284.80 |
| Korea    | 2,193.84 |
| Swailand | 1,876.27 |
| Austria  | 1,712.10 |

---

## 📈 Dashboard Features
- Interactive KPI metrics
- Top product analysis
- Seller performance tracking
- Category breakdown
- Regional revenue distribution
- Time-series revenue trends
- Dynamic filters (category, region, status)

---

## 🖥️ System Architecture
