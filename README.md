# 🛍️ Customer Segmentation Using RFM and KMeans Clustering

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering on real-world e-commerce transaction data.

---

## 🎯 Project Objective
To identify meaningful customer segments based on purchasing behavior and provide business-driven recommendations that improve marketing efficiency and customer retention.

---

## 📁 Project Structure

- **Data Overview**: Load and preview raw data
- **Data Cleaning**: Filter invalid transactions and prepare clean data
- **Feature Engineering**: Generate RFM metrics per customer
- **EDA**: Explore and visualize distributions and outliers
- **Preprocessing**: Apply log transformation and scaling
- **Clustering**: Use Elbow method and KMeans
- **Cluster Visualization**: Heatmaps and scatter plots
- **Business Insights**: Detailed cluster interpretation
- **PCA Visualization**: 2D representation of clusters

---

## 📊 Techniques Used

- Pandas, NumPy
- Seaborn, Matplotlib
- Sklearn: StandardScaler, KMeans, PCA

---

## 💡 Business Insights Summary

### 🔵 Cluster 1 – VIP Loyal Customers
- **Behavior**: High frequency & spending, very recent activity
- **Action**: Reward loyalty, personalized campaigns
- **Value**: Boosts CLV and reduces churn

### 🟢 Cluster 2 – Previously Loyal, Now Inactive
- **Behavior**: Moderate frequency, older recency
- **Action**: Win-back offers, reactivation campaigns
- **Value**: Reactivating old customers is cost-effective

### 🔴 Cluster 0 – New but Low-Value Customers
- **Behavior**: Recent but low frequency and spend
- **Action**: Nurture with onboarding and product suggestions
- **Value**: Early-stage growth opportunity

### 🟣 Cluster 3 – Dormant or Churned
- **Behavior**: High recency, very low frequency and spend
- **Action**: Try final win-back or remove from campaigns
- **Value**: Reduces marketing waste

---

## 📉 PCA Visualization

PCA was used to reduce the RFM dimensions to 2D. This allows a visual overview of how distinct the clusters are and validates the effectiveness of our segmentation.

![PCA Scatter Plot](images/pca_plot.png)

---

## 📌 Dataset

This project used the [Online Retail Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data) from Kaggle.

---

## 🧠 Author

**Zeyad Elsokary**  
LinkedIn: linkedin.com/in/zeyad-elsokary

---