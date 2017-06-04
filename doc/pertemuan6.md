**BREADTH-FIRST SEARCH (BFS)**

**Latar Belakang**

Dalam pertemuan kemarin pada mata kuliah Kecerdasan Buatan dijelaskan mengenai algoritma pencarian. Algoritma pencarian merupakan algoritma yang menerima beberapa masalah dan menghasilkan suatu solusi terhadap masalah tersebut. Salah satu dari algoritma pencarian tersebut adalah BFS (Breadth-First Search). Pada resume kali ini akan dibahas tentang definisi, kelebihan dan kekurangan, dan cara kerja BFS sendiri.

**Pembahasan**

1. **Definisi**

Algoritma BFS atau pencarian melebar merupakan sebuah algoritma yang akan melakukan pencarian graf, dimulai dari node pangkal atau awal kemudian menjelajahi semua node yang terdekat, bahkan node yang tidak terlihat juga akan dijelajahi oleh algoritma BFS.

Alagoritma BFS juga bisa disebut sebuah metode untuk memeriksa semua node yang ada di sebuah graf secara berurut menggunakan semua solusi sistematis yang ada dan bertujuan untuk memperluas graf tersebut.

2. **Kelebihan**

- Algoritma jarang sekali atau bahkan tidak pernah menemui jalan buntu
- Terjaminnya ditemukan sebuah solusi
- Dan solusi yang ditemukan merupakan solusi yang terbaik

3. **Kekurangan**

- Memakan kapasitas memori yang cukup besar
- Dan juga membutuhkan waktu yang cukup lama.

4. **Cara Kerja Algoritma BFS**

Dalam algoritma BFS, simpul anak yang telah dikunjungi disimpan dalam suatu antrian. Antrian ini digunakan untuk mengacu simpul-simpul yang bertetangga dengannya yang akan dikunjungi kemudian sesuai urutan pengantrian.Untuk memperjelas cara kerja algoritma BFS beserta antrian yang digunakannya, berikut langkah-langkah algoritma BFS:

-
  - Masukkan simpul ujung (akar) ke dalam antrian.
  - Ambil simpul dari awal antrian, lalu cek apakah simpul merupakan solusi.
  - Jika simpul merupakan solusi, pencarian selesai dan hasil dikembalikan.
  - Jika simpul bukan solusi, masukkan seluruh simpul yang bertetangga dengan simpul tersebut (simpul anak) ke dalam antrian.
  - Jika antrian kosong dan setiap simpul sudah dicek, pencarian selesai dan mengembalikan hasil solusi tidak ditemukan.
  - Ulangi pencarian dari langkah kedua.

**Penutup**

1. **Kesimpulan :** Algoritma BFS adalah algoritma yang melakukan pencarian secara melebar dengan cara mengunjungi node. Baik node yang berdekatan maupun node yang tak terlihat, untuk mencapai tujuan yaitu ditemukannya solusi.
2. **Saran :** Sebaiknya mencari referensi lain yang lebih lengkap di media atau situs lainnya.

URL Github: Kecerdasan Buatan

- Nama              : Rima Rizky Lestari
- NPM                : 1144118
- Kelas                : 3C
- Prodi                : D4 Teknik Informatika
- Kampus           : Politeknik Pos Indonesia

Referensi: http://muhamadmasruri.blogspot.co.id/2013/04/pencarian-melebar-pertama-breadth-first.html

Plagiarisme:

1. Smallseotools : https://drive.google.com/open?id=0B5Iinqg_puu9MEdUTW1SeXZ4Y1E

2. Searchenginereports : https://drive.google.com/open?id=0B5Iinqg_puu9VHlZWE9JOE1tWDg

