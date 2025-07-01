# UAS Kecerdasan Buatan

## Judul Project
Implementasi Prediksi Diabetes Mellitus Menggunakan Random Forest pada Dataset Pima Indians

## Deskripsi Singkat
Project ini bertujuan untuk membangun model machine learning yang dapat memprediksi risiko diabetes pada pasien menggunakan algoritma Random Forest. Dataset yang digunakan adalah *Pima Indians Diabetes Dataset* yang berisi data kesehatan pasien wanita dengan delapan fitur utama.

---

## Langkah Pengerjaan

1. **Pengumpulan Data**
   - Menggunakan *Pima Indians Diabetes Dataset* yang tersedia publik.
2. **Pra-Pemrosesan Data**
   - Mengatasi nilai 0 yang tidak valid dengan imputasi median.
   - Melakukan normalisasi seluruh fitur numerik.
   - Memisahkan data menjadi data latih (80%) dan data uji (20%).
3. **Pembangunan Model**
   - Melatih model Random Forest pada data latih.
   - Melakukan tuning hyperparameter untuk optimasi hasil.
4. **Evaluasi Model**
   - Menggunakan metrik Akurasi, Precision, Recall, F1 Score, dan confusion matrix.
   - Melakukan analisis feature importance.
5. **Dokumentasi & Visualisasi**
   - Seluruh proses didokumentasikan di notebook Jupyter (`notebook_model.ipynb`).
   - Hasil visualisasi (confusion matrix) disimpan di folder `Assets`.

---

---

## Referensi Jurnal Ilmiah

1. Massari, H. El, Gherabi, N., Qanouni, F., & Mhammedi, S. (2024). Diabetes Prediction Using Machine Learning with Feature Engineering and Hyperparameter Tuning. *International Journal of Advanced Computer Science and Applications, 15(8)*, 171–179. [https://doi.org/10.14569/IJACSA.2024.0150818](https://doi.org/10.14569/IJACSA.2024.0150818)
2. Noviyanti, C. N., & Alamsyah, A. (2024). Early Detection of Diabetes Using Random Forest Algorithm. *Journal of Information System Exploration and Research, 2(1)*, 41–48. [https://doi.org/10.52465/joiser.v2i1.245](https://doi.org/10.52465/joiser.v2i1.245)
3. Zhang, Z. (2025). Comparison of Machine Learning Models for Predicting Type 2 Diabetes Risk Using the Pima Indians Diabetes Dataset. *Journal of Informatics and Medical Research, 4(1)*, 65–71. [https://doi.org/10.56397/JIMR/2025.02.07](https://doi.org/10.56397/JIMR/2025.02.07)

---

## Cara Menjalankan Project

1. **Clone** repository ini ke komputer Anda.
2. Buka `notebook_model.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3. Pastikan file dataset (`dataset.csv`) tersedia di folder `data/`.
4. Jalankan notebook dari awal hingga akhir untuk mereproduksi seluruh hasil.

---

## Visualisasi

**Confusion Matrix:**  
![Confusion Matrix](Assets/confusion%20matrix.png)

---

## Catatan

- Laporan lengkap tersedia di file `uas_ai.md` atau PDF.
- Semua referensi jurnal ilmiah disimpan di folder `data/Jurnal/`.
- Jika ada pertanyaan atau kendala, silakan hubungi author via [GitHub Issues](#).

## Struktur Repository

