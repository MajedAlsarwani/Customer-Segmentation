# **Customer Segmentation using K-Means Clustering**  

## **Project Overview**  
This project analyzes customer behavior using clustering techniques. The goal is to segment customers based on their **annual income** and **spending habits** to provide valuable insights for targeted marketing strategies.  

## **Dataset**  
The dataset used is the **Mall Customer Segmentation Dataset**, which contains:  
- **Customer ID**  
- **Age**  
- **Gender**  
- **Annual Income (k$)**  
- **Spending Score (1-100)**  

## **Steps Performed**  

### **1️⃣ Data Preprocessing & Exploration**  
- Checked for **missing values** and **duplicates**.  
- Analyzed the **distribution** of variables.  
- Explored the **gender distribution**, showing a higher number of female customers.  

### **2️⃣ Finding Optimal Clusters**  
- Used the **Elbow Method** to determine the optimal number of clusters for **K-Means Clustering**.  
- Chose **K=4** as the best number of clusters.  

### **3️⃣ Applying K-Means Clustering**  
- Segmented customers into **4 groups** based on their **Income & Spending Score**:  
  - **Cluster 0**: Low Income, Low Spending  
  - **Cluster 1**: High Income, High Spending  
  - **Cluster 2**: Low Income, High Spending  
  - **Cluster 3**: High Income, Low Spending 

### **4️⃣ Cluster Insights**  
- **Age Analysis**: Cluster 2 (high spenders, low income) had the youngest average age (24.8 years), while Cluster 0 had the highest (44.9 years).  
- **Gender Analysis**: More females were found in lower spending clusters, suggesting a tendency for conservative spending.  
- **Spending vs. Income**: High-income customers either spend a lot (Cluster 1) or save more (Cluster 3).  
 
