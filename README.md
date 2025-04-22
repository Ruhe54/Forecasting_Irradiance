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
├── data/                      # Dataset dan hasil preprocessing
├── models/                    # Model yang sudah dilatih (opsional)
├── results/                   # Grafik hasil evaluasi dan visualisasi
├── algorithms/                # Implementasi setiap algoritma dalam file terpisah
│   ├── random_forest.py       # Random Forest Regressor
│   ├── gradient_boosting.py   # Gradient Boosting Regressor
│   └── xgboost_model.py       # XGBoost Regressor
├── utils/                     # Fungsi bantu dan preprocessing
├── README.md                  # Dokumentasi proyek
└── requirements.txt           # Daftar dependensi proyek

