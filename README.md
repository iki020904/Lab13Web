# Lab13web

Nama : Muhammad Rifqi aziz

NIM  : 312210111

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.

2. Buat folder baru dengan nama `Lab13web` pada docroot webserver (htdocs).

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum
> Untuk melakukan instalasi ***Codeigniter 4*** dapat dilakukan dengan dua cara, yaitu cara *manual* dan menggunakan *composer*. Pada praktikum ini kita menggunakan cara *manual*.
- Unduh Codeigniter dari website https://codeigniter.com/download
- Extrak file zip Codeigniter ke direktori htdocs/*(folder kalian)*.
- Ubah nama directory framework-4.x.xx menjadi ci4 *(nama file bebas)*.

1. **Aktifkan Extension di XAMPP Control Panel** Untuk mengaktifkan extension tersebut, melalui **XAMPP Control Panel**, pada bagian apache klik **config**

> Setelah itu lanjut dengan mengklik PHP (php.ini)

- Pada bagian extension, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian save atau simpan kembali filenya dan restart Apache web server.
  
> Extension yang perlu diaktifkan :

- php-json extension untuk bekerja dengan JSON.

- php-mysqlnd native driver extension untuk MySQL.

- php-xml extension untuk bekerja dengan XML.

- php-intl extension untuk membuat aplikasi multibahasa.

- libcurl (opsional), jika ingin pakai Curl.

2. **Menjalankan CLI (Command Line Interface)**

- Setelah melakukan restart **Apache web server**, silahkan nyalakan kembali Apache dan MySQL
- Lalu kalian dapat membuka browser dengan alamat http://localhost/nama_folder_kalian/ci4/public
- Kemudian kalian dapat membuka atau menjalankan **CLI** ***(Command Line Interface)***, Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk mengakses CLI buka terminal/command prompt yang telah disediakan **XAMPP**.
- Selanjutnya arahkan lokasi directory sesuai dengan directory project yang kalian buat **(xampp/htdocs/nama_folder_kalian/ci4)**
- Kemudian jalankan perintah untuk memanggil CLI Codeigniter dengan script ini :
```
php spark
```

3. **Mengaktifkan Mode Debugging**
   
- Codeigniter 4 menyediakan fitur **debugging** untuk memudahkan developer untuk mengetahui pesan error apabila terjadi kesalahan dalam membuat kode program.
- Untuk memudahkan mengetahui jenis errornya, maka perlu mengaktifkan mode debugging dengan cara mengubah nilai konfigurasi pada environment variable **CI_ENVIRONMENT** menjadi **development.**

> **Hasil Output Lab12 :**

![1](https://github.com/iki020904/Lab13Web/assets/115804283/4ac2d728-15af-4b9c-9e26-db38ae646809)



> **Hasil Output Lab13web :**

![2](https://github.com/iki020904/Lab13Web/assets/115804283/66c6cd0c-ddf3-426a-a511-ffc1750db3bf)


![3](https://github.com/iki020904/Lab13Web/assets/115804283/4d4202bc-5533-4d40-ae26-59d06a589219)


## Selesai, Terima Kasih
