# FTP

1. Langkah pertama buka Debian kemudian masuk ke super user dengan command sudo su dan masukkan password Linuxnya. Jika authentication failure silahkan menggunakan command su dan masukkan password Linuxnya.
![SUDO](https://user-images.githubusercontent.com/112459285/197343048-bc4382bf-db62-4b80-b256-ef8fdae2e259.png)


2. Langkah kedua setelah berhasil masuk ke super user, silahkan install proftpd dengan menjalankan command apt-get install proftpd
![apt-get install proftpd](https://user-images.githubusercontent.com/112459285/197343101-5546fa96-e5c8-4e2b-9a15-cdbf7fb22ea0.png)


3. Langkah ketiga silahkan menjalankan command nano /etc/proftpd/proftpd.conf, kemudian hapus tanda # di depan DefaultRoot~ baris ke-14 dan Port 21 ![conf](https://user-images.githubusercontent.com/112459285/197343337-ca89b640-65f0-4420-80c6-903a9475e3cb.png)


4. Langkah keempat silahkan menjalankan command systemctl restart proftpd.service

5. Langkah kelima Jalankan filezilla kemudian masukkan: Host : Isi dengan IP address dari debian Username : Nama user di debian Password : Password debian Port : 21![fz](https://user-images.githubusercontent.com/112459285/197343650-e06d2de9-efb8-4528-bd59-25125d8d3ecc.png) hasil penampilannya comand ls
![men](https://user-images.githubusercontent.com/112459285/197343688-1a4954fd-4475-418e-9665-84919dea605f.png)
