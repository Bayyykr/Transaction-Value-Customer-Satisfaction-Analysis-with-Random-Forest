\# Analisis Faktor yang Mempengaruhi Nilai Transaksi dan Tingkat Kepuasan Pelanggan



\## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data transaksi penjualan guna memahami:

1\. Faktor-faktor yang memengaruhi \*\*nilai total transaksi\*\*

2\. Hubungan antara \*\*kategori produk\*\* dan \*\*tingkat kepuasan pelanggan\*\*



Analisis dilakukan menggunakan pendekatan \*\*data preprocessing, feature engineering, dan machine learning\*\* dengan model Random Forest untuk regression dan classification.



---



\## 📂 Dataset

Dataset merupakan data simulasi transaksi penjualan yang menyerupai kondisi lapangan, berisi informasi:

\- ID transaksi

\- Tanggal transaksi

\- Kategori produk

\- Kota

\- Harga satuan

\- Jumlah pembelian

\- Rating kepuasan

\- Komentar pelanggan



Dataset melalui proses cleaning untuk menangani:

\- Missing values

\- Tipe data tidak sesuai

\- Outlier harga per kategori

\- Feature engineering tanggal



---



\## ⚙️ Tahapan Analisis



\### 1️⃣ Data Cleaning

\- Konversi tipe data tanggal

\- Penanganan missing values

\- Encoding kategori dan kota

\- Pembuatan fitur weekday/weekend

\- Penghapusan outlier harga per kategori



\### 2️⃣ Feature Engineering

\- Membuat fitur `total\_transaksi = harga × jumlah`

\- Ekstraksi informasi hari, bulan, tahun dari tanggal



\### 3️⃣ Regression

\*\*Tujuan:\*\*  

Memprediksi nilai total transaksi



\*\*Model:\*\*  

Random Forest Regressor + Hyperparameter Tuning (GridSearchCV)



\*\*Evaluasi:\*\*  

\- R² Score  

\- MAE  

\- MSE  



\*\*Insight:\*\*  

Feature importance digunakan untuk mengetahui faktor dominan yang memengaruhi nilai transaksi.



---



\### 4️⃣ Classification

\*\*Tujuan:\*\*  

Menganalisis hubungan kategori produk dengan tingkat kepuasan pelanggan



\*\*Model:\*\*  

Random Forest Classifier + Hyperparameter Tuning



\*\*Evaluasi:\*\*  

\- Classification Report  

\- Confusion Matrix  



\*\*Insight:\*\*  

Distribusi kepuasan pelanggan dianalisis per kategori produk.



---



\## 📊 Hasil Utama



\- Model regression menunjukkan performa sangat baik dengan R² tinggi.

\- Faktor paling berpengaruh terhadap nilai transaksi dapat diidentifikasi melalui feature importance.

\- Kategori produk tertentu memiliki kecenderungan rating kepuasan lebih tinggi/rendah.



---



\## 🛠️ Tools \& Library

\- Python

\- Pandas, NumPy

\- Scikit-Learn

\- Matplotlib, Seaborn



---



\## 🎯 Tujuan Pembelajaran

Proyek ini dibuat sebagai portfolio untuk:

\- Melatih proses data preprocessing nyata

\- Membangun model machine learning end-to-end

\- Menghasilkan insight bisnis dari data



---



\## 👤 Author

\*\*Mohamad Bayu Kristanto\*\*  

Mahasiswa Teknik Informatika  

Fokus: Data Science \& Machine Learning



---



\## 📌 Catatan

Notebook tersedia dalam tiga bagian:

1\. Data Cleaning  

2\. Analisis Regression  

3\. Analisis Classification  



Silakan lihat masing-masing notebook untuk detail proses.



