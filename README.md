# Latihanku-Swalayan

[1]Deskripsi Program
1. Program menggunakn bahasa pemrograman Python berextension file .ipynb
2. Program dapat dijalankan di Visual Studio Code, Jupyter Notebook, Google Colab, dan beberapa perangkat yang mendukung
3. Menggunakan file .csv sebagai dataset/databset dari program

[2]Detail Akun Program
1. Terdapat 2 akun yaitu User dan Admin
2. Admin dapat mengakses tampilan Barang sehingga bisa melakukan Penambahan Barang, Update Barang, dan Menampilkan Barang
3. User hanya bisa Menampilkan Barang dan Top-Up

[3]Tampilan Awal Program
1. Ditampilkan pada pilihan Register/Login/Forgot Password
        
        1.1 Register
            Mengisi Username,Password dan Pin sebagai daftar akun pada program
            1.1.1 Username
                  Username dapat berisikan gabungan string dan integer
            1.1.2 Password
                  Password dapat berisikan gabungan string dan integer
            1.1.3 Pin
                  Pin berisikan integer
        1.2 Login
            Jika sudah mempunyai akun bisa langsung menggunakan pilihan login, jika belum harus 
            mendaftarkan akun terlebih dahulu dan langsung diarahkan ke login
        1.3 Forgot Password
            Forgot Password/Lupa Password digunakan untuk mengganti password sebelumnya dengan mengisi 
            username dan pin, jika username dan pin ditemukan maka bisa melakukan pergantian password
        
[4]Menu Program
1. Tampilan User dapat mengakses Top-Up dan Menampilkan semua barang

        1.1 Top-Up 
            User dapat mengisi saldo pada akun tersebut
        1.2 Tampilkan Barang
            User dapat melihat semua barang yang terdapat dalam dataset/database
            1.2.1 Tampilkan Semua Barang
                  Menampilkan semua barang yang tersedia
            1.2.2 Filter Barang
                  Barang yang ditampilankan disesuai dengan jenis(Buah/Sayur/Lain)
            1.2.3 Cari Barang
                  Mencari barang sesuai Nama yang lebih spesifik     
2. Tampilan Admin dapat mengakses Barang

        2.1 Tambah Barang
            Admin dapat menambahkan Barang baru ke dalam dataset/database
        2.2 Update Barang
            Admin dapat memperbaharui Nama Barang, Harga Barang, Jenis Barang, dan Stock Barang
            
        
[5]Menu Belanja
1. Tampilan User dapat mengakses Top-Up dan Menampilkan semua barang

        5.1 Belanja 
            User dapat membeli barang belanjaan dari dataset market.csv
        5.2 Bayar Belanja
            Apabila dirasa sudah puas belanja, user bisa langsung membayar belanjaan.
            Keranjang belanja otomatis terhapus bila user sudah membayar belanja
            
            
[5]Lampiran
Dilampirkan berupa file:
1. account.csv 
   Berfungsi untuk menampung semua akun yang dimasukkan ke dalam dataset/database
2. market.csv
   Berfungsi untuk menampung semua barang
3. bill.csv
   Berfungsi untuk menampung pesanan barang belanjaan
4. loginaccount.csv
   Berfungsi untuk mengambil data akun yang sedang login  
5. Swalayan.ipynb
   Program yang akan dijalankan
   
[6]Fitur yang akan ditambahkan 
~~1. Berbelanja~~
   
[7]Referensi
1. StackOverflow
2. GeeksforGeeks
3. Ritchie Ng
4. Real Python
5. Documentations

Last Update :
06/02/2021 6:06 PM
