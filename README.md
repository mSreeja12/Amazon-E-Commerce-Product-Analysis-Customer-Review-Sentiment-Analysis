# 📊 Amazon E-Commerce Product Analysis & Customer Review Sentiment Analysis

This project is an end-to-end exploratory data analysis (EDA) of Amazon product listings and customer reviews. It includes data cleaning, insightful visualizations, and sentiment analysis using NLP to uncover key insights for business decisions.

---

## 🧠 Problem Statement

With the increasing volume of e-commerce data, understanding product trends, pricing strategies, and customer sentiment is crucial for sellers to optimize listings and increase sales. This project explores these aspects through real Amazon product and review data.

---

## 📁 Dataset Overview

The dataset contains:

- Product information like ID, category, pricing, ratings
- Customer reviews including titles and content
- Product metadata like image and product links

🧾 **Key Columns:**
- `product_name`, `category`, `discounted_price`, `actual_price`, `rating`, `review_content`, `user_name`
- Engineered columns: `sentiment`, `price_diff`, `review_length`, `word_count`

---

## 🧼 Data Cleaning

- Removed null and duplicate values
- Handled inconsistent price and rating formats
- Filtered unnecessary columns for clarity

---

## 📊 Exploratory Data Analysis

- 📌 **Top Categories** and **Most Reviewed Products**
- 📈 Price Distribution, Rating Trends
- 🔄 Discount % and its relation with Ratings
- 📉 Sentiment distribution by product category
- 📝 Review length vs rating correlation

---

## 💬 Sentiment Analysis (TextBlob)

- Polarity and Subjectivity scores extracted
- Reviews labeled as `Positive`, `Negative`, or `Neutral`
- Built sentiment categories using thresholds

---

## 📐 Feature Engineering

- `price_diff`: actual - discounted price
- `review_length`: character count of review
- `word_count`: number of words in review

---

## 📊 Visualizations

- Heatmaps of correlations
- Boxplots of ratings by category
- Distribution plots for price, ratings, sentiments
- Word clouds for positive and negative reviews (optional future addition)

---

## 📈 Business Insights

- High-discount products don't always yield better ratings
- Longer reviews often reflect stronger sentiments
- Certain categories consistently receive higher sentiments

---

## 🚀 Future Work

- 📌 Build a **Power BI dashboard** for:
  - Category-wise rating and price comparison
  - Real-time review sentiment monitoring
  - Discount vs Rating impact
- 🧠 Use advanced NLP (like VADER or BERT) for improved sentiment accuracy
- 📦 Recommendation system using collaborative filtering

---

## 🛠️ Tech Stack

- Python (Pandas, Seaborn, Matplotlib, TextBlob)
- Jupyter Notebook
- Power BI (dashboard coming soon!)

---

## 🏁 Outcomes

- Improved understanding of product performance and customer feedback
- Actionable insights for pricing, promotion, and category focus
- A strong addition to data analytics portfolio

---

## 🙋 Author

**Sreeja Mondal**  
Data Analyst | AI and ML Enthusiast | IIIT Kalyani  

