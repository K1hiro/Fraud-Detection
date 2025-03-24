Fraud Detection System
Overview
Fraud Detection System adalah proyek machine learning yang bertujuan untuk mendeteksi transaksi keuangan yang mencurigakan (fraud) menggunakan dataset kartu kredit. Proyek ini memanfaatkan algoritma Random Forest, XGBoost, serta Logistic Regression untuk membandingkan performa dalam mendeteksi transaksi penipuan.

Dataset https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
Dataset yang digunakan adalah Credit Card Fraud Detection Dataset, yang mengandung transaksi keuangan dengan label:
0 - Transaksi Normal
1 - Transaksi Fraud (Penipuan)
Features
Preprocessing Data
 -Standarisasi fitur Amount menggunakan StandardScaler
 -Pembagian dataset menjadi train dan test
Modeling
 -Random Forest Classifier
 -XGBoost Classifier
 -Logistic Regression
Handling Imbalance Data
 -Menggunakan SMOTE untuk meningkatkan jumlah sampel kelas minoritas
Evaluasi Model
 -Accuracy Score, Classification Report, dan Confusion Matrix
