# 🏦 Financial Transaction Analysis & Prediction

## 📌 Overview
Proyek ini bertujuan untuk menganalisis pola transaksi keuangan menggunakan pendekatan **Unsupervised Learning** (untuk segmentasi nasabah) dan **Supervised Learning** (untuk prediksi transaksi).

## 🔍 Methodology
1.  **Customer Segmentation (Clustering):**
    * Menggunakan algoritma **K-Means**.
    * Optimasi cluster menggunakan **Elbow Method** dan evaluasi dengan **Silhouette Score**.
    * Reduksi dimensi dengan **PCA** untuk visualisasi.
2.  **Transaction Prediction (Classification):**
    * Memprediksi kategori transaksi berdasarkan pola cluster.
    * Model yang diuji: Decision Tree, SVM.
    * Optimasi: Hyperparameter Tuning dengan RandomizedSearchCV.

## 📊 Results
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| SVM | 48.19% | 0.45 |
| **Decision Tree (Tuned)** | **96.39%** | **0.96** |

> *Model Decision Tree terbukti paling efektif dalam memprediksi pola transaksi nasabah.*

## 🛠 Technologies
* Python, Pandas, Scikit-Learn, Matplotlib, Seaborn.
