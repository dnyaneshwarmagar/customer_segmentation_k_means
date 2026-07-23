# 🛍️ Mall Customer Segmentation using K-Means Clustering

A Machine Learning project that performs customer segmentation using the K-Means Clustering algorithm. The project analyzes customer purchasing behavior based on **Annual Income** and **Spending Score**, groups customers into meaningful clusters, and provides an interactive **Streamlit web application** for predicting the customer segment.

---

## 📌 Project Overview

Customer segmentation helps businesses understand different types of customers so they can design personalized marketing strategies.

In this project, customers are grouped into **5 clusters** using the K-Means clustering algorithm based on:

- Annual Income (k$)
- Spending Score (1-100)

The trained model is deployed using **Streamlit**, allowing users to enter customer details and instantly identify the customer segment.

---

## 🚀 Features

- Data preprocessing and exploration
- Exploratory Data Analysis (EDA)
- Customer segmentation using K-Means Clustering
- Elbow Method to determine optimal number of clusters
- Cluster visualization
- Model serialization using Pickle
- Interactive Streamlit Web App
- Real-time customer segment prediction

---

## 📂 Dataset

**Dataset:** Mall Customers Dataset

Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, only the following features are used:

- Annual Income (k$)
- Spending Score (1-100)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle

---

## 📊 Exploratory Data Analysis

Performed:

- Dataset Information
- Missing Value Check
- Gender Distribution
- Histograms
- Correlation Heatmap

Visualizations include:

- Count Plot
- Distribution Plot
- Heatmap
- Cluster Scatter Plot
- Elbow Method Graph

---

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means groups customers based on feature similarity.

### Steps:

1. Load Dataset
2. Select Features
3. Apply Elbow Method
4. Train K-Means (k=5)
5. Predict Customer Cluster
6. Save Model using Pickle

---

## 📈 Elbow Method

The Within Cluster Sum of Squares (WCSS) is calculated for values of K ranging from 1 to 10.

From the Elbow Curve,

**Optimal Number of Clusters = 5**

---

## 📌 Cluster Description

| Cluster | Description |
|----------|-------------|
| Cluster 0 | Medium Income • Medium Spending |
| Cluster 1 | High Income • High Spending |
| Cluster 2 | Low Income • High Spending |
| Cluster 3 | High Income • Low Spending |
| Cluster 4 | Low Income • Low Spending |

---

## 🖥️ Streamlit Application

The application allows users to:

- Enter Annual Income
- Enter Spending Score
- Predict Customer Cluster
- Display Customer Segment Description

---

## 📁 Project Structure

```
Mall-Customer-Segmentation/
│
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── app.py
├── k_means.pkl
├── requirements.txt
├── README.md
└── images/
      ├── elbow_method.png
      └── clustering.png
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Mall-Customer-Segmentation.git
```

Move into project directory

```bash
cd Mall-Customer-Segmentation
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📸 Screenshots

### Elbow Method

(Add Screenshot Here)

---

### Customer Segmentation

(Add Screenshot Here)

---

### Streamlit App

(Add Screenshot Here)

---

## 📊 Sample Prediction

Input

```
Annual Income = 90
Spending Score = 85
```

Output

```
Cluster 1

Customers with high annual income and high annual spending.
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Unsupervised Machine Learning
- K-Means Clustering
- Elbow Method
- Customer Segmentation
- Exploratory Data Analysis
- Streamlit Deployment
- Model Serialization using Pickle

---

## 🔮 Future Improvements

- Use additional customer features such as Age and Gender.
- Automatic selection of optimal K using Silhouette Score.
- Deploy on Streamlit Cloud.
- Add downloadable prediction reports.
- Compare K-Means with DBSCAN and Hierarchical Clustering.

---

## 👨‍💻 Author

**Dnyaneshwar Magar**

If you found this project useful, don't forget to ⭐ the repository.