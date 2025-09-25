[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/xY-FshNd)
# Milestones 1

_Milestones 1 ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada Phase 0._

_version: GAIAv2.2_

_update date: 20250304_

---

## Objectives

*Milestone 1* ini dibuat dengan tujuan sebagai berikut :

- Mampu membangun problem statement dengan framework SMART sebagai salah satu langkah dalam Business Understanding.

- Mampu melakukan Data Preparation sebelum melakukan analisa terhadap data tersebut.

- Mampu melakukan perhitungan & analisa dengan menggunakan Descriptive Statistics & Inferential Statistics.

- Mampu membuat dashboard visualisasi yang menjawab problem statement.

- Mampu mengambil kesimpulan dari keseluruhan eksplorasi yang dilakukan.

---

## Problem

Anda adalah seorang Data Analyst yang akan mengerjakan sebuah project untuk menyelesaikan permasalahan seorang client. Client Anda membutuhkan hasil analisa data yang menggunakan statistik dan dashboard visualisasi untuk membantu mereka menyelesaikan masalahnya.

---

## Instructions

### General Instructions
1. Pilihlah sebuah **topik** dan buatlah **problem statement** terhadap topik yang diangkat dengan menggunakan metode SMART. Topik yang dipilih dibebaskan jenisnya.

2. Ketentuan dataset : 
   - Dataset dibebaskan dari asal sumbernya selama sumber tersebut dapat dipertanggungjawabkan dan bukan data dummy atau data buatan (dapat berasal dari Google BigQuery, Kaggle, Badan Pusat Statistik, dll).
   - Format dataset dibebaskan mengenai jenisnya (CSV, Excel, JSON, SQL Query, dll).
   - **NOTE:** Wajib mencantumkan sumber referensi data pada bagian `Identifikasi Masalah`.

3. **Konsultasikan terlebih dahulu dataset yang hendak digunakan ke buddy masing-masing student. Jika disetujui, maka silakan dikerjakan. Jika tidak disetujui, maka cari dataset yang lain dan konsultasikan lagi mengenai dataset yang baru ini.**

4. Saat melakukan konsultasi mengenai dataset yang akan dikerjakan dengan buddy sertakan :
   - URL dataset yang hendak dipakai.
   - Latar belakang.
   - Tujuan yang hendak dicapai dengan adanya report ini. Spesifikkan mengenai problem yang Anda angkat dan kegunaan report ini.
   - User/client yang akan membaca report ini.

5. Sebelum menentukan table, column, atau hal lain dalam dataset yang akan dijadikan analisis dan visualisasi data, lakukan identifikasi dan penjabaran masalah terlebih dahulu agar dapat memudahkan Anda dalam melakukan analisis. Anda dapat menggunakan metode apapun seperti analisis SWOT, Fish bone diagram, 5W+1H, dsb. 
   - Contoh :
      ```
      Problem Statement: Mengetahui Preferensi dan Perilaku Konsumsi Makanan di Area Urban di Indonesia dalam kurun waktu tahun 2021.
      
      Penjabaran masalah dengan metode 5W+1H:
      + Kota mana dengan rata-rata % pengeluaran makan paling besar?
      + Bagaimana perilaku pemilihan makanan berdasarkan harga terhadap social class masyarakat?
      + Apakah tingkat pendidikan sarjana memiliki preferensi memilih makanan-makanan yang sehat?
      + Apakah warga DKI Jakarta masih mengonsumsi makanan tradisional?
      + Usia berapa saja yang masih mengonsumsi makanan tradisional?
      ```
   - Pertanyaan/penjabaran masalah diatas dapat dijawab dengan visualisasi data dan analisis statistik.

6. Jika data yang Anda gunakan berasal dari suatu jenis database tertentu (seperti Google BigQuery), setelah melakukan identifikasi dan penjabaran masalah, tentukan metrik/data apa saja yang diperlukan lalu ambil data yang diperlukan ini dengan menggunakan SQL. `Cantumkan semua query yang Anda buat untuk mengambil semua data yang diperlukan dalam milestone ini`.

