# Simulasi-Konfigurasi-Router-Cisco
Ini adalah tugas hasil kuliah dengan proyek simulasi konfigurasi pada perangkat Cisco router

Proyek ini ada dikarenakan untuk mengetahui apakah mahasiswa sudah mampu melakukan konfigurasi pada peramglat cisco router secara nyata dan bukan dengan simulasi pada platform cisco packet tracer. Berikut penjelasannya.

1.	Download & Install PuTTY
-	Masuk ke browser manapun yang kamu suka
-	Ketik di pencarian putty dan enter
-	Klik yang paling atas dengan nama doamin https://putty.org
-	Kemudian download dan kemudian jalankan PuTTY
2.	Siapkan Router dan kabel konsol
3.	Pasang kabel sumber daya router dan nyalakan
4.	Colokkan kabel konsol ke port konsol di router dan sambungkan USB ke laptop
5.	Masuk ke manajer perangkat dan periksa di bagian port dengan nomor serial berapa
6.	Di PuTTY, cek nomor serial dengan memilih tipe serial dan masukkan nomor port, misalnya COM3 dan open
7.	Setelah masuk ke terminal router, router akan melakukan booting terlebih dahulu
8.	Setelah selesai akan muncul perintah:
Router>
9.	Kemudian ketik perintah:
    Router>enable
-	Perintah enable ini digunakan untuk masuk kedalam user EXEC
10.	Setelah masuk ke user EXEC, ketik perintah:
    Router>conf t
-	Perintah ini digunakan untuk masuk ke global configuration yang dimana ini adalah singkatan dari configure terminal
11.	Setelah itu masukkan hostname, alamat IP, subnet mask, masukkan password di line console 0, masukkan password di line vty 0 15, masukkan enkripsi password, menerapkan service password encryption, dan pesan banner
-	Hostname ini digunakan untuk mengganti nama perangkat di sisi terminal
-	Alamat IP dan subnet mask ini digunakan untuk menambahkan alamat IP dan subnet mask ke target port ethernet, misalnya di G0/1
-	Line console 0 ini adalah untuk masuk di user EXEC melalui kabel konsol
-	Line vty 0 15 ini adalah untuk melakukan remote router di user EXEC
-	Enkripsi password ini digunakan untuk mengenkripsi password yang telah dimasukkan ke router
-	Pesan banner ini digunakan untuk memberikan pesan saat mau masuk ke konfigurasi user EXEC
