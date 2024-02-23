## Background
Project Andi adalah seorang pemilik supermarket besar di salah satu kota di Indonesia. Andi memiliki rencana untuk melakukan perbaikan proses bisnis, yaitu andi akan membuat sistem kasiryang self-service di supermarket miliknya. sehingga customer bisa memasukan item yang dibeli, jumlah yang dibeli, dan harga per item yang dibeli.

---

## Objective
Proyek ini bertujuan untuk menciptakan sistem kasir swalayan dengan alur sebagai berikut :

1. Pelanggan membuat ID transaksi pelanggan.
2. Pelanggan menginput nama barang, jumlah barang, dan harga barang yang dibeli.
3. Apabila ternyata terjadi kesalahan dalam memasukkan nama barang, jumlah barang, atau harga barang, pelanggan dapat mengubah atau memperbarui barang :
   
    A). perbarui nama item
   
    B). perbarui jumlah item
   
    C). perbarui harga barang
4. Jika pelanggan membatalkan pembelian suatu barang, pelanggan dapat menghapus barang tersebut:
   
    A). hapus 1 item
   
    B). reset semua transaksi
   
5. Jika pelanggan sudah selesai membeli, namun masih ragu apakah harga barang dan nama yang dimasukkan sudah benar, pelanggan dapat memeriksa pesanan dengan output sebagai berikut:
   
    A). Mengeluarkan pesan “Ada kesalahan input data” jika terjadi kesalahan input.
   
    B). Jika sudah benar maka, Menampilkan tabel yang berisi semua data pesanan.
   
---

## Penjelasan atribute dan methode

1. `transaction` attribute dengan type list, yang digunakan untuk menyimpan data inputan
   
2. method `add_item` , digunakan untuk memasukkkan item yang dibeli

3. method `update_item_nama`, digunakan untuk update item nama ketika ada kesalahan inputan

4. method `update_item_jumlah`, digunakan untuk update item jumlah ketika ada kesalah inputan jumlah item

5. method `update_item_harga`, digunakan untuk update harga item ketika salah input untuk jumlah item yang dibeli

6. method `delete_item`, digunakan untuk menghapus salah satu item yang ingin dihapus

7. method `reset_transaction`, digunkan untuk mereset semua transaksi yang ada

8. method `check_order`, digunakan untuk mengecek orderan apakah sudah benar atau ada salah inputan

9. method `total_ptice`, digunakan untuk menghitung total belanjaan, dalam method ini ada beberapa kondisi, yaitu ketika belanjaan lebih dari 500.000 mendapat diskon 10%, leih dari 300.000 mendapat diskon 8%, dan lebih dari 200.000 mendapat diskon 5%

---


