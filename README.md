# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means clustering** to segment customers based on their purchasing behavior. Using **Principal Component Analysis (PCA)** for dimensionality reduction and data preprocessing techniques, I derived meaningful customer insights to aid business decision-making.

## 📊 Key Features
- **Data Preprocessing**: Handling missing values, feature engineering, and normalization.
- **PCA for Dimensionality Reduction**: Reducing complexity while preserving variance.
- **Optimal K Selection**: Using the **Elbow Method** and **Silhouette Score**.
- **K-Means Clustering**: Grouping customers based on key purchasing behaviors.
- **Visualizations**: PCA plots, cluster characteristics, and metric comparisons.
- **Business Insights**: Recommendations for targeted marketing strategies.

## 📂 Dataset


The dataset initially contained customer transaction details with the following features:
- **Invoice**: Sum of all purchases per customer.
- **StockCode**: Number of unique invoices per customer.
- **Description**: Sum of all items purchased.
- **Quantity**: Number of unique products bought.
- **InvoiceDate**: Days since the last purchase.
- **CustomerID**: Spending per order.
- **Country**: Items per transaction.
- 
After feature engineering, he dataset contains customer transaction details with the following key features:
- **Total Spending**: Sum of all purchases per customer.
- **Total Orders**: Number of unique invoices per customer.
- **Total Quantity**: Sum of all items purchased.
- **Distinct Items**: Number of unique products bought.
- **Recency**: Days since the last purchase.
- **Average Order Value**: Spending per order.
- **Average Items Per Order**: Items per transaction.
- **Country**: Items per transaction.

## 🚀 Installation & Usage
### 1️⃣ Clone Repository
```sh
 git clone[[https://github.com/UncleTeslim/retail_data_clustering]]
 cd retail_data_clustering
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run Clustering Analysis
```sh
python clustering.py
```

## 📈 Visualizations
- **PCA Scatter Plot**: Displays customer clusters.
- **Elbow Method**: Determines the optimal number of clusters.
- **Cluster Comparison**: Shows differences in key metrics.

## 📢 Business Insights
- **Cluster 1 (High-Value Customers)**: Frequent shoppers with higher spending. Target them with personalized offers and loyalty programs.
- **Cluster 0 (Low-Engagement Customers)**: Less frequent purchases. Use email marketing and incentives to re-engage them.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.


