# Data Analytics & Machine Learning Portfolio 🚀

Welcome to the data analytics and machine learning portfolio repository for **Team 4** (Infotact Solutions). This repository contains two distinct projects focusing on data visualization and unsupervised machine learning.

**Team Members:**
* Priyanka Kamble
* Aditya Kumar
* Sankalp Gupta

---

## 📊 Project 1: Sales Data Analysis & Dashboard Using Power BI

### 🎯 Objective
To analyze Super Store's historical sales data to understand patterns, identify profitable segments, and optimize operations. The project culminates in an interactive Power BI dashboard visualizing key business metrics.

### 🛠️ Tools & Technologies
* **Microsoft Excel:** Initial data analysis (PivotTables, Slicers).
* **Power BI:** Advanced visualizations and dashboard development.
* **Power Query Editor:** Data transformation and cleaning.

### 📁 Dataset
* **Source:** SuperStore Sales Dataset
* **Details:** 1000+ records across 23 fields including temporal, geographic, customer, product, and financial metrics.

### 📈 Key Performance Indicators (KPIs) & Findings
* **Total Sales:** $1.57 Million | **Total Orders:** 22,000 | **Total Profit:** $175,000
* **Regional Leader:** West region accounts for 33% of total sales.
* **Top Segment:** Consumer segment accounts for 48% of sales.
* **Category Insights:** Office Supplies is the top-performing category ($0.64M).
* **Time Trends:** 2020 outperformed 2019, with significant seasonal spikes in Q4 (Nov-Dec).

### 💡 Recommendations
1. Boost promotions in Q4 to capitalize on seasonal demand.
2. Target the South Region for growth through regional discounts.
3. Promote digital payments with cashback/incentives.
4. Invest in high-demand products like Phones, Chairs, and Office Supplies.

### 🖼️ Dashboard Preview / Link
**Live Dashboard Link:** [Click here to view the Super Store Sales Dashboard](https://app.powerbi.com/groups/me/reports/d664391c-5b92-4949-a198-87f1ac528cee/8e0f819884cea28a1690?experience=power-bi)

**Dashboard Preview:**
<br>
<img width="1095" height="621" alt="Super Store Sales Dashboard Preview" src="https://github.com/user-attachments/assets/bcf24f39-1a92-4880-b6f1-94e9b7be91e0" />


---

## 🤖 Project 2: Customer Segmentation Using Clustering

### 🎯 Objective
To perform customer segmentation using unsupervised machine learning (K-Means Clustering) to help businesses identify valuable customer groups, tailor marketing efforts, and optimize resource allocation.

### 🛠️ Tools & Technologies
* **Python** 
* **Libraries:** Scikit-Learn (Machine Learning), Pandas (Data Manipulation), Seaborn & Matplotlib (Data Visualization).

### 📁 Dataset
* **Source:** Mall Customer Segmentation Dataset (Kaggle).
* **Features:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100).

### ⚙️ Methodology
1. **Data Preprocessing:** Checked for missing values, applied Label Encoding for categorical data (Gender), and scaled numerical features using `StandardScaler`.
2. **Exploratory Data Analysis (EDA):** Analyzed feature distributions and correlation matrices.
3. **Optimal Clusters:** Utilized the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters ($K=5$).
4. **Modeling & Visualization:** Applied K-Means clustering and visualized the segments using 2D scatter plots and Principal Component Analysis (PCA).

### 🧩 Customer Segments (Clusters)
* **Cluster 0 (High Income, High Spending):** Ideal targets for premium/luxury products and exclusive memberships.
* **Cluster 1 (Low Income, High Spending):** Highly active shoppers; best engaged with loyalty programs and discounts.
* **Cluster 2 (High Income, Low Spending):** Cautious shoppers; require trust-building and personalized campaigns.
* **Cluster 3 (Low Income, Low Spending):** Budget-conscious; best targeted with essentials and bulk deals.
* **Cluster 4 (Young, Average Income/Spending):** Trend-driven; excellent for mobile-first campaigns and influencer marketing.

---

### 🚀 How to Run Locally
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. **For Power BI:** Open the `.pbix` file using Microsoft Power BI Desktop.
3. **For Python Clustering:** Ensure you have Python installed along with the required libraries (`pip install pandas scikit-learn matplotlib seaborn`). Run the Jupyter Notebook or Python script provided in the repository.
