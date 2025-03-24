# Tugas-Oak
Soal

1.Jelaskan Struktur Antar Hubungan dan Beri Contohnya?

2.Bila terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan kinerja, sebutkan penyebabnya?:

3.Umumnya perangkat berprioritas paling rendah memiliki waktu tunggu rata-rata yang paling singkat. Dengan dasar ini biasanya CPU diberi perioritas tertinggi pada SBI. Sebutkan alasan perangkat berprioritas 16 memiliki waktu tunggu rata-rata paling rendah? Dibawah kondisi seperti apa keadaan diatas tidak berlaku?


Jawab:
1. Sistem bus adalah mekanisme yang digunakan untuk menghubungkan berbagai komponen dalam komputer agar dapat bekerja secara bersamaan. Seperti yang kita tahu, komputer terdiri dari banyak komponen yang harus saling berkomunikasi, dan sistem bus berperan sebagai jalur utama untuk transfer data antar komponen.

Beberapa contoh jenis bus dalam komputer:

a. Bus AGP (Accelerated Graphics Port) → Digunakan khusus untuk menghubungkan kartu grafis ke motherboard, sehingga meningkatkan kinerja tampilan grafis.

b. Bus SCSI (Small Computer System Interface) → Berfungsi untuk menghubungkan perangkat penyimpanan seperti hard disk dan perangkat lain yang membutuhkan kecepatan transfer data tinggi.

c. Bus PCI (Peripheral Component Interconnect) → Memungkinkan perangkat tambahan seperti kartu suara, kartu jaringan, dan perangkat ekspansi lainnya untuk terhubung ke motherboard.

2. Jika terlalu banyak perangkat yang terhubung ke bus, kinerjanya akan menurun karena bus harus mengelola lebih banyak permintaan akses secara bersamaan. Hal ini dapat menyebabkan keterlambatan dalam pengiriman data dan membuat sistem bekerja lebih lambat. Beberapa faktor utama yang menyebabkan penurunan kinerja tersebut antara lain:

a. Waktu koordinasi yang semakin lama → Semakin banyak perangkat yang ingin menggunakan bus, semakin lama proses penjadwalan aksesnya.

b. Antrian akses yang menumpuk → Banyaknya perangkat yang harus bergantian menggunakan bus menyebabkan waktu tunggu yang lebih panjang.

c. Keterbatasan kapasitas bus → Jika jumlah data yang dikirim melebihi kapasitas bus, maka kecepatan transfer akan berkurang dan dapat menyebabkan kemacetan data.

3. Dalam sistem bus, perangkat dengan prioritas lebih rendah sering kali memiliki waktu tunggu rata-rata lebih singkat. Hal ini terjadi karena sistem bus umumnya menerapkan metode penjadwalan yang membagi akses secara merata, sehingga perangkat berprioritas rendah bisa mendapatkan giliran lebih cepat jika perangkat lain sedang sibuk atau menggunakan bus dalam waktu lama. Itulah sebabnya CPU diberikan prioritas tertinggi agar dapat mengelola tugas-tugas utama tanpa harus menunggu giliran.
Namun, dalam beberapa kondisi, aturan ini tidak selalu berlaku. Jika sistem menerapkan strict priority scheduling, perangkat dengan prioritas tinggi akan selalu didahulukan, membuat perangkat berprioritas lebih rendah harus menunggu lebih lama. Selain itu, jika terjadi kepadatan lalu lintas data di bus (bus contention), perangkat dengan prioritas rendah akan kesulitan mendapatkan akses. Faktor lain yang dapat memengaruhi adalah jika perangkat berprioritas tinggi menggunakan bus dalam durasi panjang secara terus-menerus, sehingga perangkat dengan prioritas lebih rendah jarang mendapat kesempatan untuk mengakses bus.




