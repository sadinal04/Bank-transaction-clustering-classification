# 🏦 Bank Transaction Clustering & Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Deskripsi

Proyek ini mengimplementasikan **end-to-end Machine Learning Pipeline** menggunakan **Bank Transaction Dataset** untuk melakukan segmentasi transaksi melalui **unsupervised learning (clustering)**, kemudian membangun model **supervised learning (classification)** berdasarkan hasil segmentasi tersebut.

Pipeline mencakup seluruh tahapan mulai dari **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, **feature selection**, **K-Means Clustering**, hingga **classification** menggunakan beberapa algoritma Machine Learning dan evaluasi performa model.

---

## 🎯 Tujuan Proyek

- Melakukan data cleaning dan preprocessing pada dataset transaksi perbankan.
- Mengidentifikasi pola transaksi menggunakan K-Means Clustering.
- Menentukan jumlah cluster terbaik menggunakan Elbow Method dan Silhouette Score.
- Membangun model klasifikasi berdasarkan label hasil clustering.
- Membandingkan performa beberapa algoritma Machine Learning.
- Melakukan hyperparameter tuning untuk memperoleh model terbaik.

---

## 📊 Dataset

Dataset yang digunakan merupakan **Bank Transaction Dataset** yang berisi **2.512 transaksi** dengan **16 fitur**, meliputi:

- Customer Information
- Transaction Details
- Merchant Information
- Account Balance
- Device Type
- Transaction Type
- Location
- dan berbagai atribut transaksi lainnya.

---

## ⚙️ Machine Learning Pipeline

### 1. Data Preprocessing

- Data Cleaning
- Missing Value Handling
- Feature Selection
- Label Encoding
- Standardization
- Exploratory Data Analysis (EDA)

---

### 2. Unsupervised Learning

- K-Means Clustering
- Elbow Method
- Silhouette Score
- Principal Component Analysis (PCA)
- Cluster Interpretation

---

### 3. Supervised Learning

Model yang digunakan:

- K-Nearest Neighbors (KNN)
- Gaussian Naïve Bayes

Optimasi model dilakukan menggunakan:

- GridSearchCV

---

## 📈 Key Insights

### 📊 Optimal Number of Clusters

Menggunakan **Elbow Method** dan **Silhouette Score**, diperoleh jumlah cluster terbaik sebanyak **3 cluster** dengan kualitas segmentasi yang baik.

---

### 🔍 Feature Selection Improves Clustering

Penggunaan **SelectKBest** berhasil meningkatkan kualitas cluster sehingga segmentasi transaksi menjadi lebih representatif.

---

### 💳 Transaction Segmentation

Setiap cluster memiliki karakteristik transaksi yang berbeda berdasarkan:

- Transaction Amount
- Account Balance
- Customer Age
- Merchant Category
- Device Type
- Transaction Type

Segmentasi ini membantu memahami perilaku transaksi pelanggan.

---

### 🤖 Classification Performance

Model klasifikasi berhasil mempelajari hasil segmentasi yang diperoleh dari proses clustering.

Perbandingan model menunjukkan bahwa:

- **K-Nearest Neighbors (KNN)** memberikan performa terbaik dengan akurasi sekitar **99.4%**.
- **Gaussian Naïve Bayes** juga memberikan performa yang baik dan meningkat setelah dilakukan hyperparameter tuning.

---

### ⚡ Hyperparameter Tuning

Optimasi menggunakan **GridSearchCV** meningkatkan performa Gaussian Naïve Bayes sehingga menghasilkan model yang lebih optimal dibandingkan konfigurasi awal.

---

## 📊 Hasil Proyek

Melalui proyek ini berhasil:

- Membersihkan dan mempersiapkan dataset transaksi.
- Menghasilkan segmentasi transaksi menggunakan K-Means Clustering.
- Menentukan jumlah cluster terbaik menggunakan Elbow Method dan Silhouette Score.
- Membangun model klasifikasi berbasis hasil clustering.
- Membandingkan performa beberapa algoritma Machine Learning.
- Melakukan hyperparameter tuning.
- Menghasilkan pipeline Machine Learning end-to-end dari preprocessing hingga evaluasi model.

---

## 🛠️ Teknologi

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Machine Learning

- K-Means Clustering
- K-Nearest Neighbors (KNN)
- Gaussian Naïve Bayes

### Feature Engineering

- Label Encoding
- StandardScaler
- SelectKBest
- PCA

### Model Evaluation

- Elbow Method
- Silhouette Score
- Confusion Matrix
- Classification Report
- Accuracy Score
- GridSearchCV

---

## 📌 Future Improvements

- Menambahkan algoritma clustering lain (DBSCAN, Agglomerative Clustering, Gaussian Mixture Model).
- Mencoba algoritma klasifikasi lain seperti Random Forest, XGBoost, dan LightGBM.
- Melakukan deployment model menggunakan Streamlit atau FastAPI.
- Menambahkan explainability menggunakan SHAP atau LIME.

---

## 👨‍💻 Author

**Sadinal Mufti**

- GitHub: https://github.com/sadinal04
- LinkedIn: https://www.linkedin.com/in/sadinalmufti/

---

⭐ Jika repository ini bermanfaat, jangan lupa memberikan **Star** pada repository ini.
