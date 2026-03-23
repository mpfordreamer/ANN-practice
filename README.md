# Artificial Neural Network (ANN) - Heart Failure Prediction

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi risiko kematian akibat gagal jantung menggunakan model **Artificial Neural Network (ANN)**. Model ini melatih data klinis pasien untuk menentukan faktor risiko dan probabilitas keselamatan (`DEATH_EVENT`).

---

## 📂 Struktur Proyek
```text
ANN/
├── dataset/
│   └── heart-rate-dataset.csv  # Dataset Klinis Gagal Jantung
└── ANN-practice.ipynb         # Notebook Latihan ANN
```

---

## 🛠️ Ringkasan & Library
Model dibangun menggunakan jaringan saraf tiruan (ANN) untuk klasifikasi biner.

**Library Utama:**
*   `pandas` & `numpy`: Pengolahan dan manipulasi data.
*   `seaborn` & `matplotlib`: Visualisasi data (Distribusi target, Matriks Korelasi).
*   `sklearn`: Preprocessing (StandardScaler), Data Splitting.
*   `keras` / `tensorflow`: Arsitektur model Sequential (Dense Layer).

---

## 🚀 Cara Menjalankan
Untuk menjalankan notebook ini secara interaktif di **Google Colab**, ikuti langkah berikut:

1.  **Buka Google Colab**: Masuk ke [Google Colab](https://colab.research.google.com/).
2.  **Upload Notebook**: Pilih tab `Upload` dan pilih file `ANN-practice.ipynb`.
3.  **Upload Dataset**:
    *   Pastikan path dataset di notebook sesuai (misal: `dataset/heart-rate-dataset.csv`).
    *   Upload file `heart-rate-dataset.csv` ke session storage Colab.
4.  **Jalankan Sel**: Klik `Runtime` -> `Run all` atau jalankan sel satu per satu dari atas ke bawah.

---

## 📊 Informasi Dataset
Dataset ini berisi catatan medis pasien dengan fitur-fitur seperti:
*   `age`: Umur pasien.
*   `anaemia`: Penurunan sel darah merah/hemoglobin.
*   `creatinine_phosphokinase`: Kadar enzim CPK.
*   `diabetes`: Status diabetes.
*   `ejection_fraction`: Persentase darah keluar dari jantung.
*   `high_blood_pressure`: Status hipertensi.
*   `platelets`: Jumlah keping darah.
*   `serum_creatinine`: Kadar kreatinin.
*   `serum_sodium`: Kadar natrium.
*   `sex`: Jenis kelamin.
*   `smoking`: Status merokok.
*   `time`: Periode tindak lanjut.
*   **`DEATH_EVENT`** (Target): Kematian pasien selama periode (0 = Hidup, 1 = Meninggal).
