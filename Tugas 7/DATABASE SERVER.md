# DATABASE SERVER

1. - Login ke debian dengan menggunakan user root dengan cara menjalankan command su atau sudo -i setelah itu jalankan command **apt-get install mysql-server** untuk menginstall database pada server kita, jika ada keterangan "Package 'mysql-server' has no installation candidate" coba jalankan command **apt-get install default-mysql-server**.

2. - Jika sudah selanjutnya adalah menginstall phpmyadmin, aplikasi ini digunakan untuk memudahkan user yang tidak terbiasa dengan command line karena aplikasi ini menggunakan GUI. Untuk menginstallnya silahkan jalankan command **apt-get install phpmyadmin**. Pilih apache2 sebagai web server yang digunakan.

    - Pada form di bawah ini pilih **Yes**

3. - Setelah itu kalian akan diminta untuk memasukkan root password dan konfirmasi password pada saat installasinya berjalan, saran saya buat semudah mungkin agar kalian tidak lupa pada saat ingin menggunakannya. 

4. - Selanjutnya adalah pengujian, Silahkan kalian buka browser dalam linuxnya lalu ketikkan alamat (IP server kalian)/**phpmyadmin**. Isi dengan Username = root, Password = (password yang kalian masukkan pada saat installasi)