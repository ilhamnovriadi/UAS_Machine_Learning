# Tugas UAS Machine Learning - Analisis & Prediksi Penyakit Jantung

Repositori ini dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) mata kuliah Machine Learning. Proyek ini berfokus pada penggunaan algoritma **Decision Tree** untuk memprediksi penyakit jantung berdasarkan dataset **Heart Disease**.

## 📂 Studi Kasus
**Dataset yang dipilih:** Heart Disease
Dataset ini digunakan untuk membangun model klasifikasi yang dapat memprediksi keberadaan penyakit jantung pada pasien berdasarkan berbagai atribut medis (seperti usia, jenis kelamin, tekanan darah, kolesterol, dll).

## 📝 Instruksi Tugas

Tugas ini terdiri dari tiga bagian utama:

### Bagian 1: Pemahaman Konsep (Teori)
Membahas konsep dasar algoritma Decision Tree, termasuk:
- Definisi Decision Tree.
- Konsep Node, Root, Leaf, Splitting, dan Pruning.
- Perbedaan antara Decision Tree, Random Forest, dan Gradient Boosting.
- Kelebihan dan kekurangan metode berbasis tree (tree-based methods).

### Bagian 2: Implementasi Model
Implementasi dilakukan menggunakan bahasa pemrograman **Python** dengan library **scikit-learn**. Langkah-langkah meliputi:
1. **Exploratory Data Analysis (EDA)**: Memuat dan memahami struktur data.
2. **Preprocessing**: Penanganan missing values, encoding fitur kategorikal, dan pembagian data (train/test split).
3. **Pembuatan Model**: Membangun model Decision Tree dan melakukan tuning hyperparameter (seperti `max_depth`, `criterion`).
4. **Evaluasi**: Mengukur performa model menggunakan metrik Accuracy, Precision, Recall, dan F1-score.
5. **Visualisasi**: Menampilkan struktur pohon keputusan yang terbentuk.

### Bagian 3: Analisis dan Kesimpulan
Berisi analisis hasil eksperimen, faktor yang mempengaruhi performa model, serta kesimpulan mengenai efektivitas metode Decision Tree untuk studi kasus penyakit jantung.

## 📁 Struktur Direktori

```
/
├── Bagian 2 – Implementasi Model/
│   ├── heart.csv                 # Dataset Heart Disease
│   └── uas-heart-disease.ipynb   # Jupyter Notebook berisi source code implementasi
├── readme.md                     # Dokumentasi proyek ini
└── ...
```

## 🚀 Cara Menjalankan

1. Clone repositori ini ke komputer lokal Anda.
2. Pastikan Anda memiliki Python dan library yang dibutuhkan (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Buka file `uas-heart-disease.ipynb` menggunakan Jupyter Notebook atau Google Colab.
4. Jalankan setiap sel kode secara berurutan untuk melihat proses analisis dan hasil prediksi.

## 📊 Hasil Singkat
Detail hasil evaluasi model, visualisasi pohon keputusan, dan analisis mendalam dapat dilihat langsung di dalam file notebook `uas-heart-disease.ipynb`.

---
*Tugas ini disusun sebagai syarat kelulusan mata kuliah Machine Learning.*
