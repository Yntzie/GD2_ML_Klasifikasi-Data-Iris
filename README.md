# Model 2: Logistic Regression

## Deskripsi Singkat
Repository ini berisi notebook **`GD2_ML_2_12298.ipynb`** untuk keperluan pembelajaran/eksperimen machine learning/data analysis. Dokumen ini merangkum kebutuhan environment, cara menjalankan ulang eksperimen, serta garis besar isi notebook.

## Struktur Notebook
Rangkuman heading yang terdeteksi dari sel markdown:
1) Persiapan environment & impor pustaka
2) Memuat dataset Iris dari <code>sklearn.datasets
Eksplorasi Data Awal
3) Pembagian data latih/uji
4) Standarisasi fitur (scaling)
5) Model 1: Perceptron
   Pembuatan Fungsi untuk Visualisasi Area Keputusan
6) Model 2: Logistic Regression
   Mengatasi Overfitting dengan Regularisasi
7) Model 3: Support Vector Machine (SVM) — implementasi via scikit-learn `SVC`
8) Model 5 : Random Forests
9) Model 6 :K-nearest neighbors
Simpan & Muat Model dengan Pickle

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

### Opsi B — Instal manual (jika tanpa requirements.txt)
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

## Catatan Proses & Model
- **Fungsi yang terdefinisi** (contoh, maksimal 12): plot_decision_regions
- **Pemanggilan kelas/fungsi model yang terdeteksi** (heuristik, maksimal 12): DataFrame, KNeighborsClassifier, ListedColormap, LogisticRegression, Perceptron, RandomForestClassifier, SVC, StandardScaler, accuracy_score, append, arange, argmax
- **Operasi data masukan** yang terdeteksi (heuristik): _(tidak ada pembacaan data tabular yang terdeteksi secara eksplisit)_.
