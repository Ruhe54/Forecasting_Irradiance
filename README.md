# 📈 Forecasting Irradiance dengan Berbagai Algoritma Machine Learning

Proyek ini bertujuan untuk melakukan **peramalan (forecasting) terhadap nilai irradiance** menggunakan beberapa algoritma machine learning dan membandingkan performanya berdasarkan metrik evaluasi seperti **R² Score** dan **Mean Squared Error (MSE)**.

## 🎯 Tujuan Proyek

Tujuan utama dari proyek ini adalah untuk:

- Memprediksi nilai irradiance berdasarkan data historis.
- Membandingkan performa beberapa algoritma machine learning.
- Menentukan algoritma terbaik berdasarkan hasil evaluasi metrik R² Score dan MSE.

## 🛠️ Algoritma yang Digunakan

Proyek ini membandingkan beberapa algoritma berikut:

- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

(Mungkin akan ditambahkan lebih banyak model ke depannya.)

## 📊 Metrik Evaluasi

Evaluasi performa model dilakukan menggunakan dua metrik utama:

- **R² Score (Coefficient of Determination)** – Menunjukkan seberapa baik model menjelaskan variasi data.
- **Mean Squared Error (MSE)** – Mengukur rata-rata kuadrat error antara prediksi dan nilai aktual.

## 📂 Struktur Proyek (Opsional)

```plaintext
forecasting-irradiance/
│
├── data/                  # Folder untuk dataset
├── notebooks/             # Jupyter Notebooks untuk eksplorasi dan modeling
├── models/                # File model yang telah dilatih (jika disimpan)
├── results/               # Visualisasi dan hasil evaluasi
├── README.md              # Dokumentasi proyek
└── requirements.txt       # Daftar dependensi
