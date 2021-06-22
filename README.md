# jnt
Project UAS BDL - JNT

1. Download XAMPP https://www.apachefriends.org/index.html
2. Instal XAMPP
3. download zip di github https://github.com/prajnapurnanggara/jnt/
4. eksrak jnt-main.rar, lalu ekstrak jnt.rar ke C:\xampp\htdocs
5. buka XAMPP lalu start pada apache dan sql
6. buka browser klik link, http://localhost/phpmyadmin/
7. buat databse baru dengan nama jnt
8. pilih import pada database jnt
9. kembali ke C:\xampp\htdocs\jnt pilih file jnt.sql
10. login sebagai admin http://localhost/jnt/projects/admin/login.php
11. id admin : admin
12. password : 123
13. login sebagai cs http://localhost/jnt/projects/cs/login.php
14. id cs : CS001
15. password : 123
16. login sebagai kurir http://localhost/jnt/projects/kurir/login.php
17. id kurir : KR001
18. password : 123
19. login sebagai pelanggan http://localhost/jnt/projects/pelanggan/login.php
20. id pelanggan : PL001
21. password : 123


NOTE :
1. Query user dengan pengiriman terbanyak bisa di cek lewat dashboard di admin lalu klik 'leaderboard jumlah transaksi'.
2. Query user mengeluarkan uang terbanyak bisa di cek lewat dashboard di admin lalu klik 'total pendapatan'.
3. Query daerah terbanyak melakukan pengiriman bisa di cek lewat dashboard di admin lalu klik 'leaderboard lokasi pengiriman'.
4. Query untuk mengecek paket yang berada di dalam truk kurir yang sedang kecelakaan bisa melalui halaman data paket lalu masukan kode pengiriman di bagian search.
(kode pengiriman dari kombinasi no kendaraan si kurir dan tanggal saat paket tersebut dikirim)
5. Billing bisa di cek dari halaman pelanggan lalu notaku, billing sesuai dengan id yang digunakan saat login menjadi pelanggan.
