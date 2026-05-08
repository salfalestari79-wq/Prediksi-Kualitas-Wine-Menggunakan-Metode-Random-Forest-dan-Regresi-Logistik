# Prediksi Kualitas Wine Menggunakan Random Forest dan Regresi Logistik

## Deskripsi

Project ini berisi implementasi machine learning untuk memprediksi kualitas wine berdasarkan karakteristik kimianya menggunakan metode **Random Forest** dan **Regresi Logistik**. Analisis dilakukan menggunakan Python dengan tujuan membandingkan performa kedua model dan menentukan metode terbaik berdasarkan nilai akurasi.

---

# Dataset

Dataset yang digunakan terdiri dari:

* `data_training.csv`
* `data_testing.csv`

Variabel target yang diprediksi adalah:

* `quality`

---

# Metode yang Digunakan

* Random Forest Classifier
* Regresi Logistik

---

# Tahapan Analisis

1. Import library
2. Load dataset
3. Data preprocessing
4. Handling missing value
5. Feature scaling
6. Pembagian data training dan validasi
7. Pembuatan model machine learning
8. Evaluasi model menggunakan accuracy
9. Perbandingan performa model
10. Prediksi dataset testing
11. Export hasil prediksi ke CSV

---

# Hasil

Berdasarkan hasil evaluasi:

* Random Forest Accuracy: **0.6163**
* Regresi Logistik Accuracy: **0.5988**

Model terbaik:

* **Random Forest**

---

# Tools & Library

* Python
* Pandas
* NumPy
* Scikit-learn

---

# Output

Hasil prediksi disimpan dalam format CSV:

* `hasilprediksi_randomforest.csv`
* `hasilprediksi_logistik.csv`
* `hasilprediksi_terbaik.csv`

---

# Author

Salfa Lestari

