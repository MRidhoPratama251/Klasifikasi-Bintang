# Klasifikasi-Bintang
---

<p>Proyek ini bertujuan untuk memenuhi tugas akhir dari KKL Master Class Data Science bersama BISA AI Academy. Berisi file yang memuat model untuk mengklasifikan kategori bintang kedalam jenis bintang kurcaci [0] atau bintang raksasa [1]. Dataset yang memberikan 5 fitur untuk mengklasifikan bintang ke dalam dua kategori dengan penjelasan tiap fitur sebagai berikut :<p>

1. Vmag (Magnitudo Visual atau Magnitudo Semu):
   * Definisi: Vmag adalah besaran yang menunjukkan kecerlangan suatu objek seperti bintang yang diamati dari Bumi. Magnitudo semu ini dipengaruhi oleh jarak antara pengamat dan objek, sehingga bintang yang 
       sama akan terlihat memiliki kecerlangan berbeda jika dilihat dari jarak yang berbeda.
   * Penggunaan: Vmag sering digunakan dalam observasi astronomi untuk memberikan perkiraan awal tentang seberapa terang sebuah bintang terlihat dari Bumi.<p>
   
2. Plx (Paralaks) dan e_Plx (Error dalam Paralaks):
   * Definisi: 
   Plx adalah singkatan dari paralaks, yang merupakan sudut kecil yang diukur ketika bintang dilihat dari dua posisi berbeda dalam orbit Bumi. Paralaks digunakan untuk menghitung jarak ke bintang. Satuan yang 
   digunakan adalah parsec (pc), dengan $1pc=3.086\times10^{16} m$.
   e_Plx: Ini adalah ketidakpastian atau galat dalam pengukuran paralaks, yang menunjukkan seberapa akurat pengukuran jarak tersebut.
   * Penggunaan: Paralaks adalah metode utama untuk mengukur jarak bintang yang relatif dekat dengan Bumi.

3. B-V (Indeks Warna):
   * Definisi: B-V adalah indeks warna yang dihitung dari perbedaan antara magnitudo bintang dalam filter biru (B) dan visual (V). Nilai ini berhubungan erat dengan suhu permukaan bintang; bintang yang lebih 
     panas (lebih biru) memiliki nilai B-V yang lebih rendah.
   * Penggunaan: Indeks B-V digunakan untuk mengklasifikasikan bintang berdasarkan suhu dan warna, serta untuk memperkirakan suhu permukaan bintang.

4. Amag (Magnitudo Absolut):
   * Definisi: Amag adalah magnitudo absolut, yang menunjukkan kecerlangan intrinsik dari bintang, yaitu kecerlangan yang akan terlihat jika bintang berada pada jarak standar 10 parsec dari Bumi. Tidak seperti 
     magnitudo semu, Amag tidak tergantung pada jarak pengamat.
   * Penggunaan: Magnitudo absolut digunakan untuk membandingkan kecerlangan nyata dari bintang-bintang, terlepas dari jaraknya.
   
5. SpType (Spektral Tipe):
   * Definisi: SpType menunjukkan tipe spektral atau kelas dari bintang, berdasarkan sistem klasifikasi Morgan-Keenan (MK). Huruf OBAFGKM menunjukkan klasifikasi berdasarkan warna dan suhu, dengan O yang paling 
     panas (biru) dan M yang paling dingin (merah). Angka Romawi menunjukkan kelas luminositas bintang, dari supergiant (I) hingga dwarf (V).
   * Penggunaan: Tipe spektral digunakan untuk memahami karakteristik fisik bintang, seperti suhu, ukuran, dan evolusi.

