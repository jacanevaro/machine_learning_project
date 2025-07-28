# 🍇Clustering Customers by Demographics Using K-Means

## This was an unsupervised learning project for MDS-640 Machine Learning during the Spring of 2025. 
---

## 🔭Project Summary

Mall customer data is separated into clusters for more granular advertising and service
- Data Visualization
- Data Preprocessing
- Data Transformation
- Finding Optimal K Using the Elbow and Silhouette Methods
- K-Means Clustering

---

## ⚙️Tools
- 🐼 **Pandas**
- #️⃣ **Numpy**
- 📊 **Matplotlib**
- 🤖 **Sklearn**
- 🌊 **Seaborn**

---

## 📂Dataset 

The dataset is called `mallcustomers.csv` and includes data for 200 mall customers.

💾 [Download the Dataset](mallcustomers.csv)

### Features
- 🚻 **Gender**
- 🌱 **Age**
- 💰 **Income**
- 💯 **SpendingScore**

---

## 💡Key Insights
- Based on the inertia scores, I determined that `k=5` is optimal.
- Cluster 0 had the most people overall.
- All clusters had more women than men, except for cluster 3. The advertising directed at that cluster should be geared toward men.
- Clusters 1 and 2 had median ages of 32 and 23.5 respectively, which is significantly younger than the other three. Special care should be taken to tailor the advertising to these younger generations. 

--- 

## 🏃Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/jacanevaro/machine_learning_project.git
   cd machine_learning_project

