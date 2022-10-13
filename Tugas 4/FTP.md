#FTP

1. Langkah pertama buka Debian kemudian masuk ke super user dengan command su dan masukkan password Linuxnya. Jika authentication failure silahkan menggunakan command su dan masukkan password Linuxnya.
![SU](https://user-images.githubusercontent.com/112459285/195469206-0e400e8c-aeae-41b7-b648-2f0dd5448f4c.png)

2. Setelah berhasil masuk ke super user, silahkan install proftpd dengan menjalankan command apt-get install proftpd
![apt](https://user-images.githubusercontent.com/112459285/195469223-618c03d1-4a3e-4fac-bb55-ea1d6dc486bd.png)

3. Silahkan menjalankan command nano /etc/apt/sources.list kemudian tambahkan # di depan deb cdrom baris ke-2 atau bisa juga text pada baris ke-2 tersebut dihapus.
![sourt nano](https://user-images.githubusercontent.com/112459285/195469237-9286d4cd-cd91-4913-926e-b855899a9892.png)

4. Simpan dan jalankan command apt-get update dan coba jalankan lagi command apt-get install proftpd untuk menginstall ulang. Kali ini saya menggunakan settingan default yang ada pada aplikasi proftpd, namun jika anda membutuhkan konfigurasi pada FTP server anda, silahkan konfigurasikan pada file /etc/proftpd/proftpd.conf. Selanjutnya pengujian pada proftpd, kali ini saya lakukan dengan menggunakan aplikasi filezilla yang akan diinstall pada computer client. Untuk itu silahkan download aplikasi tersebut pada https://filezilla-project.org/download.php jika sudah diinstall jalankan, maka tampilannya akan sebagai berikut:
![Screenshot 2022-10-13 075642](https://user-images.githubusercontent.com/112459285/195469264-6f3fd2b2-8f26-436f-8caa-aa0dca7ea8e4.png)

5. Jalankan filezilla kemudian masukkan: Host : Isi dengan IP address dari debian Username : Nama user di debian Password : Password debian Port : 21
![EROR](https://user-images.githubusercontent.com/112459285/195469275-6fa679b6-2350-4163-b530-bf43b83fd6ce.png)
akan tetapi punya saya eror
