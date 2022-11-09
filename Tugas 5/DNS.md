# DNS

1. Pertama ketikan command sudo su 
2. Kedua ketikan comand "cd /etc/bind" berfungsi untuk konversi dari DNS ke Ip Address. Misalnya ketika kita ketik  www.maria.com melalui Web Browser, maka akan menampilkan website dari server Debian. Buat  file konfigurasi untuk file forward dari DNS tersebut. Karna konfigurasinya cukup banyak, maka kita akan  lsmengcopykan saja dari default yang sudah ada.![2](https://user-images.githubusercontent.com/112459285/197345174-56c344c2-8ef2-4188-8207-8d2fedf58c6f.png)
3. Ketiga ketikan command "exit" dan ketikan ip addrs ![3](https://user-images.githubusercontent.com/112459285/197345299-53b0918b-052d-4e93-bcf8-497782ed8ff3.png) yaitu ip addressnya 192.168.50.1
4. Keempat ketikan command " cd /etc/bind dan nano named.conf.local sebagai konfigurasi ![4](https://user-images.githubusercontent.com/112459285/197345457-188cc0bd-d8de-4541-ab28-3cad2d1eabbd.png) ![4 2](https://user

5. Kelima bagian ini adalah bagian yang paling penting, karena kita akan menentukan nama untuk  domain dari server debian. Di sini kita bisa menggunakan domain dengan TLD (Top Level Domain), tetapi hanya bisa digunakan untuk local saja (tidak terhubung ke internet). Karena untuk mendapatkan TLD 
secara online sudah ada organisasi khusus yang mengaturnya yaitu PANDI untuk di Indonesia Kita akan mengkonfigurasi pada file /etc/bind/named.conf. Silahkan kalian ketikkan perintah nano  /etc/bind/named.conf.local . Dan tuliskan seperti pada gambar dibawah ini. images.githubusercontent.com/112459285/197345505-6570b111-42f5-448e-88da-403b072ce257.png) setelah itu ctrl+s,ctrl+x

6. Keenam ketikan cp db.local db. maria dan nano db.192 lalu enter ![5](https://user-images.githubusercontent.com/112459285/197345708-fa7dcb3a-f496-4e64-b5cf-529812b02bcd.png) maka akan seperti gambar ini ![5 2](https://user-images.githubusercontent.com/112459285/197345809-968c2d2f-9e19-48b0-98f7-66c6cff81594.png) berfungsi untuk konversi Ip Address ke DNS ctrl+i

7. Ketujuh ketikan nano db.maria![6](https://user-images.githubusercontent.com/112459285/197346119-ac6b16b0-d554-4995-9505-2b52a41cc0c1.png)

