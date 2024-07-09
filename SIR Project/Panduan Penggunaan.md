# Cara Menjalankan Program: Panduan Pengguna

Model ini mensimulasikan penyebaran COVID-19 di Provinsi Lampung berdasarkan data pada 1 April 2023. Terdapat dua kasus yang disimulasikan:

* Kasus 1: Tanpa Isolasi Mandiri
Kasus ini mengasumsikan tidak adanya upaya khusus untuk mengurangi penularan, seperti isolasi mandiri.

* Kasus 2: Dengan Isolasi Mandiri
Kasus ini memperhitungkan adanya upaya isolasi mandiri (social distancing) yang dapat mengurangi tingkat penularan.

## Panduan Penggunaan:
1. Eksekusi Program:
  * Pastikan Python dan library yang dibutuhkan (numpy, scipy.integrate, matplotlib) terinstal.
  * Jalankan kode program untuk kedua kasus (Kasus 1 dan Kasus 2).

2. Interpretasi Hasil:
  * Program akan menghasilkan grafik yang menampilkan:
    * Model Penyebaran COVID-19: Menunjukkan tren keseluruhan populasi terinfeksi.
    * Susceptible (Rentan Terinfeksi): Populasi yang belum terinfeksi.
    * Infected (Terinfeksi): Populasi yang sedang terinfeksi.
    * Recovered (Sembuh): Populasi yang sudah sembuh.
  * Perhatikan perbedaan pola grafik pada kedua kasus untuk melihat pengaruh isolasi mandiri.

## Parameter:
* N: Total populasi (dapat disesuaikan sesuai data wilayah).
* I0: Populasi awal yang terinfeksi (kasus awal).
* R0: Populasi awal yang sudah sembuh.
* beta: Tingkat penularan penyakit.
* gamma: Tingkat kesembuhan.
* rho (hanya Kasus 2): Efektivitas isolasi mandiri dalam mengurangi penularan (nilai antara 0 dan 1).

## Sumber Data:
https://dinkes.lampungprov.go.id/infografis-update-situasi-covid-19-provinsi-lampung-1-april-2023-pukul-15-00/

## Disclaimer:
Hasil simulasi ini adalah perkiraan berdasarkan model SIR dan data yang ada. Penyebaran penyakit sebenarnya dipengaruhi oleh berbagai faktor lain yang tidak tercakup dalam model ini.
