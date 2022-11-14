# DATABASE SERVER

1. - Login ke debian dengan menggunakan user root dengan cara menjalankan command su atau sudo -i setelah itu jalankan command **apt-get install mysql-server** untuk menginstall database pada server kita, jika ada keterangan "Package 'mysql-server' has no installation candidate" coba jalankan command **apt-get install default-mysql-server**.
![apt-get install default-mysql-server](https://user-images.githubusercontent.com/112459285/201567002-c883e7c4-385f-4db2-9d75-f3d3d562847b.png)


2. - Jika sudah selanjutnya adalah menginstall phpmyadmin, aplikasi ini digunakan untuk memudahkan user yang tidak terbiasa dengan command line karena aplikasi ini menggunakan GUI. Untuk menginstallnya silahkan jalankan command **apt-get install phpmyadmin**. Pilih apache2 sebagai web server yang digunakan.
![apt-get install phpmyadmin](https://user-images.githubusercontent.com/112459285/201567017-1714710f-86a4-4126-8b47-f32c5bbabfc9.png)

    - Pada form di bawah ini pilih **Yes**
![apt-get install phpmyadmin (2)](https://user-images.githubusercontent.com/112459285/201567031-9f5fdf91-e5de-432a-b48b-0cff420f4af9.png)

3. - Setelah itu kalian akan diminta untuk memasukkan root password dan konfirmasi password pada saat installasinya berjalan, saran saya buat semudah mungkin agar kalian tidak lupa pada saat ingin menggunakannya. 
![apt-get install phpmyadmin (3)](https://user-images.githubusercontent.com/112459285/201567054-395e8578-8047-4f6c-abc8-16fe95c7d991.png)

![apt-get install phpmyadmin (2)](https://user-images.githubusercontent.com/112459285/201567061-454a273f-6294-49f4-a960-bd187193145a.png)
4. - Selanjutnya adalah pengujian, Silahkan kalian buka browser dalam linuxnya lalu ketikkan alamat (IP server kalian)/**phpmyadmin**. Isi dengan Username = root, Password = (password yang kalian masukkan pada saat installasi)
