# Pertemuan 1 – Dasar Algoritma untuk Machine Learning

## Identitas
Nama  : Muhammad Rizal Haris  
NIM   : 105841103223  
Kelas : 5A Applied Machine Learning  
Tanggal : 28 Februari 2026  

---

## Tujuan Praktikum

Praktikum ini bertujuan untuk melatih penggunaan beberapa library Python yang umum digunakan dalam machine learning, yaitu NumPy, Pandas, dan Matplotlib. Selain itu, praktikum ini membantu memahami cara membaca dataset serta mengenali struktur data sebelum dilakukan analisis lebih lanjut.

---

## Library yang Digunakan

- NumPy → untuk pengolahan data numerik dan operasi matriks  
- Pandas → untuk pengelolaan data dalam bentuk tabel (DataFrame)  
- Matplotlib → untuk membuat visualisasi data  

---

## Penjelasan Kegiatan

### 1. NumPy
- Membuat 20 angka acak dengan rentang 0–100.  
- Menghitung statistik dasar seperti mean, median, standar deviasi, nilai minimum, dan maksimum.  
- Mengubah array satu dimensi menjadi matriks 4x5 menggunakan reshape.  
- Melihat dimensi matriks dengan shape dan melakukan transpose untuk menukar baris dan kolom.

### 2. Pandas
- Membuat daftar nama mahasiswa secara otomatis.  
- Menghasilkan nilai acak dengan rentang 50–100.  
- Menyusun data ke dalam DataFrame dengan kolom Nama dan Nilai.  
- Menambahkan kolom Status (Lulus / Tidak Lulus).  
- Menghitung rata-rata kelas dan jumlah mahasiswa yang lulus.  
- Menampilkan tiga nilai tertinggi menggunakan nlargest().

### 3. Visualisasi
- Membuat bar chart untuk menampilkan nilai setiap mahasiswa.  
- Membuat histogram untuk melihat distribusi nilai.  
- Menyimpan grafik dalam format PNG.

### 4. Dataset Wine
- Memuat dataset menggunakan load_wine(as_frame=True).  
- Melihat ukuran dataset dengan shape.  
- Menampilkan lima baris pertama dengan head().  
- Melihat ringkasan statistik menggunakan describe().  
- Dataset terdiri dari 178 data dan termasuk klasifikasi multikelas.

---

## Kesimpulan

Dari praktikum ini dapat dipahami cara dasar menggunakan NumPy, Pandas, dan Matplotlib dalam pengolahan serta visualisasi data. Selain itu, praktikum ini memberikan pemahaman awal tentang struktur dataset machine learning sebelum digunakan dalam proses pemodelan.
