
# Aplikasi Surat Masuk & Keluar

### Author

- [Yusuf](https://www.github.com)

#### Requirement
- PHP 7.4+
- MySQL
- Apache / NginX

#### PANDUAN
- Pastikan conn.php di konfigurasi (abaikan jika sudah benar)
- Jika ingin menambah modul CRUD buat folder, misalkan kamu ingin membuat CRUD "user", maka buat folder dengan nama "user".
- Di dalam folder tersebut ada file index.php, tambah.php, edit.php, hapus.php
- Kemudian ada file yang khusus untuk handle data, contoh : proses_tambah.php, proses_edit.php

### CARA PEMANGGILAN CONN.PHP

contoh : kamu berada di folder user. jadi pemanggilan conn.php menggunakan
require_once('../conn.php');
atau
include_once('../conn.php');


