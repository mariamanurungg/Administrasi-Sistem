# Cara Menghubungkan client-server dengan Windows
1. - Buka VirtualBox, kemudian buka kembali Terminal pada VirtualBoxnya.
 ![langkah 1](https://user-images.githubusercontent.com/112459285/192760695-d833571f-46e7-4440-b2a1-b709ed3ba5c7.png)
 
2. - Setelah itu untuk melakukan konfigurasi kita harus login sebagai root ketikan su dan nano /etc/network/interfaces. Kemudian pada bagian password ketikkan password root yang kita buat pada saat instalasi.
![langkah 2](https://user-images.githubusercontent.com/112459285/192760754-ee7106b5-2fce-4d8e-92a0-f4556c80b644.png)
![langkah 3](https://user-images.githubusercontent.com/112459285/192760936-3b75d783-8487-4c43-bb36-a57e26abca67.png) 

3. - Langkah selanjutnya kita akan ke file interface. Edit file dengan menambahkan konfigurasi IP Address server, sebagai contohnya IP Address Server pada eth0 adalah 192.168.243.2 Setelah selesai, tekan ctrl+s lalu Enter untuk menyimpan yang kita buat tadi, kemudian ctrl+x untuk keluar dari editor. 
![langkah 4](https://user-images.githubusercontent.com/112459285/192761029-2f4021ab-6307-4409-8649-22265ed11ef0.png)

4. - Setelah selesai melakukan konfigurasi IP Address, kemudian restart service dari networking pada komputer server kita. Caranya ketikkan perintah /etc/init.d/networking restart lalu tekan Enter. 
![langkah 5](https://user-images.githubusercontent.com/112459285/192761059-e31277d8-44e6-4971-b962-693497c86d74.png)

5. - Langkah selanjutnya kita harus memastikan dulu apakah IP Address kita berhasil atau tidak. Caranya dengan mengetikkan perintah ifconfig atau ip a lalu Enter 
![langkah 6](https://user-images.githubusercontent.com/112459285/192761108-b3c32554-d6b4-4974-b6d4-ff6f6c8de42e.png)

6. - Setelah itu, buka Control Panel -> Network and Internet Connections -> Network Connections. di situ akan terdapat Local Are Connections.
![langkah 7](https://user-images.githubusercontent.com/112459285/192762207-e0ba2c7a-d65d-426f-bff5-e7b3999fe249.png)

7. - Klik kanan pada Local Area Connections lalu pilih Properties. Klik pada Internet Protocol (TCP/IP) kemudian klik Properties, akan muncul Jendela Internet Protocol (TCP/IP) Properties.
![langkah 8](https://user-images.githubusercontent.com/112459285/192762254-6345e24f-b6b5-47c6-acd3-3a4eae1437f4.png)

8. - Pada Internet Protocol (TCP/IP) Properties pilih Use the following IP address, kemudian masukkan IP Address pada network yang sama. Sebagai contoh IP Address untuk komputer client tidak bolah sama dengan yang sebelumnya 192.168.243.2 kemudian pada bagian Subnet mask biasanya akan terisi 255.255.255.0 secara otomatis. Setelah itu tekan Ok. Setelah selesai buka cmd dan ping ip address.
![langkah 9](https://user-images.githubusercontent.com/112459285/192762379-e0e1de59-437a-4978-b88c-2138b69c54ea.png)

