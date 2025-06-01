# 🧠 Network Traffic Clustering & Anomaly Detection using Machine Learning

This project leverages unsupervised learning techniques to detect and analyze potentially malicious traffic within a large-scale network dataset (CICIDS2017). It includes clustering, explainability (SHAP), and anomaly detection approaches to enhance threat visibility.

---

## 📂 Project Overview

- **Dataset**: CICIDS2017 (268,013 network flows with 79 features)
- **Goal**: Automatically identify behavioral clusters and detect anomalous patterns within normal traffic.
- **Approach**:
  - Exploratory Data Analysis (EDA)
  - Feature Selection & Scaling
  - Unsupervised Clustering (K-Means, DBSCAN, GMM)
  - Model Explainability with SHAP
  - Anomaly Detection using Mahalanobis Distance
  - Evaluation per Cluster

---

## ✨ Key Visualizations

### 📊 Cluster Projection (t-SNE / PCA)

![image](https://github.com/user-attachments/assets/21d1a197-f1ce-461f-bbd1-e803a5c1d7cf)

---

### 🔍 SHAP Summary Plot (Cluster Explainability)

![image](https://github.com/user-attachments/assets/2d48579e-3908-4cae-bfba-a66fa0c901e4)
![image](https://github.com/user-attachments/assets/057eab7b-4851-427c-b3eb-da340b3c3744)



---

### 🌡️ Cluster Profile Heatmap

![image](https://github.com/user-attachments/assets/78899f29-20eb-43d5-8006-1b319662d69f)


> Feature-level profiles of each cluster, helping identify patterns and anomalies.

---

## 🛠️ Tools & Libraries

- Python, Jupyter
- Scikit-learn, Pandas, NumPy
- SHAP, Seaborn, Matplotlib
- CICIDS2017 Dataset

---
