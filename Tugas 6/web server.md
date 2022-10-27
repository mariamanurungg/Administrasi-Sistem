# WEB SERVER 

1. Langkah pertama buka Debian kemudia masuk ke super user dengan command **sudo su** dan masukkan password Linuxnya.

2. Langkah kedua silahkan install web server dengan mennjalankan command **apt-get install apache2**

3. Langkah ketiga jika sudah berhasil silahkan jalankan penginstalan bahasa pemprograman php dengan command **apt-get install php8.1**(php8.1 artinya php versi 8.1) jika gagak coba jalankan command **sudo apt -y install php8.1**

4. Langkah keempat selanjutnya konfigurasi, kita bisa melihat hasil dengan mengunjungi web browser dan mengetikkan alamat IP server kita (jalankan command **ip a** untuk melihat IP server) maka akan muncul seperti gambar dibawah ini.

5. Langkah kelima selanjutnya kita akan menguji menggunakan script php untuk menampilkan info php pada server kita, Kita akan membuat skrip php pada folder **/var/www**  Jalankan command **nano /var/www/html/test/php** atau jika gagal **nano /var/www/test.php**. Setelah itu masukkan skrip seperti gambar dibawah ini 

6. Langkah keenam yaitu ;yang langkah terakhir selanjutnya buka browser dalam linuxnya lalu ketik (**IP server kalian)/test.php.** Maka akan muncul laman tentang info dari php yang kita install pada server. 

**SELESAI**
