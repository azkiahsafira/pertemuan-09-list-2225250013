# Pertemuan 09 - List dan Pengolahan Data Numerik
Nama: Azkiah Safira
NIM: 2225250013
Kelas: 3F

## Tujuan
Mengolah kumpulan data numerik dengan list Python. Melalui latihan dan praktik ini, mahasiswa mempelajari cara membuat list, mengakses elemen menggunakan indeks positif dan negatif, mengambil bagian list menggunakan slicing, serta menambah, mengubah, dan menghapus elemen.

Mahasiswa juga mempelajari penggunaan perulangan untuk menelusuri data, menghitung jumlah dan rata-rata, menentukan nilai minimum dan maksimum, menyaring nilai berdasarkan batas kelulusan, serta menggunakan fungsi untuk mengolah kumpulan data numerik.

## Struktur Program
Program Pertemuan 09 terdiri atas enam file latihan dan satu file praktik yang disusun berdasarkan materi list dan pengolahan data numerik.

Folder `latihan` berisi enam file Python sebagai berikut:
1. `01_dasar_list.py` — mempelajari pembuatan list dan penyimpanan kumpulan data.
2. `02_indeks_dan_slicing.py` — mempelajari akses elemen menggunakan indeks dan slicing.
3. `03_manipulasi_list.py` — mempelajari penambahan, penyisipan, perubahan, dan penghapusan elemen list.
4. `04_agregasi_nilai.py` — mempelajari perhitungan jumlah, banyak data, dan rata-rata nilai.
5. `05_filter_kelulusan.py` — mempelajari penyaringan nilai berdasarkan batas kelulusan.
6. `06_fungsi_statistik.py` — mempelajari penggunaan fungsi untuk mengolah dan menganalisis data numerik.

Folder `praktik` berisi file `analisis_nilai_mahasiswa.py`. Program ini mengolah kumpulan nilai mahasiswa, menampilkan banyak data, menghitung total, rata-rata, nilai minimum dan maksimum, menghitung jumlah mahasiswa yang lulus dan belum lulus, serta menghasilkan list nilai mahasiswa yang lulus.

File `.gitignore` digunakan untuk mengecualikan file sementara dan cache Python yang tidak perlu dimasukkan ke repositori Git.

## Cara Menjalankan
Jalankan terminal pada folder proyek Pertemuan 09. Pastikan Python telah terpasang, kemudian jalankan program praktik menggunakan perintah berikut:

    python3 praktik/analisis_nilai_mahasiswa.py

Untuk menjalankan file latihan, gunakan perintah sesuai nama file yang ingin dijalankan. Contohnya:

    python3 latihan/01_dasar_list.py

Pastikan nama folder dan file sesuai dengan struktur program agar setiap program dapat dijalankan dengan benar.

## Test Case
Pengujian dilakukan untuk memastikan program dapat mengolah data numerik, menghitung statistik, menentukan kelulusan berdasarkan batas nilai 60, dan menangani list kosong tanpa menghasilkan kesalahan.

| No. | Data/Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1 | `[60, 70, 80]` | Rata-rata = 70.00 | Diisi setelah pengujian | Diisi setelah pengujian |
| 2 | `[60, 70, 80]` | Minimum = 60 dan maksimum = 80 | Diisi setelah pengujian | Diisi setelah pengujian |
| 3 | `[60, 70, 80]` | Jumlah mahasiswa lulus = 3 | Diisi setelah pengujian | Diisi setelah pengujian |
| 4 | `[59, 60, 61]` | Jumlah mahasiswa lulus = 2 | Diisi setelah pengujian | Diisi setelah pengujian |
| 5 | `[]` | Fungsi rata-rata menangani list kosong tanpa menghasilkan kesalahan | Diisi setelah pengujian | Diisi setelah pengujian |

Hasil aktual dan status diisi berdasarkan hasil program yang benar-benar dijalankan. Pengujian dinyatakan berhasil apabila hasil aktual sesuai dengan hasil yang diharapkan.

## Refleksi
Saya memahami bahwa list dapat digunakan untuk menyimpan banyak data dalam satu variabel sehingga pengolahan data menjadi lebih terstruktur. Indeks digunakan untuk mengakses elemen tertentu, sedangkan slicing digunakan untuk mengambil bagian dari list.

Saya juga memahami bahwa perulangan dan fungsi dapat digunakan bersama list untuk menghitung statistik dan memeriksa kelulusan mahasiswa. Salah satu kesalahan yang perlu diperhatikan adalah melakukan pembagian dengan jumlah data ketika list kosong. Kesalahan tersebut dapat diatasi dengan memeriksa apakah list memiliki elemen sebelum menghitung rata-rata.