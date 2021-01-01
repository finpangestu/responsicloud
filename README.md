# responsicloud

Nama  : Muhammad Alfin Pangestu
NIM   : 195410015

Image Link : https://hub.docker.com/_/php

Petunjuk :
1. Git Clone pada terminal : git clone https://github.com/finpangestu/responsicloud.git
2. pull image dari docker hub : docker pull finpangestu/responsicloud
3. masuk direktori : cd responsicloud
4. Running Docker Compose : docker-compose up -d
5. Jika selesai buka web browser / tab di browser ketik : localhost (Menu web), localhost:8080 (database)
6. Login database dengan username : root, password : example
7. Buat data base dengan creat tabel dengan nama tb_blog
8. Buat isi table dengan : 

            id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) | sisanya kosongkan
            
            nama  | varchar | lenght (25) | options (default) | sisanya kosongkan
            
            nim | int | length (9)  | sisanya kosongkan
            
            Default values (conteng), Comment (conteng)
            
            lalu save.
9. Buka kembali tab localhost, masuk pada bagian crud
10. Jika selesai, turn off docker compose : docker-compose  stop
