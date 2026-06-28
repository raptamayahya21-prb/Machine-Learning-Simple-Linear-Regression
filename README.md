# Prediksi Nilai Murid Menggunakan Simple Linear Regression

Proyek ini menerapkan salah satu teknik statistik dan machine learning paling dasar, yaitu **Simple Linear Regression (Regresi Linear Sederhana)**. Tujuannya adalah untuk memprediksi suatu nilai output (nilai murid) berdasarkan satu variabel input (fitur) menggunakan pustaka (*library*) `scikit-learn` pada bahasa pemrograman Python.

---

## 📋 Deskripsi Proyek

Proyek ini mencakup alur kerja *data science* terstruktur yang diimplementasikan di dalam Jupyter Notebook:
1. **Eksplorasi & Pemahaman Data:** Menggunakan dataset performa murid (*Student Performance*) yang bersumber dari Kaggle untuk menganalisis hubungan antar variabel.
2. **Pra-pemrosesan Data (Preprocessing):** Menentukan variabel prediktor/fitur ($X$ atau *explanatory variable*) dan variabel target ($y$ atau *response variable*), serta membagi data menjadi training set dan testing set.
3. **Pemodelan:** Menginisialisasi dan melatih model `LinearRegression` menggunakan pustaka Scikit-Learn untuk mencari nilai *intercept* ($\alpha$) dan *slope/coefficient* ($\beta$).
4. **Evaluasi Model:** Mengukur performa dan kecocokan model menggunakan metrik **R² Score (Coefficient of Determination)** untuk mengetahui seberapa baik model dalam memprediksi data baru.

---

## 📊 Dataset

* **Sumber Data:** Dataset Performa Murid (*Student Performance*) dari Kaggle.
* **Karakteristik Data:** Memiliki 1 Fitur utama ($X$) sebagai variabel bebas dan 1 Target ($y$) sebagai variabel terikat yang ingin diprediksi nilainya.

---

## 🛠️ Teknologi dan Library yang Digunakan

Proyek ini dibangun menggunakan ekosistem data science Python berikut:
* **Python 3**
* **Pandas:** Untuk memuat data (`read_csv`), manipulasi data, dan menampilkan struktur DataFrame.
* **Scikit-Learn (Sklearn):** * `LinearRegression` untuk pembuatan dan pelatihan model regresi.
  * Metrik evaluasi untuk menghitung performa nilai $R^2$.

---

Created by **Raptama Yahya Purba**
