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

<p align="center"><img src="https://drive.google.com/uc?export=view&id=1K98VSxSRNRVhnuq90ksc0Jw3-Qyh5KU1"></p>

<b>Kelebihan Topologi Bus</b>
Arsitektur IEEE 80.3 digunakan dalam topologi ini.
Relatif mudah dipasang dan digunakan untuk jaringan kecil.
Ini membutuhkan lebih sedikit media daripada topologi lainnya.
Kegagalan satu node tidak mempengaruhi fungsi jaringan.
Biaya rendah.
Ekspansi lebih mudah. Sebuah node baru dapat dengan mudah ditambahkan dengan menggunakan konektor.

<b>Kekurangan Topologi Bus</b>
Seluruh jaringan gagal jika ada putusnya kabel utama.
Sulit dikonfigurasi
Sulit untuk memecahkan masalah karena semuanya terjadi dalam satu segmen media.
Lalu lintas jaringan yang lebih tinggi memperlambat kecepatan bus. Hanya satu perangkat yang mentransmisikan pada satu waktu, perangkat lain menunggu giliran.
Masalah tabrakan.

### Topologi Ring
Topologi ring adalah loop melingkar dari link point-to-point. Setiap perangkat terhubung langsung ke ring atau tidak langsung melalui perangkat antarmuka atau kabel drop. Tidak seperti topologi bus, ia tidak memiliki terminator di ujung kabelnya. Pada topologi ini data berpindah dari satu node ke node lainnya. Data bergerak dalam satu arah saja. Setiap workstation memeriksa pesan untuk alamat tujuan yang cocok. Jika alamat tidak cocok dengan node, cukup buat ulang pesan dan kirimkan dalam perjalanan. Jika alamat cocok, node menerima pesan dan mengirim balasan ke pengirim.

<p align="center"><img src="https://drive.google.com/uc?export=view&id=1Yob2DjmYlCwxA0hSGpfyIYcVHcCWwPe6"></p>

<b>Keuntungan Topologi Ring</b>
Kemudahan instalasi.
Biaya rendah karena hanya satu kabel yang digunakan.
Sebuah fitur internal khusus yang disebut beaconing memungkinkan workstation bermasalah untuk mengidentifikasi diri mereka sendiri dengan cepat.
Tidak ada tabrakan.
Paket data berjalan dengan kecepatan lebih tinggi.

<b>Kekurangan Topologi Ring</b>
Jaringan cincin membutuhkan lebih banyak media fisik daripada jaringan bus.
Kegagalan media pada loop searah atau tunggal menyebabkan kegagalan jaringan total.
Putusnya cincin kabel menyebabkan seluruh jaringan terputus.
Sulit untuk mengkonfigurasi ulang topologi ring.

### Topologi Mesh
Dalam topologi Mesh, setiap node terhubung ke setiap node lain dalam jaringan. Ada dua jenis, topologi Mesh penuh, dan topologi Mesh parsial. Dalam topologi Mesh penuh, semua node (workstation atau perangkat lain) terhubung langsung satu sama lain. Dalam topologi Mesh parsial, beberapa node terhubung ke yang lain, tetapi beberapa node hanya terhubung ke node lain yang dengannya mereka bertukar data paling banyak.

<p align="center"><img src="https://drive.google.com/uc?export=view&id=1My3R-JTNtWgtG1COGOzJ-HPi1vBLnKLc"></p>

<b>Keuntungan Topologi Mesh</b>
Jika satu tautan gagal, seluruh sistem terus bekerja.
Tidak ada masalah kemacetan lalu lintas karena tautan khusus sedang digunakan.
Tautan khusus memastikan transmisi lebih cepat tanpa penundaan.
Tautan khusus juga memastikan privasi dan keamanan data.

<b>Kekurangan Topologi Mesh</b>
Menghubungkan setiap perangkat ke setiap perangkat lain dalam jaringan membuat instalasi dan konfigurasi ulang menjadi sulit.
Biaya pemasangan kabel tinggi.

### Topologi Hybrid
Topologi hybrid adalah jenis topologi yang terdiri dari satu atau lebih interkoneksi dari dua atau lebih jaringan yang didasarkan pada topologi fisik yang berbeda. Ketika dua hub dari topologi yang berbeda bergabung sehingga perangkat yang terpasang padanya dapat berkomunikasi, itu disebut jaringan Star-Bus. Ketika dua atau lebih topologi star dihubungkan bersama menggunakan hub khusus yang disebut MAU (Multi-utilization Access Unit). Hal ini dikenal sebagai topologi star-ring.

<p align="center"><img src="https://drive.google.com/uc?export=view&id=19QhgziJwbaa4kkpTsYZochs9uTdlfjLq"></p>

