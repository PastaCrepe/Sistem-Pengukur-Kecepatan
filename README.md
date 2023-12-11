# Disini adalah repositori mengenai Tugas Kelompok 6 PST dengan judul Sistem Pengukur kecepatan

Link dapat dilihat di https://youtu.be/c0fpd4xZqVQ

Sistem memiliki input berupa dua sensor inframerah, dan output berupa buzzer, foto kamera, dan LCD I2C
sistem ini bekerja ketika kendaraan melewati salah satu sensor inframerah, yang menyimpan waktu ketika satu sensor IR menyala, ketika kendaraan melewati IR kedua, waktu ir kedua tercatat dan dikurangi dengan waktu pertama, waktu akan diproses cm/ms menjadi km/h.

ketika kecepatan yang dikalkulasi melebihi 50km/jam, maka kelauarnnya akan terteta sebagai berikut:
-lcd akan menampilkan terlalu cepat
-buzzer aktif, dan
-remote shutter akan mengaktifkan kamera dan kamera memotret kendaraan yang terlalu cepat
