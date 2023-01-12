# GoAbsensi

## _Apilkasi Presensi Dosen dan Pegawai Berbasis  Mobile_

Aplikasi GoAbsensi Merupakan Aplikasi Presensi Dosen Dan Pegawai Berbasis Website (sebagai dahsboard admin dan layanan API) dan Mobile (Untuk User ketika melakukan Absensi). Dibuat dengan menggunakan framework Laravel, Flutter.

## Kelompok 1 (WEB) Kelas 3E

1. Muhammad Farid Mustakim
2. Dimas Hendra Wijaya
3. Dini Adistia Budi
4. Nadia Pramita Sari
5. Erwin Yunita Sari
6. Surya Dio Alviansyah

## Kelompok 2 (Mobile) Kelas 3E

1. Agam Surya Armanda
2. Denta Artha Deananta
3. Irma Dwi Febriana
4. Diana Yuli Hertanti
5. Nisaul Apriyanti

## Original Repository

Web & Rest Api
https://github.com/agam-surya/presences_laravel
Mobile Flutter
https://github.com/agam-surya/GoAbsensi

## WEB

## Fitur

1. Autentikasi User

- Login Dan Logout User

2. authorization
- admin
- user

3. Dashboard menu
- jumlah user 
- jumlah jabatan 
- jumlah staff sesuai jabatan(contoh = dosen : 10, pegawai: 2)
- tabel Rekomendasi staff / karyawan paling rajin absen menggunakan metode SAW

4. Manajemen posisi/jabatan 

- CRUD(melihat,menambah,mengubah dan menghapus) data jabatan

5. manajemen staff sesuai jabatan

- CRUD(melihat,menambah,mengubah dan menghapus) data staff sesuai jabatan

6. manajemen waktu absensi

- CRUD(melihat,menambah,mengubah dan menghapus) data waktu absen

7. manajemen hari libur

- CRUD(melihat,menambah,mengubah dan menghapus) data hari libur


8. laporan kehadiran 

- list absensi
- cetak list absensi format pdf

9. data izin user

- melihat data izin semua user
- terima atau tolak data izin
- download file izin yang telah dikirim

10. Lokasi Absen

- melihat lokasi absen

## Demo Web

| URL      | https://goabsensi-beta-2.000webhostapp.com/ |
| -------- | ------------------------------------------- |
| email    | admin@gmail.com                             |
| password | password                                    |

## Instalasi WEB & REST API

### Spesifikasi

- PHP ^7.4/^8 sesuai kebutuhan hosting
- Laravel ^8
- PHP Composer
- Database MySQL atau MariaDB
- web hosting 000webhost

### Cara Install

1. Clone atau download source code
   - Pada terminal, clone repo `git clone https://github.com/agam-surya/goAbsensi-web/`
   - Jika tidak menggunakan Git, silakan **Download Zip** 
2. buka folder yang telah di extract `cd goAbsensi-web`
3. `composer install`
4. `cp .env.example .env`
   - Jika tidak menggunakan Git, bisa rename file `.env.example` menjadi `.env`
5. Pada terminal `php artisan key:generate`
6. Buat **database pada mysql** untuk aplikasi ini dengan nama `goabsensi`
7. **Setting database** pada file `.env`
8. `php artisan migrate`
9. `php artisan db:seed`
10. `php artisan serve`
11. Selesai

### Login Admin

```
Username: admin@gmail.com
Password: password
```

## Api Akses Dan Dokumentasi

Dokumentasi Api Bisa Diakses Di : https://documenter.getpostman.com/view/23565435/2s8YzXvfNJ


## MOBILE APP

## Fitur

1. Autentikasi User

- Login Dan Logout User
- active session
- check internet connection

2. Absen Masuk

- deteksi radius lokasi absen user dengan lokasi kampus 
- alert dialog sebagai keterangan absen

3. Absen Pulang

- deteksi radius lokasi absen user dengan lokasi kampus
- alert dialog sebagai keterangan absen

