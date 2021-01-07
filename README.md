menggunakan images php:7.4-apache

     https://katacoda.com/courses/ubuntu/playground1804

Lakukan git clone pada terminal

     git clone https://github.com/Andono-and/cloud.git
Kemudian pull images dari Dockerhub

     docker pull dwisetiyoand/1234:latest
Setelah selesai proses download, kemudian masuk ke directory yang sudah kita buat

     cd cloud
Selanjutnya menjalankan docker compose dengan command berikut

     docker-compose up -d
Setelah selesai kemudian buka browser dan masuk ke localhostnya

     localhost
     localhost:8080
Kemudian login ke database dengan :

     username : root
     password : example
     database : - (kosongi)
Buat databasenya
Kemudian kembali lagi ke localhostnya, dan masuk ke menu CRUD untuk menambah/mengedit data
