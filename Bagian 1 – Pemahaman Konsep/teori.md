# Bagian 1 – Pemahaman Konsep (Teori)

### 1. Apa yang dimaksud dengan Decision Tree?
**Decision Tree** adalah algoritma *supervised learning* non-parametrik yang digunakan untuk tugas klasifikasi dan regresi. Algoritma ini memodelkan keputusan dan konsekuensi yang mungkin terjadi dalam struktur seperti pohon (tree-like structure), di mana setiap simpul internal mewakili pengujian pada atribut, setiap cabang mewakili hasil pengujian, dan setiap simpul daun (leaf node) memegang label kelas atau nilai target.

### 2. Jelaskan konsep berikut:
- **Node**: Titik keputusan dalam pohon di mana data dipisahkan berdasarkan fitur tertentu.
- **Root**: Node paling atas dari pohon (awal mula) yang berisi seluruh dataset sebelum percabangan apa pun.
- **Leaf (Daun)**: Node terminal atau ujung dari pohon yang tidak memiliki cabang lagi. Ini merepresentasikan hasil prediksi atau keputusan akhir.
- **Splitting**: Proses membagi sebuah node menjadi dua atau lebih sub-node berdasarkan kriteria tertentu (misalnya Gini Impurity atau Entropy) untuk memisahkan kelas target sebaik mungkin.
- **Pruning**: Proses pemangkasan cabang pohon yang tidak signifikan atau terlalu kompleks untuk mencegah *overfitting*. Pruning bisa dilakukan saat pembentukan pohon (*pre-pruning*) atau setelah pohon terbentuk (*post-pruning*).

### 3. Apa perbedaan Decision Tree, Random Forest, dan Gradient Boosting?
| Fitur | Decision Tree | Random Forest | Gradient Boosting |
|-------|---------------|---------------|-------------------|
| **Definisi** | Satu pohon keputusan tunggal. | Kumpulan banyak pohon keputusan (Bagging). | Kumpulan pohon yang dibangun secara berurutan (Boosting). |
| **Cara Kerja** | Membagi data secara rekursif hingga kriteria berhenti terpenuhi. | Membangun banyak pohon secara independen (paralel) dan mengambil suara mayoritas. | Membangun pohon secara sekuensial, di mana pohon baru memperbaiki kesalahan pohon sebelumnya. |
| **Kecenderungan** | Cenderung *overfitting* (varian tinggi). | Mengurangi varian (lebih stabil & akurat). | Mengurangi bias dan varian (sangat akurat). |
| **Kecepatan** | Cepat dilatih & diprediksi. | Lambat dilatih (banyak pohon), cepat diprediksi. | Lambat dilatih (sekuensial), cukup cepat diprediksi. |

### 4. Sebutkan kelebihan dan kekurangan tree-based methods.
**Kelebihan:**
- Mudah diinterpretasikan dan divisualisasikan (khususnya Decision Tree tunggal).
- Tidak memerlukan penskalaan fitur (seperti Normalization/Standardization).
- Dapat menangani data numerik dan kategorikal sekaligus.
- Tahan terhadap outlier dibandingkan model linear.

**Kekurangan:**
- Decision Tree tunggal sangat rentan terhadap *overfitting*.
- Bisa menjadi tidak stabil; perubahan kecil pada data bisa menghasilkan pohon yang sangat berbeda.
- Cenderung bias jika kelas tidak seimbang (imbalanced class).
