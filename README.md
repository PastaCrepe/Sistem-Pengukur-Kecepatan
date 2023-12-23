# Kelompok 6 PST Sistem Pengukur kecepatan

Link demo sistem dapat dilihat di https://youtu.be/c0fpd4xZqVQ

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

Anggota pengerjaan :
-Akamal Alkhaeri
-Alghifari Syarief
-Athallah Putra Fajar Prijaka
-Muhammad Daffa Faidhullah
-Muhammad Novrian Adillah

