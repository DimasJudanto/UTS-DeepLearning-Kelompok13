# Kode UTS Deep Learning

Setiap task adalah satu notebook Google Colab yang menjalankan semua langkah dari data mentah sampai file prediksi, termasuk semua tabel dan grafik di laporan.
| File | Task | Output |
|---|---|---|
| task1_klasifikasi.ipynb | Task 1: klasifikasi multimodal cacat produk | prediksi_klasifikasi.csv |
| task2_rul.ipynb | Task 2: prediksi remaining useful life | prediksi_rul.csv |
| task3_clustering.ipynb | Task 3: clustering jenis material | cluster.csv |

## Data
Data tidak disertakan. File yang dibutuhkan:
- Task 1: `klasifikasi_train.npz`, `klasifikasi_test.npz`, `klasifikasi_train_meta.csv`, `klasifikasi_test_meta.csv`
- Task 2: `rul_train.csv.gz`, `rul_test.csv.gz`
- Task 3: `clustering.npz`, `clustering_meta.csv`

## Cara mereproduksi
1. Buka notebook di Google Colab → **Runtime → Change runtime type → T4 GPU**.
2. **Runtime → Run all**.
3. Saat tombol **Choose Files** muncul, pilih file data task tersebut. File dipindahkan ke `/content/data/`. Kalau file sudah ada di sana, upload dilewati.
4. Semua hasil tersimpan di `/content/outputs/`.
