# Proyek Machine Learning - Analisis Transaksi Bank

## Deskripsi Proyek
Proyek ini merupakan analisis data transaksi bank menggunakan teknik Machine Learning yang terdiri dari dua komponen utama:
1. Clustering - Segmentasi pelanggan berdasarkan pola transaksi
2. Klasifikasi - Prediksi tipe transaksi (Credit/Debit)

## Informasi Proyek
- Nama: Masahiro Gerarudo Yamazaki
- Email: masahiroymzk24@gmail.com

## Dataset
Dataset yang digunakan berasal dari Kaggle: [Bank Transaction Dataset for Fraud Detection](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection)

### Struktur Dataset
- **Dataset_clustering.csv**: Dataset utama untuk analisis clustering
- **Dataset_inisiasi.csv**: Dataset hasil preprocessing untuk analisis klasifikasi

## Komponen Utama

### 1. Clustering Analysis
- Implementasi algoritma KMeans dan DBSCAN
- Visualisasi menggunakan Elbow Method dan Silhouette Score
- Analisis fitur menggunakan PCA
- Preprocessing data:
  - Normalisasi data numerik
  - Encoding data kategorikal
  - Deteksi dan penanganan outlier

### 2. Klasifikasi Analysis
- Implementasi model:
  - Random Forest Classifier
  - Logistic Regression
- Teknik preprocessing:
  - SMOTE untuk handling imbalance data
  - Feature scaling
  - Label encoding
- Evaluasi model:
  - Confusion Matrix
  - Accuracy Score
  - F1 Score
  - Precision dan Recall

## Persyaratan
- Python 3.x
- Jupyter Notebook
- Library yang diperlukan:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - yellowbrick
  - plotly
  - imbalanced-learn

## Struktur Proyek
.
├── Dataset_clustering.csv         # Dataset untuk analisis clustering
├── Dataset_inisiasi.csv          # Dataset hasil preprocessing
├── README.md                     # Dokumentasi proyek
├── [Clustering]_Submission_Akhir_BMLP_Masahiro_Gerarudo_Yamazaki.ipynb
├── [Klasifikasi]_Submission_Akhir_BMLP_Masahiro_Gerarudo_Yamazaki.ipynb
└── alur proyek.png               # Diagram alur proyek
