# 📊 Customer Segmentation & Behavioral Analysis

## 🚀 Project Overview
This project focuses on **customer segmentation and behavioral analysis** based on brand purchase data. We use **Pandas, Matplotlib, Seaborn, PCA, and K-Means Clustering** to explore customer demographics, analyze brand preferences, and segment customers into meaningful clusters. 

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/customer-segmentation.git
cd customer-segmentation
```

### 2️⃣ Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Run the Script
Ensure the dataset `ecom_cust_seg.csv` is in the `dataset` folder, then execute:
```bash
python Customer Segmentation.ipynb
```

---

## 📌 Steps to Follow

### 1️⃣ Data Preparation & Exploration 🧐
- Load the dataset and inspect the first few rows.
- Check for missing values and replace missing gender values with "Unknown."
- Plot gender distribution using **bar chart** and **pie chart** for the top 100 customers.
- Create gender-specific subsets for further analysis.

### 2️⃣ Brand Analysis 📊
- Identify brand-related columns.
- Compute total orders for each brand and visualize overall brand preferences using bar charts.
- Identify **top 10 brands** and visualize them using pie charts.
- Separate brand analysis for male and female customers with **horizontal bar charts**.

### 3️⃣ Dimensionality Reduction with PCA 🎭
- Standardize brand feature columns.
- Apply **Principal Component Analysis (PCA)** to reduce high-dimensional data into **two principal components (PCA1 & PCA2).**
- Visualize customers in PCA space using a scatter plot (colored by order volume).

### 4️⃣ Clustering Based on Brand Behavior 🤖
- Determine the optimal number of clusters using the **Elbow Method**.
- Apply **K-Means Clustering (k=4)** to group customers based on brand behavior.
- Visualize the **clusters in PCA space** with color-coded clusters and centroids.

### 5️⃣ Subclustering by Order Volume 📦
- Define order bins (0-4, 5-8, 9-12) to segment customers further.
- Combine the **cluster label** and **order bin** to form a new subcluster label.
- Visualize **subclusters in PCA space** using distinct colors.
- Compute **summary statistics** (min, max, mean, count of orders) for each subcluster.

---

## 🎯 Key Learnings
✅ Understanding customer segmentation using **purchase data** 📦
✅ Applying **PCA** for dimensionality reduction 🎭
✅ Implementing **K-Means clustering** for behavioral grouping 🤖
✅ Creating **insightful visualizations** to understand consumer patterns 📊

---

## 📌 Output
📸 **Gender Distribution**

📉 **Brand Orders Visualization**

🎭 **PCA Scatter Plot**

🎯 **Customer Clustering in PCA Space**

📦 **Subclustering by Order Volume**

---
