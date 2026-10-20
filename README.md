# Ujian Tengah Semester (UTS) Graf Sains Data

## Identitas Mahasiswa

- **Nama:** Cintiya Agustin Nareswari
- **NIM:** 24031554218
- **Kelas:** 2024A
- **Mata Kuliah:** Graf Sains Data

## Deskripsi

Repository ini berisi pengerjaan Ujian Tengah Semester (UTS) mata kuliah Graf Sains Data menggunakan dataset RetailRocket. Pengerjaan meliputi pengolahan data, analisis, serta penerapan metode rekomendasi menggunakan Python sesuai dengan instruksi soal yang diberikan oleh dosen.

## Tujuan

1. Mengolah dan menganalisis data interaksi pengguna dan item.
2. Menerapkan metode K-Nearest Neighbors (KNN) untuk memberikan rekomendasi item.
3. Menentukan tiga item rekomendasi berdasarkan hasil perhitungan KNN.
4. Mengevaluasi hasil rekomendasi menggunakan Hit@5 dan NDCG@5.

## Dataset

Dataset yang digunakan adalah RetailRocket E-commerce Dataset yang disediakan oleh dosen.

Dataset untuk keperluan pengerjaan dapat diakses melalui tautan berikut:

[Google Drive — Dataset Training dan Testing](https://drive.google.com/drive/folders/1UkhfL5t0m-UTRVieCY6BikOxuZKvE9ob)

## Periode Data

Data dibagi menjadi dua periode sebagai berikut:

- **P1 (Training):** 3 Mei – 17 Agustus 2015
- **P2 (Testing):** 18 Agustus – 18 September 2015

## Metode dan Tahapan Pengerjaan

1. **Persiapan data:** membaca dan mengolah dataset menggunakan Python.
2. **Wrangling dan EDA:** melakukan pengolahan serta eksplorasi data.
3. **Pembentukan matriks User-Item:** merepresentasikan interaksi pengguna dengan item.
4. **Rekomendasi KNN:** menghitung kemiripan antar-User menggunakan cosine similarity dan menentukan lima tetangga terdekat dengan \(k=5\).
5. **Evaluasi rekomendasi:** menghitung Hit@5 dan NDCG@5 untuk menilai hasil rekomendasi.

## Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Neo4j

## Struktur Repository

```text
UTS-Graf-Sains-Data
├── README.md
└── uts_graf_RetailRocket.ipynb
```

Dataset training dan testing disimpan di Google Drive karena ukuran file dapat cukup besar. Tautannya tersedia pada bagian Dataset.

## Cara Menjalankan

1. Siapkan Python dan environment yang digunakan untuk pengerjaan.
2. Unduh dataset training dan testing dari tautan Google Drive.
3. Letakkan kedua file pada folder `data` sesuai dengan lokasi yang digunakan dalam notebook.
4. Instal dependensi yang diperlukan.
5. Buka `uts_graf_RetailRocket.ipynb` menggunakan Jupyter Notebook.
6. Jalankan setiap cell secara berurutan.

## Hasil Pengerjaan

Hasil pengerjaan mencakup pengolahan dan eksplorasi data RetailRocket serta penerapan metode KNN untuk rekomendasi item. Evaluasi rekomendasi dilakukan menggunakan Hit@5 dan NDCG@5. Kode, hasil eksekusi, visualisasi, dan interpretasi disajikan dalam notebook.

## Penutup

Repository ini disusun sebagai dokumentasi pengerjaan Ujian Tengah Semester mata kuliah Graf Sains Data berdasarkan instruksi yang diberikan oleh dosen.
