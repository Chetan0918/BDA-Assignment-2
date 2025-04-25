# BDA-Assignment-2
Here’s a clean and concise **README introduction** you can use for your GitHub repo to describe the Spark-based projects for classification, clustering, and recommendation:

---

## 🚀 Spark MLlib Projects using PySpark

This repository contains three machine learning projects built using **Apache Spark's MLlib** on **Google Colab**, demonstrating how to handle large-scale data processing and modeling with PySpark. Each project showcases a different category of machine learning:

---

### 📌 1. Classification Model (Iris Dataset)

We use the classic **Iris dataset** to build a multi-class classification model. The model predicts the species of Iris flowers using features like sepal and petal dimensions. PySpark's `LogisticRegression` from `ml.classification` is used along with proper feature vectorization and evaluation using accuracy.

---

### 📌 2. Clustering Model (Mall Customers Dataset)

A simple customer segmentation task using KMeans clustering is performed on a sample of mall customer data. Customers are grouped based on features like age, annual income, and spending score using `KMeans` from `ml.clustering`. This helps understand patterns in customer behavior.

---

### 📌 3. Recommendation Engine (Mini MovieLens Sample)

This project builds a basic **Recommendation System** using collaborative filtering with the **ALS (Alternating Least Squares)** algorithm. Based on user ratings, the model suggests movies to users. We evaluate the model using RMSE to gauge prediction accuracy.

---

### ⚙️ Tools & Environment

- **Language**: Python  
- **Framework**: Apache Spark (PySpark)
- **Platform**: Google Colab  
- **Library**: Spark MLlib  
- **Evaluation Metrics**: Accuracy, RMSE

---

### 📁 Structure

```
/Spark-Projects
  ├── Classification.ipynb
  ├── Clustering.ipynb
  └── RecommendationEngine.ipynb
```

---

Let me know if you'd like this extended with setup instructions, data sources, or example outputs!
