# Customer Segmentation Using Machine Learning

A BTech Computer Science & Engineering internship project that segments customers based on purchasing behavior and demographic information using Python and K-Means clustering.

## 📌 Project Overview

Customer segmentation is the process of dividing customers into groups based on similarities in their behavior and characteristics.

In this project, customer data is analyzed using **Python and Machine Learning** to identify meaningful customer segments based on:

* Customer recency
* Number of orders
* Total spending
* Average order value
* Annual income
* Customer satisfaction

The project uses **K-Means Clustering** to identify different groups of customers and provides business recommendations for targeted marketing.

## 🎯 Objectives

* Analyze customer purchasing behavior
* Perform data preprocessing and exploratory analysis
* Identify meaningful customer groups
* Apply K-Means clustering
* Evaluate clustering using Silhouette Score
* Visualize customer segments
* Provide targeted marketing recommendations

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **CSV Dataset**

## 📊 Dataset

The project contains **300 synthetic/demo customer records**.

The dataset includes:

| Feature                 | Description                    |
| ----------------------- | ------------------------------ |
| Customer_ID             | Unique customer identifier     |
| Age                     | Customer age                   |
| Gender                  | Customer gender                |
| Annual_Income_INR       | Annual income                  |
| City                    | Customer city                  |
| Tenure_Months           | Customer relationship duration |
| Recency_Days            | Days since last purchase       |
| Total_Orders            | Number of orders               |
| Total_Spend_INR         | Total amount spent             |
| Average_Order_Value_INR | Average spending per order     |
| Online_Orders           | Number of online orders        |
| Discount_Usage_Pct      | Discount usage percentage      |
| Satisfaction_Score      | Customer satisfaction score    |
| Preferred_Category      | Preferred product category     |

> **Note:** The dataset is synthetic/demo data created for academic and internship demonstration purposes. It does not contain real customer or confidential company information.

## 🔬 Methodology

The project follows these steps:

1. Data collection and preparation
2. Data cleaning and inspection
3. Exploratory Data Analysis
4. Feature selection
5. Feature standardization
6. K-Means clustering
7. Silhouette Score evaluation
8. Customer segment profiling
9. Data visualization
10. Business recommendations

## 🤖 Machine Learning Model

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to divide data into groups based on similarity.

The main behavioral features used for clustering are:

* `Recency_Days`
* `Total_Orders`
* `Total_Spend_INR`

Different values of K were evaluated using the **Silhouette Score**.

The final project uses **4 customer segments** for business interpretation.

## 👥 Customer Segments

The analysis identifies four business-oriented customer groups:

### 1. High-Value Customers

Customers with high spending and frequent purchases.

**Recommended strategy:**

* VIP rewards
* Premium offers
* Early access to prod
