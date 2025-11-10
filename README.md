# 🎓 University Clustering with K-Means

This project demonstrates how to apply **K-Means Clustering**, an **unsupervised machine learning algorithm**, to group universities based on their characteristics.  
The dataset includes information such as **tuition**, **graduation rate**, and **student enrollment**.  
By the end, we explore how well the algorithm can identify patterns — such as grouping **private** and **public** universities — without using labels during training.

---

## 📘 Project Overview

In this project, we:
- Load and explore a university dataset containing academic and financial metrics  
- Perform **data cleaning and preprocessing**  
- Apply **K-Means clustering** to partition universities into groups  
- Visualize the clusters using **Seaborn** and **Matplotlib**  
- Evaluate clustering performance using known labels (for learning purposes only)

---

## 🧠 Key Concepts

- **Unsupervised Learning** — Learning from unlabeled data  
- **K-Means Algorithm** — Partitioning data into *k* groups based on feature similarity  
- **Feature Scaling** — Ensuring balanced feature influence  
- **Cluster Evaluation** — Comparing clusters with known labels (optional)

---

## 🧩 Technologies Used

- **Python 3.10+**  
- **scikit-learn**  
- **pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook**  

---

## 🚀 Project Workflow

1. **Data Exploration**  
   - Inspect dataset statistics and visualize distributions  
   - Identify outliers and missing values  

2. **Preprocessing**  
   - Scale features using `StandardScaler`  
   - Select relevant numerical columns for clustering  

3. **Modeling with K-Means**  
   - Initialize and fit the K-Means model  
   - Analyze centroids and cluster assignments  

4. **Evaluation**  
   - Compare predicted clusters with known “Private” vs “Public” labels  
   - Use confusion matrix and classification metrics for interpretation  

5. **Visualization**  
   - Use scatter plots and pair plots to visualize cluster separation  

---

