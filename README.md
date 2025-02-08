# Customer Segmentation Using K-Means Clustering

## Overview
This project focuses on **customer segmentation** using **K-Means clustering**. The goal is to group customers based on their purchasing behavior and provide insights for business strategies such as targeted marketing and customer retention.

## Dataset
The dataset consists of transaction data with key attributes such as:
- **Total Spending**: Total amount spent by each customer.
- **Total Orders**: Number of transactions per customer.
- **Total Quantity**: Total items purchased.
- **Average Order Value**: Spending per order.
- **Average Items Per Order**: Items purchased per transaction.
- **Distinct Items**: Unique products purchased.
- **Recency**: How recently a customer made a purchase.

## Clustering Approach
- **Principal Component Analysis (PCA)** was applied to reduce dimensionality and visualize the clusters.
- **K-Means clustering** was used to group customers into **six distinct segments** based on their purchasing behavior.

## Key Findings
1. **Cluster 0 (High-Value Frequent Buyers)**
   - High total spending and frequent orders.
   - Large variety of items purchased.
   - Recent purchases indicate engagement.
   
2. **Cluster 1 (Low-Value Infrequent Buyers)**
   - Lowest spending and order count.
   - Fewer distinct items purchased.
   - Longer recency suggests inactivity.

3. **Cluster 2 (Moderate Spenders with Mid-Level Frequency)**
   - Mid-range spending and orders.
   - Decent variety in purchases.
   - Moderate recency.

4. **Cluster 3 (Frequent Shoppers with Moderate Spending)**
   - High purchase frequency but moderate spending per order.
   - Good variety in purchases.
   - Engagement is relatively high.

5. **Cluster 4 (Low-Engagement Customers)**
   - Lowest spending and unique items purchased.
   - Few transactions and long recency.

6. **Cluster 5 (High-Spending Engaged Customers)**
   - High spending and large order volumes.
   - High recency, showing active engagement.

## Visualizations
- **PCA-based Cluster Visualization:** Displays customer segmentation in reduced dimensions.
- **Customer Distribution by Country:** Shows that most customers belong to the UK, with smaller segments in other countries.

## Repository Structure
- `retail_data.ipynb` - Jupyter Notebook containing data preprocessing, clustering, and analysis.

## Requirements
To run this project, you need:
- **Jupyter Notebook (or JupyterLab)**
- **Anaconda (Recommended)** or a Python environment with the required libraries.

## Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/UncleTeslim/retail_data_clustering]
   cd retail_data_clustering
   ```
2. Install dependencies:
   ```bash
   conda create --name retail_data_clustering python=3.8
   conda activate retail_data_clustering
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run `retail_data_clustering.ipynb` to see the results.

## Future Work
- Experiment with **alternative clustering methods** (e.g., DBSCAN, Hierarchical Clustering).
- Improve **feature engineering** to enhance clustering quality.
- Deploy as a dashboard for **interactive customer segmentation insights**.

## Contributors
- **Teslim Kazeem** - Data Scientist

## License
This project is licensed under the MIT License.