7. Penjabaran masalah yang akan dijawab menggunakan visualisasi data dan analisis statistik **HARUS** berisi minimal terdapat `6 penjabaran` masalah dibawah ini :
   - 4 penjabaran untuk `visualisasi data`.
      + Dibebaskan mengenai jenis plot visualisasinya (Bar Plot, Line Chart, dll).
      + Dibebaskan mengenai jenis library visualisasi yang dipakai (`matplotlib`, `pyplot`, `seaborn`, dll). 
      + Anda diwajibkan memberikan insight pada setiap plot visualisasi yang dibuat.
   - 1 penjabaran untuk `statistik deskriptif`.
      + Anda dapat menggunakan perhitungan seperti :
         - *central tendency*
         - *measure of variance*
         - *outlier analysis*
         - dll.
      + Sesuaikan dengan penjabaran masalah yang ditentukan.
   - 1 penjabaran untuk `statistik inferensial`.
      + Anda dapat menggunakan perhitunganseperti :
         - *confidence interval*
         - *statistical significance*
         - *statistical testing*
         - *hypothesis testing: one sample, two sample independent, paired test, ANOVA, chi-square*, 
         - dll.
      + Sesuaikan dengan penjabaran masalah yang ditentukan.

8. Output dari Milestone ini adalah dashboard data visualisasi dan analisis menggunakan `Tableau Public` dan `Python Notebook`.

### Notebook Instructions

1. Isi *notebook* harus mengikuti *outline* di bawah ini:
   1. Introduction
      > Bagian ini harus diisi dengan identitas Student.

   2. Problem Statement and Dataset Description
      > Bagian ini harus mencantumkan **topik permasalahan**, **problem statement**, **latar belakang**, **sumber dataset**, serta **penjabaran masalah** yang ingin dianalisa menggunakan metode statistik dan visualisasi data. Berikan juga penjelasan mengenai deskripsi dataset dan asal dataset yang Anda gunakan.

   3. Data Loading 
      > Bagian ini berisi proses *data loading* dan eksplorasi data sederhana. Cantumkan query SQL masing-masing data yang di-load jika dataset berasal dari Google BigQuery atau server SQL lainnya. Tampilkan juga datanya.

   4. Data Cleaning
      > Bagian ini berisi proses penyiapan data berupa data cleaning sebelum dilakukan eksplorasi data lebih dalam. Proses data cleaning dapat berupa memberi nama baru untuk setiap kolom, mengisi missing values, menghapus kolom yang tidak dipakai, dan lain sebagainya.

   5. Exploration and Analysis
      > Bagian ini berisi proses analisis, penjelasan, perhitungan statistik deskriptif & inferensial, serta pembuatan visualisasi data. Untuk visualisasi data wajib memberikan insight pada setiap plot visualisasinya.

   6. Conclusion
      > Pada bagian terakhir ini, **harus berisi** kesimpulan yang mencerminkan solusi/rekomendasi/jawaban atas permasalahan yang diangkat serta menarik benang merah dari seluruh eksplorasi dan analisa secara singkat, padat, dan jelas.

3. Simpan notebook dengan format `P0M1_<nama-student>.ipynb`, misal `P0M1_fahmi_iman.ipynb`.

### Dashboard Instructions

1. Buatlah dashboard menggunakan `Tableau`. Dashboard dapat berupa 1 halaman atau beberapa halaman.

2. Dashboard yang dibuat terdiri dari 2 bagian yaitu : 
   1. Bagian `Data Visualization` :
      - Minimal terdapat 4 plot visualisasi data yang ditampilkan pada dashboard sesuai dengan yang dibuat pada Notebook.
      - Minimal terdapat 2 interactivity pada dashboard.
      - Pada bagian ini, Anda tidak perlu menulis insight masing-masing plot visualisasinya.

   2. Bagian `Statistical Analysis` :
      - Pada dashboard, buatlah bagian mengenai Statistik Deskriptif dan Statistik Inferensial yang sama dengan yang Anda lakukan pada Python Notebook.
      - Tuliskan juga analisa yang Anda buat mengenai eksplorasi statistik ini.
      - Tuliskan mengenai kesimpulan eksplorasi yang Anda lakukan dan analisa yang Anda buat.

3. Presentasikan dashboard yang telah dibuat pada Phase 1 Week 2 Day 4 AM.