4. Fitur Ijin / Permission

- ijin WFH (masih tetap bisa absen dan terhitung hadir)
- ijin Sakit (tidak bisa melakukan absensi)
- bisa mengunggah file ijin, dan juga akhir waktu ijin
- memberi keterangan ijin

5. History atau Riwayat absensi

- Menampilkan setiap aktifitas (absen masuk, pulang, ijin, status ijin)
- Menampilkan Waktu pada saat melakukan aktifitas tersebut

6. Management User Profile

- add/update photo profile
- update informasi user (nama, no HP, alamat)

7. Menampilkan 5 Peringkat Dosen Terbaik Dengan Metode SAW

### Spesifikasi
- DART version: 2.17.0
- FLUTTER version: 3.0.0
- DEVTOOLS version: 2.12.2

cara installasi :

    - Clone project ini
    - ketikkan perintah flutter pub get di terminal

Ubah link web server API pada file lib\common\constant.dart *optional*
    
cara run project : 
    - hubungkan HP ke Laptop dengan kabel data
    - ketikkan flutter run di terminal
    - pilih devices yang akan menjalankan flutter nya ( windows,browser, atau Nama device kamu)
    - kemudian tunggu sampai proses compile nya selesai

atau kita bisa langsung install app-debug.apk nya di HP.


