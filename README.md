# 🛒 Amazon Sales Data Analysis 📊

This project performs an in-depth exploratory data analysis (EDA) on an Amazon Sales dataset to uncover patterns in customer purchases, product sales performance, and geographical trends. The insights derived can aid in decision-making for marketing, inventory, and logistics.

---

## 📁 Dataset Overview

The dataset contains detailed transaction records of Amazon products. Each row represents a sale and includes:

| Column Name    | Description                           |
| -------------- | ------------------------------------- |
| `order_id`     | Unique identifier for each order      |
| `product_id`   | Unique identifier for each product    |
| `product_name` | Name/title of the product             |
| `category`     | Category to which the product belongs |
| `sub_category` | Sub-category of the product           |
| `price`        | Price of the product                  |
| `quantity`     | Quantity of the product ordered       |
| `order_date`   | Date of the order                     |
| `ship_date`    | Date when the product was shipped     |
| `customer_id`  | Unique identifier for each customer   |
| `region`       | Geographic region of the customer     |
| `state`        | State where the product was ordered   |
| `profit`       | Profit made on the sale               |
| `sales`        | Total sales revenue from the order    |

---

## 🧪 Objective

* Discover high-selling products and profitable categories.
* Understand regional demand and performance.
* Track shipping delays or shipping trends.
* Identify patterns between profit, sales, and product type.

---

## 🧾 Key EDA Insights

* **Top Performing Categories:** \[e.g., Electronics and Books drive the most profit]
* **Profitability vs Sales:** \[Some products have high sales but low or negative profit]
* **Regional Analysis:** \[Southern and Western regions lead in sales volume]
* **Shipping Delays:** \[Delayed orders observed mostly in X and Y states]

*Visualizations were created using Matplotlib, Seaborn, and Plotly.*

---

## 📊 Dashboard (Power BI)

A dynamic **Power BI dashboard** was created to visualize:

* Total Sales, Profit, and Quantity metrics
* Category-wise and Sub-category trends
* Monthly and regional analysis
* Profit vs Sales scatter plots
* Filters for interactive exploration

---

## 📊 Power BI Dashboard Preview

![Dashboard](https://github.com/mSreeja12/Amazon-E-Commerce-Product-Analysis-Customer-Review-Sentiment-Analysis/blob/main/Dashboard.png?raw=true)

---

## 🛠️ Tech Stack

* **Python**: Data analysis and preprocessing
* **Libraries**: `pandas`, `matplotlib`, `seaborn`, `plotly`
* **Power BI**: Interactive dashboard
* **Jupyter Notebook**: Code execution environment

---

## 📂 Project Structure

```bash
amazon-sales-analysis/
│
├── data/
│   └── amazon_sales.csv
│
├── eda/
│   └── amazon_sales_eda.ipynb
│
├── dashboard/
│   └── amazon_sales_dashboard.pbix
│
├── images/
│   └── profit_vs_sales.png
│   └── category_sales.png
│
├── README.md
└── requirements.txt
```

---

## 📷 Sample Visualizations

<p float="left">
  <img src="images/category_sales.png" width="45%" />
  <img src="images/profit_vs_sales.png" width="45%" />
</p>

---

## 🧠 Future Scope

* Predict future sales using time series models
* Implement product recommendation engine
* Customer segmentation using clustering (e.g., K-Means)

---

## 📌 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/amazon-sales-analysis.git
   ```

2. Open the notebook:

   ```bash
   jupyter notebook eda/amazon_sales_eda.ipynb
   ```

3. Run each cell to reproduce the analysis.

4. Open the `.pbix` file using Power BI Desktop to explore the dashboard.

---

## 👤 Author

**Sreeja Mondal**
IIIT Kalyani
