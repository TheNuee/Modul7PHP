# Modul7PHP
![alt text](https://github.com/TheNuee/Modul7PHP/blob/master/Screenshot%20(47).png)
![alt text](https://github.com/TheNuee/Modul7PHP/blob/master/Screenshot%20(48).png)
![alt text](https://github.com/TheNuee/Modul7PHP/blob/master/Screenshot%20(49).png)

1)<?php
$servername = "localhost";
$database = "niagahos_namadatabase";
$username = "niagahos_user";
$password = "passworddatabase";

// untuk tulisan bercetak tebal silakan sesuaikan dengan detail database Anda
// membuat koneksi
$conn = mysqli_connect($servername, $username, $password, $database);
// mengecek koneksi
if (!$conn) {
    die("Koneksi gagal: " . mysqli_connect_error());
}
echo "Koneksi berhasil";
mysqli_close($conn);
?>

2)saya menuju menu database lalu membuat database dan dengan menginputkan nama database nya

3)CREATE TABLE name_table(
    nama_field tipe(panjang),
    nama_field tipe(panjang),
    ...
    nama_field tipe(panjang),
    nama_field tipe(panjang),
    PRIMARY KEY (nama_field_key)
)


4)UPDATE nama_tabel SET nama_kolom = data_baru WHERE kondisi


5)DELETE FROM nama_tabel WHERE kondisi
