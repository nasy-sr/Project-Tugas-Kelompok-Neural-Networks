# Project Tugas Kelompok Neural Networks 
**Mata Kuliah:** MKB24003 - Machine Learning (3 SKS)
**Universitas Darwan Ali**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)

##  Anggota Kelompok
* **Nama Anggota 1:** Nasywa Salsabiila Romadhona (2457201002354)
* **Nama Anggota 2:** Krisopras Yaspis Verlenia (2457201002361)
* **Nama Anggota 3:** Oktavia Ramadhani (2457201002385)
* **Nama Anggota 4:** Nisa Puspita Sari (2457201002448)

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan **Artificial Neural Networks (ANN)** secara *end-to-end* pada empat domain dataset yang berbeda. Sesuai dengan tujuan pembelajaran, kami melakukan preprocessing data, membangun arsitektur model, dan mengevaluasi performanya untuk pengambilan keputusan sistem informasi.

Kami menggunakan 4 dataset dengan karakteristik unik:
1.  **Online Retail II:** Data transaksi ritel (Sparse Data).
2.  **Heart Failure Clinical Records:** Data medis klinis (Imbalanced Data).
3.  **Financial Market Data:** Data harga saham (Time-Series).
4.  **Hotel Booking Demand:** Data reservasi hotel (Categorical & Numerical).


## Hasil Analisis & Evaluasi

### 1. Online Retail Classification 
* **Dataset:** [UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
* **Tugas:** Klasifikasi perilaku transaksi.
* **Hasil:** Akurasi **100%**.
* **Analisis:** Fitur transaksi sangat distingsif sehingga model mampu membedakan kelas dengan sempurna.

### 2. Heart Failure Prediction 
* **Dataset:** [UCI Heart Failure Clinical Records](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)
* **Tugas:** Prediksi risiko kematian pasien (Binary Classification).
* **Hasil:** Akurasi **77%**, namun Recall untuk kelas risiko kematian masih perlu ditingkatkan (55%).
* **Analisis:** Tantangan utama adalah ketidakseimbangan data (*imbalanced*), disarankan menggunakan teknik SMOTE ke depannya.

### 3. Stock Price Prediction 
* **Dataset:** Historical Stock Data (Time-Series).
* **Tugas:** Regresi prediksi harga penutupan (*Close Price*).
* **Hasil:** Model mengalami *Overfitting* (Gap besar antara Training & Validation Loss).
* **Analisis:** Model Neural Network terlalu kompleks untuk jumlah data time-series yang terbatas. Pendekatan LSTM mungkin lebih cocok dibandingkan MLP standar.

### 4. Hotel Booking Demand 
* **Dataset:** [Kaggle Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
* **Tugas:** Prediksi pembatalan reservasi.
* **Hasil:** Akurasi **100%**, Precision **1.0**, Recall **1.0**.
* **Analisis:** Model sangat efektif. Fitur seperti `Deposit Type` (Non-Refundable) menjadi indikator pembatalan yang sangat kuat.


## Struktur Repository
* `/data`: Berisi file dataset (atau link sumber data untuk file besar).
* `/notebooks`: Kode sumber lengkap dalam format `.ipynb` (Google Colab).
* `/reports`: Dokumentasi laporan akhir dalam format PDF.

---
*Dibuat untuk memenuhi Tugas Project Semester Ganjil 2025.*
