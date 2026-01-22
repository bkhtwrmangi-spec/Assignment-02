# Assignment 2 – Data Science Projects

## 📌 Overview

This repository contains **Assignment 2** for the Data Science internship at **Arch Technologies**. The assignment focuses on applying machine learning techniques to solve real-world problems using Python.

The assignment includes two main tasks:

* **Task 3:** Customer Segmentation using KMeans Clustering
* **Task 4:** Movie Rating Prediction using Collaborative Filtering

All work is implemented in **Jupyter Notebooks**, with clear steps, comments, and visualizations.

---

## 🧩 Task 3: Customer Segmentation

### 🔹 Objective

To group customers into different segments based on their purchasing behavior using clustering techniques.

### 🔹 Dataset

* Customer dataset containing:

  * Gender
  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

### 🔹 Methodology

* Data preprocessing and feature selection
* Feature scaling using **StandardScaler**
* Applying **KMeans clustering**
* Determining optimal clusters
* Visualizing customer segments

### 🔹 Output

* Identified meaningful customer segments
* Visual representation of clusters
* Business insights based on customer behavior

---

## 🎬 Task 4: Movie Rating Prediction

### 🔹 Objective

To predict how a user might rate a movie they have not yet watched.

### 🔹 Dataset

* **MovieLens 100K Dataset** (Kaggle)
* File used: `u.data`
* Columns:

  * user_id
  * movie_id
  * rating
  * timestamp

### 🔹 Methodology

* Created a user–movie rating matrix
* Handled missing values
* Applied **User-Based Collaborative Filtering**
* Used **Cosine Similarity** to measure user similarity
* Evaluated model performance using **RMSE**

### 🔹 Output

* Predicted movie ratings for users
* Model performance measured using RMSE

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
Assignment-02/
│── Task3_Customer_Segmentation.ipynb
│── Task4_Movie_Rating_Prediction.ipynb
│── u.data
│── README.md
```

---

## ✅ Conclusion

This assignment demonstrates the practical application of machine learning techniques such as clustering and collaborative filtering. The tasks showcase data preprocessing, model building, evaluation, and visualization skills essential for real-world data science problems.

---

## 👤 Author

**Bakhtawar**
Data Science & AI Intern
**Arch Technologies**
