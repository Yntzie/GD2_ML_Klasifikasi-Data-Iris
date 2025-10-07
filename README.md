# Model 2: Logistic Regression

## Deskripsi Singkat
Repository ini berisi notebook **`GD2_ML_2_12298.ipynb`** untuk keperluan pembelajaran/eksperimen machine learning/data analysis. Dokumen ini merangkum kebutuhan environment, cara menjalankan ulang eksperimen, serta garis besar isi notebook.

## Struktur Notebook
Persiapan environment & impor pustaka

Memuat dataset Iris dari sklearn.datasets
Eksplorasi Data Awal

Pembagian data latih/uji

Standarisasi fitur (scaling)

Model 1: Perceptron
Pembuatan fungsi untuk visualisasi area keputusan

Model 2: Logistic Regression
Mengatasi overfitting dengan regularisasi

Model 3: Support Vector Machine (SVM) — implementasi via scikit-learn.SVC

Model 5: Random Forests

Model 6: K-Nearest Neighbors (KNN)
Simpan & muat model dengan Pickle

## Kebutuhan & Instalasi
### Virtual Environment (disarankan)
```bash
# Dari folder proyek
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# Linux/macOS
# source .venv/bin/activate

# Instal dependensi
pip install -r requirements.txt
```

### Instal manual (jika tanpa requirements.txt)
Paket pihak-ketiga yang terdeteksi dari notebook:
```
distutils
matplotlib
numpy
pandas
pickle
scikit-learn
```

## Cara Menjalankan
1. Aktifkan environment (lihat bagian *Kebutuhan & Instalasi*).
2. Buka notebook:
   ```bash
   jupyter notebook GD2_ML_2_12298.ipynb
   ```
   atau gunakan VS Code / Jupyter Lab.
3. Jalankan sel dari awal sampai akhir (*Run All*). Pastikan dataset/berkas yang dirujuk tersedia pada path yang benar.
