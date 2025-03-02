# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on **Customer Segmentation** using **K-Means Clustering**, helping businesses target customers effectively based on their purchasing behavior.

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## 📂 Dataset Information
Dataset: `customer_data.csv`
### Columns:
- **Customer ID**: Unique identifier for each customer
- **Age**: Age of the customer
- **Annual Income**: Income in $
- **Spending Score**: Score based on spending behavior

## 🔄 Steps Performed
### 1️⃣ Data Preprocessing
- Loaded dataset and checked for missing values & duplicates
- Standardized numerical features using `StandardScaler`

### 2️⃣ Finding Optimal Clusters
- Used **Elbow Method** to determine the best `k`
- Validated results using **Silhouette Score**

### 3️⃣ Applying K-Means Clustering
- Implemented K-Means with the optimal cluster count
- Assigned cluster labels to customers

### 4️⃣ Visualization & Insights
- **2D Scatter Plot** (PCA for dimensionality reduction)
- **Pair Plot** for feature relationships
- **Centroid Visualization**

## 📊 Business Insights
📍 **High-Income, High-Spending Customers** → Premium offers & loyalty programs  
📍 **Low-Income, High-Spending Customers** → Budget-friendly deals  
📍 **Potential Buyers** → Targeted promotions  
📍 **Budget-Conscious Customers** → Discounts & affordability strategies  

## 📎 Outputs
- 📂 `customer_data_with_clusters.csv` (Dataset with Cluster Labels)
- 📈 **Elbow Method Plot**
- 🎨 **2D Scatter Plot of Clusters**
- 🖼 **Pair Plots & Centroid Visualization**


#MachineLearning #CustomerSegmentation #DataScience #KMeans #Python #GitHub
