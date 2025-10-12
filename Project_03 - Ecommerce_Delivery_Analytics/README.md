# 🚚 E-commerce Delivery Analytics

This project performs **Exploratory Data Analysis (EDA)** on a E-commerce delivery dataset focused on the performance of e-commerce grocery delivery services such as Blinkit, Swiggy Instamart, and JioMart.
It captures crucial details related to delivery times, customer feedback, service ratings, order values, and payment methods, providing valuable insights into customer satisfaction and platform efficiency.

---

## 📌 Objective

- Perform **data cleaning** and **preprocessing**.
- Create **visualizations** to understand trends and patterns.

---

## 📂 Dataset Source

- **Name**: `Ecommerce_Delivery_Analytics_New.csv` Ecommerce Delivery Analytics
- **Source**: Publicly available dataset from Kaggle.
- **Rows**: More than 100,000 rows of real-world-inspired data
- **Columns**: 11

**Features**:
- `Order ID
- `Customer ID
- `Platform
- `Order Date & Time
- `Delivery Time (Minutes)
- `Product Category
- `Order Value (INR)
- `Customer Feedback
- `Service Rating
- `Delivery Delay
- `Refund Requested   

---

## 📁 Folder Structure

```text
Project_03 - Ecommerce_Delivery_Analytics/
│
├── Ecommerce_Delivery_Analytics/
│   ├── data/
│   │   ├── raw/            # Original dataset
│   │   ├── processed/      # Cleaned dataset
│   │
│   ├── notebooks/
│   │   ├── Ecommerce_Delivery_Analytics.ipynb
│   │
│   ├── README.md           # Project documentation
│
└── requirements.txt
```

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📈 Key Visualizations

- **Histogram (with Kernel Density Estimate)** – Distribution of Delivery Time (Minutes) (o observe the overall distribution and variation in delivery times).
- **Box Plot** – Box Plot of Order Value (INR) (To analyze the spread and skewness of order values).
- **Count Plot (Categorical Distribution)** – Count of Orders by Platform (To visualize the frequency of orders across different delivery platforms (e.g., Blinkit, Swiggy Instamart, JioMart)).
- **Heatmap** – Correlation Heatmap of Numeric Features (To show correlations between quantitative variables such as Delivery Time, Order Value, and Service Rating).
- **Pair Plot (Multivariate Visualization)** – Pair Plot of Selected Features (To explore relationships and distribution patterns across multiple numerical variables such as Delivery Time (Minutes), Order Value (INR), and Service Rating).

---

## 🔍 Key Insights

- Delivery times cluster around a certain mean but show a long tail due to delayed orders.
- Order value distribution indicates the presence of high-value outliers.
- Platform-wise analysis suggests uneven order distribution across e-commerce services.
- Strong correlations exist between Service Rating and Delivery Time (Minutes), highlighting delivery efficiency as a key satisfaction driver.

---
