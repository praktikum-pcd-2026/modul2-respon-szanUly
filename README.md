# RESPONSI MODUL 2


# Membaca gambar `background.png` dan menampilkan (gambar dan shape) 
<img src="Hasil/hasil0.png" alt="hasil0.png" width="250">

---
# Memecah gambar menjadi tiga channel terpisah: Red, Green, dan Blue
<img src="Hasil/hasil1.png" alt="hasil1.png" width="800">

---
# Menampilkan histogram setiap channel secara individu untuk melihat distribusi intensitas warna dasar
<img src="Hasil/histogram1.png" alt="histogram1.png" width="800">

---
# Membaca gambar target `red_target.png`, `green_target.png`, `blue_target.png` dan menampilkannya hasil grayscale
<img src="Hasil/hasil2.png" alt="hasil2.png" width="800">

---
# Menampilkan histogram setiap channel gambar target untuk melihat distribusi intensitas warna dasar
<img src="Hasil/histogram2.png" alt="histogram2.png" width="800">

---
# Melakukan spesifikasi pada setiap channel pada gambar `background.png` terhadap gambar target dengan ketentuan channel `red` dengan `red_target.png`, `green` dengan `green_target.png`, `blue` dengan `blue_target.png` . Serta menampilkan gambar hasil spesifikasi dan histogramnya
<img src="Hasil/hasil3.png" alt="hasil3.png" width="800">

---

<img src="Hasil/histogram3.png" alt="histogram3.png" width="800">
---

# Menggabungkan semua channel hasil spesifikasi menjadi satu gambar utuh dan menampilkan gambar awal `background.png` dan hasil spesifikasi. Lakukan analisis terhadap pengaruh spesifikasi

<img src="Hasil/hasil4.png" alt="hasil4.png" width="800">

---

# Membaca dan menampilkan gambar `foreground.png` (gambar dan shape).

<img src="Hasil/hasil5.png" alt="hasil5.png" width="250">

---

# Sebelum melakukan penjumlahan perhatikan shape dari gambar `hasil spesifikasi` dan  `foreground.png`. Lakukan salah satu operasi Transformasi Geometri pada gambar `foreground.png` agar memiliki shape yang sama dengan gambar `hasil spesifikasi`. 
note: lakukan operasi transformasi geometri pada tiap channel `foreground.png` dan gabungkan semua channel. `tanpa menggunakan fungsi resize`

<img src="Hasil/hasil6.png" alt="hasil6.png" width="800">

---

# Setelah shapenya sama gambar hasil spesifikasi dan gambar foreground (hasil operasi transformasi geometri) kemudian digabungkan menggunakan `fungsi penjumlahan` dengan logika kondisional:
- Jika piksel pada foreground memiliki nilai intensitas (bukan hitam), maka piksel tersebut yang digunakan.  
- Jika tidak, maka piksel diambil dari citra background hasil spesifikasi.


Hasilnya adalah sebuah citra komposit di mana objek foreground berada di atas latar belakang yang kontrasnya telah disesuaikan.

<img src="Hasil/hasil7.png" alt="hasil7.png" width="250">

---
# Tahap akhir melibatkan pembagian citra komposit menjadi tiga bagian secara vertikal: bagian kiri, tengah, dan kanan.

<img src="Hasil/hasil8.png" alt="hasil8.png" width="250">

---

# Tampilkan histogram untuk gambar bagian tengah saja

<img src="Hasil/histogram4.png" alt="histogram4.png" width="250">

---

# Khusus pada bagian tengah, lakukan proses Ekualisasi Histogram pada tiap channel untuk meratakan distribusi intensitas agar kontrasnya meningkat secara otomatis. Tampilkan hasil gambar dan histogramnya. Lakukan analisis atas pengaruh proses ekualisasi pada gambar

<img src="Hasil/hasil9.png" alt="hasil9.png" width="250">

<img src="Hasil/histogram5.png" alt="histogram3.png" width="250">

---

# Setelah itu, ketiga bagian tersebut disatukan kembali menjadi satu citra utuh (`bagian kiri`, `bagian tengah hasil ekualisasi`, `bagian kanan`).

<img src="Hasil/hasil10.png" alt="hasil10.png" width="250">

---
# Berikan kesimpulan dari semua proses yang dilakukan