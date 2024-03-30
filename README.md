# tugas-python5
Data Warehouse Python Part 5 (Mentor Pendamping Galuh Ramaditya)

Nama : Riski Syaputra
Kelas : Data Warehousing

Deskripsi Project

Buatlah repository baru dengan menggunakan akun github pribadi
Upload tugas Python 5: OOP pada respository tersebut
Invite mentor @abdulghif sebagai collaborator
Dokumentasikan homework anda pada file Readme.md
Tugas dikumpulkan dalam bentuk link di LMS.
Detail tugas Python 5:

Buatlah class MarketingDataETL yang memiliki tiga metode: extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv) transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong) store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFramet.
Gunakan inheritance untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL. Tambahkan metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli). Demonstrasi polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.
