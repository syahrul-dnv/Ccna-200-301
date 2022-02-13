# Mengenal Topologi Jaringan

Ketika kita mendengar atau membaca kata <b>topologi</b>, kita pasti bertanya pada diri kita sendiri apa itu topologi? Jadi inilah jawabannya. Sebuah topologi atau topologi jaringan mengacu pada cara di mana kabel dijalankan ke workstation individu (komputer host, kelompok komputer) atau jaringan. Ini menggambarkan tata letak sebenarnya dari perangkat keras jaringan komputer. Dua atau lebih perangkat terhubung ke tautan, dua atau lebih tautan membentuk topologi. Selanjutnya, kita akan membahas <b>topologi dalam jaringan</b>.

Ada dua jenis topologi jaringan .

1. topologi fisik 
2. topologi logis

<b>Topologi fisik</b>: Topologi fisik jaringan mengacu pada konfigurasi kabel, komputer, dan periferal lainnya.<br>
<b>Topologi logis</b>: Topologi logis adalah metode yang digunakan untuk melewatkan informasi antar stasiun kerja.

## Jenis Topologi Jaringan
<ul>
  <li>Topologi Star Topologi</li>
  <li>Bus Topologi</li>
  <li>Ring Topologi</li>
  <li>Mesh Topologi</li>
<li>Hybrid
</ul>

### Topologi Star
Topologi star menggunakan perangkat terpusat (hub, switch) yang menghubungkan semua komputer dengan bantuan kabel twisted pair. Setiap perangkat jaringan memiliki tautan point-to-point khusus ke perangkat terpusat. Tidak ada hubungan langsung antara komputer ini dan komputer dapat berkomunikasi melalui perangkat terpusat saja. Strategi ini mencegah tabrakan yang merepotkan dan menjaga jalur komunikasi tetap terbuka dan bebas dari lalu lintas. Topologi star adalah salah satu topologi terbaik dan paling banyak digunakan dalam jaringan .

Contoh Topologi Star: jika satu komputer A ingin mengirim data ke komputer lain B, komputer A mengirimkan data ke perangkat terpusat dan perangkat ini kemudian mengirimkan data ke komputer B.

<p align="center"><img src="https://drive.google.com/uc?export=view&id=1XqdIDyd9umPjbW7gEdjdeEXzG7LvsJjp"></p>

<b>Kelebihan Topologi Star</b>
Saat ini topologi star digunakan.
Manajemen jaringan jauh lebih mudah.
Kemudahan pemasangan kabel.
Mudah untuk mendeteksi kesalahan dan menghapus bagian.
Keandalan jaringan tinggi.
Jika satu komputer atau tautan gagal, seluruh sistem tidak akan runtuh. Hanya tautan atau komputer itu yang terpengaruh.

<b>Kekurangan Topologi Star</b>
Jika perangkat terpusat gagal, seluruh sistem akan runtuh.
Biaya pemasangan kabel lebih mahal karena setiap node terhubung satu per satu ke perangkat terpusat.
Memerlukan lebih banyak kabel daripada kebanyakan topologi.
Cukup sulit untuk dipasang.

### Topologi Bus
Tapi topologi adalah jenis kedua dari topologi jaringan. Dalam topologi bus, semua workstation terhubung ke segmen kabel yang sama. Kabel diakhiri di setiap ujungnya. Tanpa terminator, sinyal listrik akan mencapai ujung kabel tembaga dan memantul kembali, menyebabkan kesalahan pada jaringan. Data berjalan di kedua arah hingga diambil oleh NIC workstation atau server. Jika pesan tidak terjawab atau tidak dikenali, pesan tersebut mencapai ujung kabel dan menghilang di terminator. Konektor digunakan dalam topologi bus.































