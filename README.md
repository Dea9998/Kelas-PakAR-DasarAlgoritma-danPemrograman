# Kelas-PakAR-DasarAlgoritma-danPemrograman

## ORDER COFFEE APP

Aplikasi sederhana berbasis CLI (Command Line Interface) untuk pesan kopi.
Dibuat dengan Python menggunakan konsep Object-Oriented Programming (OOP).
Tugas ini terinspriasi dengan video youtube :
https://youtu.be/wPc6mANhIj4?si=9UwSVJbLzl55hqXn

LINK JIKA INGIN MENCOBA
https://colab.research.google.com/drive/16j4KcRfhomkEbp3kk9SSTaaAjRzLy4Ku?usp=sharing


## FITUR

- Pilih kopi dari menu.

- Tambah kopi ke daftar pesanan.

- Lihat ringkasan pesanan.

- Checkout dengan konfirmasi.

- Pesan dan tampilan menggunakan bahasa santai khas lokal.


## CARA MENGERJAKAN 
1. Pastikan sudah install Python minimal versi 3.x.

2. Clone repository ini atau download file.py-nya.

3. Jalankan lewat terminal atau CMD:

kode :

python coffee_order.py

## MENU KOPI

1. Espresso Mantap Jiwa - Rp300
2. Latte - Rp350
3. Cappuccino bukan cina - Rp450
4. Americano Bikin Melek - Rp330

## STRUKTUR KODE

Struktur Kode

- Coffee class

Menyimpan data nama dan harga kopi.

- Order class

1. add_item(): nambah kopi ke pesanan.

2. show_order(): nunjukin daftar pesanan sama total harga.

3. checkout(): konfirmasi beli dan reset pesanan.

5. total(): hitung total harga.

- main() function

coffee-inventory/
├── coffee.py              # File utama program
├── inventory.json         # Data menu & stok (otomatis dibuat)
├── backup_inventory.json  # Backup data
└── README.md              # Penjelasan project

Tempat program jalan, nampilin menu, dan nerima input dari pengguna.

## CONTOH SAAT DIPAKAI

--- Menu Kopi Kita ---
1. Espresso Mantap Jiwa - Rp300 (Stok: 9)
2. Latte - Rp350 (Stok: 10)
3. Cappuccino bukan cina - Rp450 (Stok: 10)
4. Americano Bikin Melek - Rp330 (Stok: 9)
5. Lihat keranjang pesanan
6. Checkout
7. Laporan penjualan
8. Backup data
9. Keluar
Pilih nomor menu: 9

jika pilih opsi "keluar" lalu akan muncul tulisan

Makasih banyak udah mampir Bang! Sampai jumpa lagi.


Ketika checkout tapi belum ada pesanan, bakal muncul:

Your cart is empty.

INI MASIH DALAM PROSES PENGEMBAGAN 
