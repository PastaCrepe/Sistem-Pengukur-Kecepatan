# Kelompok 6 PST Sistem Pengukur kecepatan

Anggota Pengerjaan :
-Akmal Alkhaeri
-Alghifari Syarief
-Athallah Putra Fajar Prijaka
-Muhammad Daffa Faidhullah
-Muhammad Novrian Adillah

Pengenalan :
Sistem memiliki input berupa dua sensor inframerah, dan output berupa buzzer, foto kamera, dan LCD I2C
sistem ini bekerja ketika kendaraan melewati salah satu sensor inframerah, yang menyimpan waktu ketika satu sensor IR menyala, ketika kendaraan melewati IR kedua, waktu ir kedua tercatat dan dikurangi dengan waktu pertama, waktu akan diproses cm/ms menjadi km/h.


Cara Kerja :
Terdapat Dua keadaan pada sistem, yang berbentuk:
  Ketika kecepatan yang dikalkulasi melebihi 50km/jam, maka kelauarnnya akan terteta sebagai berikut:
  -lcd akan menampilkan terlalu cepat
  -buzzer aktif, dan
  -remote shutter akan mengaktifkan kamera dan kamera memotret kendaraan yang terlalu cepat
  Bila kecepatan tidak melebihi 50km/jam, maka sistem menampilkan kecepatan aman di lcd.

VIdeo dapat ditonton dibawah

https://github.com/PastaCrepe/Sistem-Pengukur-Kecepatan/assets/76557101/a4b3b208-0a61-401d-9048-1576b8fc5ad5

Link untuk video dengan kualitas lebih baik dapat ditonton di https://www.youtube.com/watch?v=c0fpd4xZqVQ&t=1s