### Markdown File Creation Instructions

1. Pada repository ini terdapat file [description.md](description.md).

2. File ini akan berisi deskripsi dokumentasi repository project yang Anda buat yang berfungsi untuk :
   - Menjelaskan tujuan project, fungsi, dan kegunaannya.
   - Memudahkan orang lain memahami project yang Anda kerjakan sebelum mereka melihat/menggunakannya.
   - Memberikan instruksi tentang bagaimana cara menginstall, membuka, menjalankan, dan memahami project yang Anda buat.
   - dll.

3. Silakan edit file tersebut. Anda dapat menambah, mengurangi, atau mengubah bagian-bagian yang ada didalam file tersebut seperti :
   - Penambahan bagian instalasi program.
   - Penambahan bagian kontak.
   - Penambahan screenshot dashboard/web yang dibuat.
   - dll.

4. Milestone 1 yang Anda buat ini dapat Anda masukkan ke repository GitHub pribadi Anda sebagai portofolio project yang pernah Anda kerjakan. Adapun ketentuannya adalah : 
   1. **Anda hanya berhak memasukkan Milestone 1 ke repository GitHub pribadi Anda setelah Anda berada di Phase 1 Week 3.**
   2. **File `README.md` dan `assignment-rubrics.png` yang ada pada repository tugas dilarang untuk dimasukkan ke repository pribadi.**
   3. Anda dapat memasukkan file Python Notebook beserta dataset ke dalam repository Anda.
      - Rename notebook yang semula berformat `P0M1_<nama-student>.ipynb` menjadi `notebook.ipynb`.
      - Pada file notebook, Anda tidak perlu menuliskan mengenai Batch Hacktiv8.
   4. File [description.md](description.md) :
      - Masukkan ke dalam repository GitHub pribadi Anda.
      - Rename file ini menjadi `README.md`.
      - File ini akan menjadi dokumen utama yang akan menunjukkan deskripsi project yang telah Anda bangun.

5. Catatan penting : 
   1. Anda wajib mengedit file [description.md](description.md) dan menguploadnya ke repository tugas GitHub Classroom.
   2. File ini akan selanjutnya dinilai sebagai salah satu bagian dalam Milestone 1.
   3. Setelah Anda selesai mengerjakan Milestone 1 ini, jangan membuat repository baru di GitHub Anda.
   4. Tunggulah hingga Anda berada di Phase 1 Week 3.

---

## Submission

- Simpan assignment Milestone 1 ini dengan nama :
  + Format penamaan file Python Notebook : `P0M1_<nama-student>.ipynb`. Misal : `P0M1_fahmi_iman.ipynb`.
  + Format penamaan file dataset : `P0M1_<nama-student>_dataset.csv`. Misal : `P0M1_fahmi_iman_dataset.csv`.

- Masukkan juga dataset yang Anda pakai pada project ini.

- Pada Python Notebook (`.ipynb`) yang Anda buat, tambahkan URL Dashboard pada bagian paling atas notebook.

- Tidak adanya URL dashboard pada Python Notebook akan menyebabkan tidak dinilainya dashboard yang Anda buat menggunakan Tableau.

- Push Assignment yang telah Anda buat ke repository tugas GitHub Classroom Anda.

- Contoh bentuk repository :
  ```
  P0-M1/fahmi-iman
  |
  ├── assignment-rubrics.png
  ├── description.md
  ├── P0M1_fahmi_iman.ipynb
  ├── P0M1_fahmi_iman_dataset.jpg
  └── README.md
  ```
---

## Rubrics

![plot](assignment-rubrics.png)

---

```
Total Points : 66

Catatan : Penilaian Milestone 1 juga dapat dipengaruhi oleh aktivitas Student selama Phase 0 berlangsung, baik sesi kelas maupun sesi mentoring dengan buddy-nya masing-masing sehingga terdapat kemungkinan adanya penambahan atau pengurangan nilai diluar rubric yang telah disebutkan diatas.
```

---

## Notes

* **Deadline : Phase 0 Week 4 Day 3 pukul 23:59 WIB.**

* **Keterlambatan pengumpulan tugas mengakibatkan skor Milestone 1 menjadi 0.**
