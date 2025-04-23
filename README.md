# Proyek Klasifikasi Gambar - Waste Classification

Proyek ini bertujuan untuk mengklasifikasikan gambar sampah ke dalam dua kategori: **Organic** dan **Recyclable**. Proyek ini menggunakan TensorFlow untuk membangun model klasifikasi gambar dan mengkonversi model tersebut ke dalam format TFLite dan TensorFlow.js.


## Dataset

Dataset yang digunakan dalam proyek ini dapat diunduh melalui link berikut:
- **Dataset Waste Classification**: [Kaggle - Waste Classification](https://www.kaggle.com/datasets/techsash/waste-classification-data)

## Struktur Direktori

```plaintext
submission/
│
├── saved_model/             # Model yang disimpan setelah pelatihan
├── tfjs_model/              # Model yang dikonversi untuk digunakan dengan TensorFlow.js
├── tflite/                  # Model yang dikonversi untuk digunakan pada perangkat mobile
│   └── model.tflite         # File model TFLite
├── requirements.txt         # Daftar dependensi untuk proyek
├── notebook.ipynb           # Notebook Jupyter yang digunakan untuk pelatihan model
└── README.md                # Panduan penggunaan proyek ini
```

## Persyaratan

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal semua dependensi yang dibutuhkan. Anda dapat menginstalnya menggunakan file `requirements.txt` yang disediakan.

1. **Menginstal dependensi**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Menyiapkan Dataset**:
   - Unduh dataset dari [link Kaggle](https://www.kaggle.com/datasets/techsash/waste-classification-data).
   - Ekstrak dataset dan letakkan dalam direktori yang sesuai.
