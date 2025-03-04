# keuangan V1

Pastikan Python sudah terinstal, lalu instal Django menggunakan pip:
<br>
>pip install django

Kemudian akses folder projek dengan command line sampai menemukan file yang bernama "manage", lalu jalankan perintah: 
<br>
>python manage.py runserver

Akses urls Web
* Panel admin: http://127.0.0.1:8000/admin/
* Tampilan transaksi: http://127.0.0.1:8000/transaksi/
* Tampilan add transaksi tanpa perantara admin: http://127.0.0.1:8000/transaksi/tambah/
* Ekspor CSV: http://127.0.0.1:8000/transaksi/ekspor-csv/

<br>
username: admin
<br>
password: admin

# Fitur
Fitur Menengah
<br>
1. Filter Pencarian
* Menambahkan filter pencarian berdasarkan nama transaksi.
* Menambahkan filter transaksi berdasarkan jenis (pemasukan/pengeluaran) atau rentang tanggal.

2. Input Transaksi di Frontend
* Membuat formulir dari input transaksi pada halaman web (bukan hanya melalui panel admin).
* Validasi input data (untuk memastikan nominal tidak negatif, tanggal valid, dll.).
  
4. Pagination
* Jika data transaksi banyak, menambahkan paginasi berguna untuk membatasi jumlah data yang ditampilkan per halaman.
  
6. Ekspor Data
* Menambahkan fitur ekspor data transaksi ke dalam format CSV, sehingga bisa dibuka menggunakan Exel.

# Versi Sebelumnya
* V0: https://github.com/krisnasuma/keuangan/
