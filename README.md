# Klasifikasi Dataset IoT dengan GAN

Proyek ini adalah bagian dari tugas penelitian untuk membangun sistem klasifikasi dataset Internet of Things (IoT) menggunakan Generative Adversarial Network (GAN). Tujuannya adalah untuk meningkatkan akurasi klasifikasi dalam domain IoT dengan memanfaatkan kemampuan GAN untuk menghasilkan data sintetik dan meningkatkan jumlah data pelatihan.

## Fitur Utama

- **Model GAN:** Implementasi model GAN yang dilatih dengan dataset IoT untuk menghasilkan data sintetik yang menyerupai data asli.
- **Klasifikasi Data IoT:** Model klasifikasi dibangun menggunakan data asli dan data sintetik untuk memperbaiki performa.
- **Preprocessing dan Augmentasi Data:** Proses preprocessing diterapkan pada dataset untuk mempersiapkan data bagi model GAN dan klasifikasi.
- **Evaluasi Model:** Metrik evaluasi digunakan untuk menilai performa model klasifikasi dengan dan tanpa augmentasi data GAN.

## Teknologi yang Digunakan

- **Python** (versi 3.x)
- **TensorFlow** dan **Keras** untuk membangun dan melatih model GAN dan klasifikasi
- **NumPy** dan **Pandas** untuk manipulasi data
- **Matplotlib** dan **Seaborn** untuk visualisasi hasil

## Struktur Proyek

```plaintext
├── data/                    # Folder untuk menyimpan dataset
├── models/                  # Folder untuk menyimpan arsitektur dan model yang telah dilatih
├── notebooks/               # Notebook Jupyter untuk eksperimen dan eksplorasi
├── src/                     # Kode utama untuk model GAN dan klasifikasi
│   ├── gan.py               # Kode implementasi model GAN
│   ├── classifier.py        # Kode implementasi model klasifikasi
│   └── utils.py             # Fungsi utilitas seperti preprocessing
├── README.md                # Deskripsi proyek ini
└── requirements.txt         # Daftar dependensi Python
```