## Screenshots WEB
![Screenshot (217)](https://user-images.githubusercontent.com/72247163/211124424-86cf12b7-b87d-464f-8cae-4e9f71059f2e.png)
![Screenshot (218)](https://user-images.githubusercontent.com/72247163/211124426-2cadbac1-74d6-42ae-a61c-3c7aa3914992.png)
![Screenshot (219)](https://user-images.githubusercontent.com/72247163/211124427-a3b23903-a920-429d-848b-cbba703c3868.png)
![Screenshot (220)](https://user-images.githubusercontent.com/72247163/211124429-bbe17155-48a6-4a8e-b0a3-c25fe61dfc63.png)
![Screenshot (221)](https://user-images.githubusercontent.com/72247163/211124430-3bd46f70-e806-489b-b9e0-4e952a1138b8.png)
![Screenshot (222)](https://user-images.githubusercontent.com/72247163/211124431-4d679051-7a76-4b9a-8c96-724faee2e0a9.png)
![Screenshot (223)](https://user-images.githubusercontent.com/72247163/211124432-9a098c13-d9cc-4d27-9221-b268ee98228d.png)
![Screenshot (224)](https://user-images.githubusercontent.com/72247163/211124433-96ef051b-b4b9-46f4-9435-f9c5df3edbab.png)
![Screenshot (225)](https://user-images.githubusercontent.com/72247163/211124434-2ac2b79a-9819-4e29-abcf-77f7779f85d5.png)
![Screenshot (226)](https://user-images.githubusercontent.com/72247163/211124436-b008e47d-a63e-4bcb-9885-1b2b414a6ee0.png)
![Screenshot (229)](https://user-images.githubusercontent.com/72247163/211124437-9025634c-3f75-4a56-a323-cadc7193277b.png)
![Screenshot (230)](https://user-images.githubusercontent.com/72247163/211124439-d63e47d3-7d4a-4ffe-82a9-3c82cbbd1c2e.png)
![Screenshot (231)](https://user-images.githubusercontent.com/72247163/211124440-66816c79-08d0-43dd-a5d0-4b3499338cc0.png)
![Screenshot (232)](https://user-images.githubusercontent.com/72247163/211124442-19dbc8dd-1e76-4fb5-af13-85f81b89898b.png)
![Screenshot (233)](https://user-images.githubusercontent.com/72247163/211124444-2b033676-ebed-40c9-8077-f9e45588cac3.png)
![Screenshot (234)](https://user-images.githubusercontent.com/72247163/211124445-3b1168e9-e437-4c6b-a2af-c1ec672e1f67.png)
![Screenshot (235)](https://user-images.githubusercontent.com/72247163/211124446-cde76af6-78bc-4906-b801-25433f45bebc.png)
![Screenshot (237)](https://user-images.githubusercontent.com/72247163/211124448-12e443ee-9f91-4e06-a7eb-704894c4bf91.png)
![Screenshot (238)](https://user-images.githubusercontent.com/72247163/211124449-51b8bc10-8ed0-4fad-b722-bb2bc322b2be.png)
![Screenshot (239)](https://user-images.githubusercontent.com/72247163/211124450-3c645963-4fbe-455d-93d1-0b968ab67958.png)
![Screenshot (240)](https://user-images.githubusercontent.com/72247163/211124452-fcdc98ba-e450-4f4b-b7f9-674dd89a6d7a.png)
![Screenshot (241)](https://user-images.githubusercontent.com/72247163/211124453-61f6af99-27a2-45da-804b-e2d3eb028b24.png)
![Screenshot (242)](https://user-images.githubusercontent.com/72247163/211124456-14296871-296c-41fe-b4d3-518423e190fb.png)
![Screenshot (243)](https://user-images.githubusercontent.com/72247163/211124457-ab0937f2-e3f1-4c5d-ab11-6c24b2b6b4f3.png)
![Screenshot (244)](https://user-images.githubusercontent.com/72247163/211124458-6d16c6bc-6c11-40ec-89ac-9ce9533f4e44.png)
![Screenshot (245)](https://user-images.githubusercontent.com/72247163/211124459-1c880472-506c-4a2a-be9f-15f039b273d8.png)
![Screenshot (216)](https://user-images.githubusercontent.com/72247163/211124461-6505fbdd-1214-4fda-b3bd-b3b4bc517e80.png)

    
## ScreenShots MOBILE APP


# SplashScreen
![841be807-3235-4089-b4f8-61b6cc15b1b6](https://user-images.githubusercontent.com/72247163/210799899-04f4b5c8-5284-42c5-a9c4-efe098da59de.jpg)

# Login Page
![ba77cb0f-b9db-4e9b-b527-cb660468630a](https://user-images.githubusercontent.com/72247163/210799961-495a4ae0-4d89-4349-91d0-21512e0a5d86.jpg)

# Home Page
![035b66a5-a590-4ec6-b5ea-8207ec2ee762](https://user-images.githubusercontent.com/72247163/210800028-437cdb13-ecfc-4040-aac2-4ea917a2dbea.jpg)

# Alert Dialog
![4f66c077-99d2-4ea9-989d-63ec0929de22](https://user-images.githubusercontent.com/72247163/210800870-1c8c4799-e4bf-4ee8-9a8c-1978a5fa7922.jpg)
![f6e34990-6ed4-456f-aab9-f4a6888fc168](https://user-images.githubusercontent.com/72247163/210801595-9cd879c7-177b-4c35-b8bd-fd6036321fc6.jpg)
![536099b4-2bd1-4c80-8bb5-985b0328ff21](https://user-images.githubusercontent.com/72247163/210801594-29b7ef8c-0f4b-4ffb-a803-dd7706169724.jpg)

# Izin
![50fc0de3-c8b7-4754-a7cb-60e2d9cd35b4](https://user-images.githubusercontent.com/72247163/210800297-674f5cab-023d-44f2-b006-401e63d90dd6.jpg)

# History Page
![fc9b74e0-7583-4463-a14e-48d66c69d6d8](https://user-images.githubusercontent.com/72247163/210800103-ee34aebf-344f-44bd-8696-83853543e8c2.jpg)

# Profile Page
![759ed0a4-cc43-4509-98c8-59bea5a55839](https://user-images.githubusercontent.com/72247163/210800323-da8f632e-38a4-4928-847b-d13b7ed29995.jpg)

# Detail Photo Profile
![3c44d1de-5b83-4905-9880-f9a8baa1b6c1](https://user-images.githubusercontent.com/72247163/210801596-a880ad4e-0d22-44d2-9545-a46abe2d474b.jpg)
