# Cara Menghubungkan client-server dengan Windows

1. -  Pertama, jalankan mesin virtual Debian 11 Linux terlebih dahulu. Caranya klik mesin virtual Debian 11 kemudian klik tombol Mulai. ![Screenshot 2022-09-15 175711](https://user-images.githubusercontent.com/112459285/193059024-5165d8c0-f140-4ff6-a171-fa17a6b8796e.png)

2. - Kedua setelah itu untuk melakukan konfigurasi kita harus login sebagai **root**.(*su*). Karena di dalam sistem linux, root adalah hak akses yang paling tinggi (Super User). Jika kita login sebagai user biasa, kita tidak akan bisa melakukan konfigurasi. Caranya pada bagian user ketikkan root (su) lalu tekan Enter, kemudian pada bagian password ketikkan password root yang kita buat pada saat instalasi Debian Linux. ![Screenshot 2022-09-22 070124](https://user-images.githubusercontent.com/112459285/193059129-853e8e88-94d1-4187-b916-b34fc36a74c1.png)

3. - Ketiga ketik perintah terminal : nano /etc/network/interfaces lalu tekan Enter. ![zz](https://user-images.githubusercontent.com/112459285/193059834-bac84af1-ac3f-43a9-814b-5dccfda0102a.png)

4. - Keempat langkah selanjutnya kita akan ke file interface. Edit file dengan menambahkan konfigurasi IP Address server, sebagai contohnya IP Address Server pada eth0 adalah 192.168.243.2 Setelah selesai, tekan ctrl+s lalu Enter untuk menyimpan yang kita buat tadi, kemudian ctrl+x untuk keluar dari editor. ![yy](https://user-images.githubusercontent.com/112459285/193061242-c7e69e9e-2a95-4026-a930-b747db1ec07e.png)

5. - Kelima setelah selesai melakukan konfigurasi IP Address, kemudian restart service dari networking pada komputer server kita. Caranya ketikkan perintah /etc/init.d/networking restart lalu tekan Enter.
6. - Keenam langkah selanjutnya kita harus memastikan dulu apakah IP Address kita berhasil atau tidak. Caranya dengan mengetikkan perintah **ifconfig** atau **ip a** lalu Enter
8. - Ketujuh langkah selanjutnya klik kanan pada Local Area Connections lalu pilih Properties. Klik pada Internet Protocol (TCP/IP) kemudian klik Properties, akan muncul Jendela Internet Protocol (TCP/IP) Properties. Kemudian Klik OK.
9. - Terakhir pada Internet Protocol (TCP/IP) Properties pilih Use the following IP address, kemudian masukkan IP Address pada network yang sama. Sebagai contoh IP Address untuk komputer client tidak bolah sama dengan yang sebelumnya 192.168.243.1, kemudian pada bagian Subnet mask biasanya akan terisi 255.255.255.0 secara otomatis. Setelah itu tekan Ok. Setelah selesai *buka cmd dan ping ip address*
