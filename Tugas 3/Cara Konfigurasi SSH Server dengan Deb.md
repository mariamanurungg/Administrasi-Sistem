# Cara Konfigurasi SSH Server dengan Debian

1. Pertama tahap ini silahkan login sebagai user bisa klik su  
![1](https://user-images.githubusercontent.com/112459285/193229141-dd9c4207-51d0-4e91-9b33-f7fe018c3ae2.png)

2. Kedua Sebelumnya kita akan mengecek kembali, bahwa adapter 1 / eth0 ter bridge ke internet, karena pada saat ini koneksi internet saya menggunakan VirtualBox Host-Only Network #2 , maka disesuaikan dengan adapter nya, oleh karena itu saya menggunakan Intel(R) Wireless-AC 9560 160Mhz ![adapter](https://user-images.githubusercontent.com/112459285/193231461-10a5eda4-6b36-4182-8734-dedf4c6da21d.png) Jika sudah, saat nya kita lakukan konfigurasi IP Address pada Linux Debian, tapi sebelum itu kita akan mengecek berapakah IP Address Internet yang kita dapatkan dari ISP.
3. ketiga setting ip nya dengan ketikan perintah nano /etc/network/interfaces , crtl+x dan ctrl+s  
![in](https://user-images.githubusercontent.com/112459285/193229690-b241bb30-c5e4-4d8d-ba1e-87cdb8968f67.png)
4. Keempat ketikan ip a 
![2](https://user-images.githubusercontent.com/112459285/193229803-fc04727f-658e-43e8-b3e7-eb9b5f795776.png)
5. Kelima buka aplikasi futty masukkan ip 192.168.43.105
![4](https://user-images.githubusercontent.com/112459285/193229862-6fe73d63-fc30-475b-8623-52562db11c39.png)
6. dan akan muncul 
![3](https://user-images.githubusercontent.com/112459285/193229885-0b7800d9-2816-4b0a-87b0-0d49d0be62a2.png)
