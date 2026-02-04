# 🛍️ Customer Segmentation using Unsupervised Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-green)
![KMeans](https://img.shields.io/badge/Algorithm-KMeans-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Internship](https://img.shields.io/badge/Internship-Arch%20Technologies-purple)

---

## 📌 Project Information
- **Name:** Fozia  
- **Internship:** Arch Technologies  
- **Task:** Customer Segmentation (Task 4)  
- **Learning Type:** Unsupervised Learning  

---

## 📖 Project Overview
Customer segmentation is a key business strategy used to understand customer behavior and improve targeted marketing.

In this project, we worked with a dataset that **does not contain target labels (y)**. Therefore, **Unsupervised Learning** techniques were applied.

We used **K-Means Clustering** to segment customers based on:
- **Annual Income**
- **Spending Score**

This segmentation helps businesses:
- Identify high-value customers  
- Understand spending behavior  
- Design personalized marketing strategies  

---

## 📂 Dataset
- **Dataset Name:** Mall_Customers.csv  
- **Features Used:**
  - Age
  - Gender
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** – Data Handling  
- **Matplotlib & Seaborn** – Data Visualization  
- **Plotly Express** – Interactive Visualizations  
- **Scikit-learn** – Machine Learning (KMeans, Scaling)

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Cleaning
- Loaded dataset using Pandas  
- Checked for:
  - Missing values ❌  
  - Duplicate values ❌  

✔️ **Dataset was clean and ready for clustering**

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution of **Annual Income**
- Distribution of **Spending Score**
- Gender count analysis
- Relationship between **Income vs Spending Score**

🔍 **Insight:**  
Customers with similar income levels show **very different spending behavior**, making segmentation necessary.

---

### 3️⃣ Feature Selection
Selected key features for clustering:
- Annual Income (k$)
- Spending Score (1–100)

---

### 4️⃣ Feature Scaling
- Applied **StandardScaler**
- Ensured all features contribute equally to clustering

---

### 5️⃣ Finding Optimal Clusters (Elbow Method)
- Calculated **WCSS (Within Cluster Sum of Squares)**
- Observed elbow point at:

🎯 **Optimal K = 5**

This gives the best balance between:
- Accuracy  
- Simplicity  

---

### 6️⃣ Applying K-Means Clustering
- Applied **KMeans with 5 clusters**
- Assigned each customer to a cluster
- Visualized clusters using:
  - Scatter plots
  - Centroids

---

### 7️⃣ Cluster Analysis
Analyzed average values of:
- Annual Income
- Spending Score
- Age

---

## 📊 Cluster Insights

| Cluster | Customer Type | Description |
|--------|--------------|-------------|
| Cluster 1 | 💎 Premium Customers | High income, high spending |
| Cluster 3 | 📈 Potential Customers | High income, low spending |
| Cluster 2 | ⚡ Impulsive Buyers | Young customers, high spending |
| Cluster 0 | 👥 Regular Customers | Moderate income & spending |
| Cluster 4 | 📉 Low Engagement | Low income, low spending |

---

## 🚀 Business Impact
- Helps businesses identify **high-value customers**
- Enables **targeted marketing campaigns**
- Improves customer retention and sales strategies

---

## 📌 Conclusion
This project demonstrates how **Unsupervised Learning** can extract meaningful insights from unlabeled data.  
K-Means clustering successfully segmented customers into actionable groups that can directly support business decision-making.

---

## 📎 Author
**Fozia**  
_Data Science Intern – Arch Technologies_

---

⭐ If you like this project, don’t forget to **star the repository**!
