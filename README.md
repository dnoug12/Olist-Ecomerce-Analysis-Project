# 📊 Brazil E-Commerce Data Analysis (Olist)

## 🔍 Introduction
This project analyzes data from the **Olist** e-commerce platform to uncover revenue trends, customer behavior, delivery performance, and to recommend strategies for improving business operations.

📌 **Main Objectives**:
- Analyze revenue and order volume over time.
- Explore shopping behavior by hour/day.
- Evaluate delivery performance and optimize logistics.
- Segment customers by shopping characteristics.
- Propose strategies to improve business outcomes.

---

> Please refer to **Report.pdf** for a comprehensive overview of the analysis.

## 📂 Data Sources
The dataset is the **Olist Brazilian E-Commerce Dataset** from Kaggle, consisting of the following tables:

| 📁 **Filename**                                  | 📄 **Description**                                                |
|--------------------------------------------------|------------------------------------------------------------------|
| 🛍 `olist_customers_dataset.csv`                 | Customer information (customer ID, address, zip code).           |
| 🌍 `olist_geolocation_dataset.csv`               | Geolocation data (longitude, latitude, postal code).             |
| 📦 `olist_orders_dataset.csv`                    | Order information (order ID, order date, order status).          |
| 📊 `olist_order_items_dataset.csv`               | Order item details (price, shipping fee, quantity).              |
| 💳 `olist_order_payments_dataset.csv`            | Payment information (payment method, payment installments).      |
| ⭐ `olist_order_reviews_dataset.csv`             | Customer reviews for each order.                                 |
| 🎁 `olist_products_dataset.csv`                  | Product information (product ID, category, weight, dimensions).  |
| 🏪 `olist_sellers_dataset.csv`                   | Seller information (seller ID, store location).                  |
| 🔄 `product_category_name_translation.csv`       | Translation of product categories from Portuguese to English.     |

**🔗 Data Link:** [Kaggle - Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📊 Key Analyses

### 📈 1. Revenue & Order Trends
- Revenue spikes during peak months.
- Highest order volume in the **evening (6 PM - 10 PM)**.

### 🚚 2. Delivery Performance
- Delivery times vary significantly between months.
- Some regions experience **excessive delivery delays**, indicating a need to optimize logistics.

### 👥 3. Customer Segmentation
- Distinct customer groups based on shopping behavior.
- **Credit Card** payments correspond to the highest average order value.

---

## 🛠️ Setup & Running the Project

### 1️⃣ Install Required Libraries
```bash
pip install pandas numpy seaborn matplotlib scikit-learn streamlit
```

### 2️⃣ Run the Analysis Notebook
```bash
jupyter notebook analysis.ipynb
```

### 📌 Future Directions
- ✅ Sales forecasting using Machine Learning.
- ✅ Optimize delivery time based on historical data.
- ✅ Build a personalized product recommendation system.

📩 **Contact & Contributions:** Feel free to open a Pull Request if you’d like to contribute!

🔗 GitHub: https://github.com/dnoug12

