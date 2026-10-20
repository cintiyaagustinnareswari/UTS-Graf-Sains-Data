# Ujian Tengah Semester (UTS) Graf Sains Data

## Identitas Mahasiswa

- **Nama:** Cintiya Agustin Nareswari
- **NIM:** 24031554218
- **Kelas:** 2024A
- **Mata Kuliah:** Graf Sains Data

## Deskripsi

Repository ini berisi pengerjaan Ujian Tengah Semester (UTS) mata kuliah Graf Sains Data. Pengerjaan menggunakan dataset RetailRocket yang telah disediakan oleh dosen. Pengolahan dan analisis data dilakukan menggunakan Python sesuai dengan instruksi soal UTS.

## Tujuan

1. Mengolah dan menganalisis data interaksi antara pengguna (*user*) dan item.
2. Menerapkan metode K-Nearest Neighbors (KNN) untuk memberikan rekomendasi item.
3. Menentukan tiga item rekomendasi berdasarkan hasil perhitungan KNN.
4. Mengevaluasi hasil rekomendasi menggunakan Hit@5 dan NDCG@5.

## Dataset

Dataset yang digunakan adalah RetailRocket E-commerce Dataset yang disediakan oleh dosen. Dataset ini berisi data interaksi pengguna dengan item pada platform e-commerce, seperti aktivitas melihat item, menambahkan item ke keranjang, dan melakukan transaksi.

Untuk pengerjaan rekomendasi, data dibagi menjadi data training dan data testing. Data training digunakan untuk membangun sistem rekomendasi, sedangkan data testing digunakan untuk mengevaluasi hasil rekomendasi.

## Metode dan Tahapan Pengerjaan

1. **Persiapan data:** membaca dan mengolah data agar dapat digunakan dalam analisis.
2. **Pembentukan matriks User-Item:** merepresentasikan interaksi pengguna dengan item.
3. **Perhitungan kemiripan:** menggunakan cosine similarity untuk mengukur kemiripan antar-User.
4. **Rekomendasi KNN:** memilih lima tetangga terdekat (\(k=5\)) dan menentukan item rekomendasi berdasarkan skor tertinggi.
5. **Evaluasi:** menghitung Hit@5 dan NDCG@5 untuk menilai hasil rekomendasi.

## Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Scikit-learn

## Struktur Repository

```text
UTS-Graf-Sains-Data-RetailRocket/
├── README.md
├── UTS_Analytics_KNN.ipynb
└── data/
    ├── training.csv
    └── testing.csv
```

## Cara Menjalankan

1. Siapkan Python dan Jupyter Notebook.
2. Letakkan file dataset pada folder yang sesuai dengan lokasi yang digunakan dalam notebook.
3. Instal library yang diperlukan:

   ```bash
   pip install pandas numpy scipy scikit-learn jupyter
   ```

4. Buka notebook dan jalankan setiap cell secara berurutan.

## Hasil Pengerjaan

Hasil pengerjaan meliputi implementasi rekomendasi item menggunakan KNN, tiga item rekomendasi teratas, serta evaluasi menggunakan Hit@5 dan NDCG@5. Kode, hasil eksekusi, dan interpretasi disajikan dalam notebook.

## Penutup

Repository ini disusun sebagai dokumentasi pengerjaan Ujian Tengah Semester mata kuliah Graf Sains Data berdasarkan instruksi soal yang diberikan oleh dosen.
