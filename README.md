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

## 🖼️ Visualizations

### 📸 Gender Distribution
![Gender Distribution](https://media-hosting.imagekit.io//06bdab5e8faf4090/1.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=fK-itm8ZaLtAxncF9giY-g7NUQ6Homp0WMh95VYEARcyy3kdtHpAkdYP5xfxH6BLlO8nGXA-tED-CNg2KlHelQ-JBMceIitCtRJ2~aCla29MR51rDBkjQJUqDfa7eNi~ewCKWgl9HQinSBHbsoxW~~sfpz5HZdAEWLtAb3R41nGGY4jzpoNFRZtoxAqdy8x9ETb9yLpQelQtrJ98C83CjxjsiiiCESq~Hmm4uwMFO6Eth2fX247PoH84GNToDxyAvB7RsLW9l8Aepfh2~5~2talHp37LPED7TYScLUyelWU-zrUME6bzPNMw9QpAqIo-YBzeSgtTFwrDO18W4uEXDg__)

### 📉 Top 100 Customers distribution by Orders
![Top 100 Customers distribution by Orders](https://media-hosting.imagekit.io//c92fd968e21a48f1/2.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=g6xN4RR8p7Dp5TWxr0MFUivvNpc3BVZhZ7yS4ZGD42mcEkTmpAfB8uHySC60puwEvHE92GxTusfEJFFmnKgrGRz-OtWrt18JivIqVqfAAVEh5u~vQSJFzR~ReCgKFni4Gv7V80Jh9fFAMC-lKGNl-ikZ6W4~gjVEmHGGHz8AxrAflo4OsxuOt5rrQFD---HbDbuR5743qM-wDDhSpF2Gma1RYyqh5ruDR13CLV7-7YdK7~obD02YpLl41Z~9c0pWZa7qJSl1FdnZ0-ohxdBMohZy5WW~iaADY0ESCGEdkiUw~zOVpdrAInRcwsJi2OkvVryB-FO5IDJnB78qyerCfw__)

### 🎭 Total Orders by each Brand
![Total Orders by each Brand](https://media-hosting.imagekit.io//eec8f4b64f5d4861/3.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=UzxUCIiuDo3~I82bqidK4XSrl51iBMw7cxteRaFNE7vFh5QwAD8XrHHj1jLEujb8AMlN1Eoh-zVUC5FfOYwpt9tn~lHcoH08XecrIWaeJ9TGWMe97~0y3749uAXfF~0-oetTYCz1RB6A6z3Y0b1mSkp5o3Vp7CSyvwggVM8gSDGq~DW--s27vPs3ddlrKCpOnCbZpQ2a3XTn6jplKhJFxoP4A9~DRibBDGUS4BZxsXj8jwVC-F9X3fvJWuEqzvkYXzagNh-UL6DV-akqOeImwRQCI2d~zinlWTlcWwSudfzHDaPdsEh1NDVJjZ~M8zDPdUFpQgU1les52Spd0KXESA__)

### 🎯 Top 10 brands contribution to Total Orders
![Top 10 brands contribution to Total Orders](https://media-hosting.imagekit.io//670a9e65dd83460c/4.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=REWppcq7i2sNLJ0MKrQcemHn0nVkz~r9buSdpBj~KSsykpsziY7TYCnmU5qLuz3eFZqzKYud6Mhu8eEeeSInoxcu0q0mrvKOD865Y37jFcJsqY3EozFWjX5sKOr6nz2yRNJVZKgTTb8br-wkNL8CKEKNfwMlWzJrzwoy~kW4WpTk1y-lJ2SrC9PkGQCdD1XIcBtJ2itklQuoAEahIFjkptKR867otnaB5Uyj4JYpVdBHUMRB3pP5lBMAYHHz8ls528kW02nl7Sov3hoLwW3eH1I4peM4LWiNy~4gecHBhZXv0-ytMkM07-O-f-1Aza1Z0WlbY24bMwyRqkjjgHt-AA__)

### 📦 Top 10 brands for Male Customers
![Top 10 brands for Male Customers](https://media-hosting.imagekit.io//a0829bf9014d423d/5.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=qR4nz6eRZWbOEFrFhqY-gutFgicATPragbwgYLwL8HqWH~NcrIxwrjEZ8aC6vzA2wK4zOJBagDxVdeRUcYk8IyUah~tKs2FlXxhaR2tQgWiAfbPEJrZm8YQQhYSOBfHCrJWLDEe9F8whEs6bo4770mNXYs6ym7iatVb9S-knaSUqylWoQiAKOrp~VpaQultmYVdFeJuSN6oiOsMWVbEQKGygshyp1ghgHEQoep39C5Sm3bayyWaFK-mQd35AbqQ7hgKR4-~XdXFsUfFfk0MFHb-OEEDsh-PNeysOZYT0WrvzBTMkSf12RisEjpPZeYwX23x-LxxkJq4AIwtv-gSOag__)

### 📊 Top 10 brands for Feale Customers
![Top 10 brands for Female Customers]([Images/6.png](https://media-hosting.imagekit.io//623f256bdf0642b1/6.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=TYmzVLRNfyyskesc82HJ0zRf2m-Fzpsfpq7Pob0-elDa3fHxS504KLKtoFiiXjKL4d0aXGoKKi3xyRhEflq0d9P080rKnBF4R5hg3xjsyaSrrFp9xKJ-4K00hWpC3goukeOJiLRmkqEbeUC~FUBaClE7sEBjUcFv9OcsAs81uPwfYleh9NC6MmJTIUpzHH9u3~~6qPLEwUJfWXQydA5Bd84J4ICzVuaugM6JtORGZrEgpn6iOsXnqWgP-TnWbQ6UjrR0pIO314qQMByiVZIel2FLROCJFdMQbDh1CaDvoyr8R4bCHCNrmqGi0~U2t1oI4RAHmqrkdYYAdWGVYMu0gQ__)) 

### 📊 PCA Projection of Brand Orders
![PCA Projection of Brand Orders](https://media-hosting.imagekit.io//4c13035296bf465b/7.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=NVWlUnrs9BeozyetARq1xgUjx~rn8aMUZkauOhrPPjQBu4iZo9T1PVAPp1cbmBmn5vJXEW2oyeJwWw0AUzEmsPX3G8Iw~R3OCwywYVBIhhNlqq2EvSWVMzGZ3hLaqKa-TQnsQDJhl3ShuzLOTRUN4kuVYhJSKNpDbR9y3PY5f8n1llEx5aZs77YTPwJ5o9EwdVHGtW7DiljEYXtKvrYsuOLUMpbGEpyCr3vKFL4KweoxgqEgsqOplysWZHOZFTsPi9wiGbtlBH2rtQ7GQ1ArGECdEW1guBg4RKQERv3sdB5cRSSd7Cki5DDWb1yFuFjhyUGCH7zAEzMf72lNKKinXg__) 

### 📊 Elbow Method for Optimal K
![Elbow Method for Optimal K](https://media-hosting.imagekit.io//881148f00b6d490c/8.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=r-5cJhRahsu2xTpPLZHmzyJHNUSXes1P-5wrQkANFAMdBXSDli6pGR6hmNpkIWi5922j-ieCtcCv8wG5A13vRRkpffq8zRWdjHUSLjAU6kQemRqbXUaQx~yWK~nS~UIaTXD5U7pw4GhGEBtqGH1W7CFpGepz1-GJ2dQhej8fE1SAGaOfxTG1jO1P6n3NuztX24~d-o6ZrtrCM~jFmLunW1HKIvufoA-xtG5JJEcjbEof-ygl3hcvOqewlheh6fvivnzkQBzOD5zLeNdKtVQJcwZGE7tqxwh1iwAr0O3MyVh4ZudGIfPlfqN7z8rYczikZlxvDQ3Kt302KQeupIAbvQ__) 

### 📊 Customer clusters based on Brand Preferences
![Customer clusters based on Brand Preferences](https://media-hosting.imagekit.io//6774fcd2a8ce4ea1/9.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=SRXwkA9LJRxXc~Wu~kv9GjTL7EaUJoGDaLfJ4jz3wTVgD~LXgNi5vYPei2rHJFCf0emZFliF6XRVNe0JvVnLtfKCK7N-Ey3xPIHGvpuLWkkxdgf8RTHIm~tm78TpXWrErd5~Wk~i65Od~16JIroLLEXXttCi52mCz0FSo~jp-UYvT0--JGsV3qaP7o6KYk6jGKpKyDGpjMJtrtSTW0SMKXcH8oXVpN3ZAzwW8lTBoNrp8XG735MIdHIuMz~kCIMcngVnC0h6m6CabsZ2bUNivcHmbyQAcyugQv3q5bQhVE02tqENlNTVP15sbqENWAH1wppgGFDkoKg3dX1~PsKaJg__)

### 📊 Customer sub-clusters (Segmentation by order within Brand Preferences)
![Customer sub-clusters (Segmentation by order within Brand Preferences)](https://media-hosting.imagekit.io//005160aa2c354d7c/10.png?Expires=1835269668&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=JQlZT-O7dCyDqCool1X3tnreMsmAxwMlpdHogKgNslm73OJMtxND0MPGXBgNRg7224Ixju75qeivZQQjyIWl~H55Yk6N~DwDr1~AET0X47YpxqZgAJKBZp58tSfN4cl51oEX6Qh9Z3VXY1EIhT4a9Gn8l~sJ70tzHDXYkdsZlknOtnNcSF64oNZ4MwVdgXhuh4txrDNkAMl96RBtUZF~tm~Jbl84Ev5sJBpo0LG4aPMf93hi14RjHS4-M5DSS8akemgh~IFVosfu5SA96vLFmFtLwfhiq6FLhUTLUhRGsPabfKsjDFmzpqKaSg5Cob-21VhXzlaRJTnEdyaQZA~kVg__) 

---

## 📌 Output
📸 **Gender Distribution**

📉 **Brand Orders Visualization**

🎭 **PCA Scatter Plot**

🎯 **Customer Clustering in PCA Space**

📦 **Subclustering by Order Volume**

---
