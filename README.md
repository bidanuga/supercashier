# Self-Service Simple Cashier

## Requirements / Objectives
- Menambahkan Item: Pengguna dapat menambahkan item ke daftar belanja dengan menyediakan nama item, jumlah, dan harga per item.
- Memperbarui Item: Pengguna dapat memperbarui nama, jumlah, atau harga item setelah item tersebut ditambahkan ke daftar belanja.
- Menghapus Item: Pengguna dapat menghapus item dari daftar belanja.
- Mereset Transaksi: Pengguna dapat mengatur ulang daftar belanja, menghapus semua item yang telah ditambahkan.
- Cek Daftar Belanja: Pengguna dapat melihat daftar saat ini dari item yang telah mereka tambahkan ke daftar belanja.
- Total Harga: Sistem menghitung total harga dari semua item dalam daftar belanja, dengan mempertimbangkan diskon yang berlaku.

## Alur Program / Flowchart
1. Saat kode dieksekusi, akan ditampilkan pesan selamat datang untuk pengguna di Home Market.
2. Pengguna diberikan menu berisi berbagai opsi untuk melakukan berbagai tindakan.
3. Pengguna dapat memilih opsi menu dengan mengetikkan angka yang sesuai dan menekan Enter.
4. Berdasarkan pilihan pengguna, mereka dapat menambahkan, memperbarui, menghapus item, mengecek daftar belanja, menghitung total harga, dan mengatur ulang transaksi.
5. Pengguna dapat keluar dari program dengan memilih "0" dari menu.
6. Kode ini mencakup penanganan kesalahan untuk input yang tidak valid, sehingga menjamin pengalaman pengguna yang lancar.

## Cara Penggunaan
1. Menambahkan Item:
    - Pengguna memilih opsi menu "1".
    - Pengguna memasukkan nama item, jumlah, dan harga per item.
    - Item ditambahkan ke daftar belanja.

2. Memperbarui Item:
    - Pengguna memilih opsi menu "2", "3", atau "4" berdasarkan aspek yang ingin diperbarui (nama, jumlah, atau harga).
    - Pengguna menyediakan nama item yang sekarang dan informasi baru.
    - Item diperbarui dengan informasi baru.

3. Menghapus Item:
    - Pengguna memilih opsi menu "5".
    - Pengguna memasukkan nama item yang ingin dihapus.
    - Item dihapus dari daftar belanja jika ada.

4. Mereset Transaksi:
    - Pengguna memilih opsi menu "6".
    - Daftar belanja dikosongkan, dan semua item dihapus.

5. Cek Daftar Belanja:
    - Pengguna memilih opsi menu "7".
    - Daftar saat ini dari item dengan jumlah, harga, dan total harga ditampilkan.

6. Total Harga:
    - Pengguna memilih opsi menu "8".
    - Total harga dari semua item dalam daftar belanja, setelah diberlakukan diskon yang berlaku, ditampilkan.


![Flowchart Final Project Python II drawio (3)](https://github.com/bidanuga/supercashier/assets/136604752/c2f0e052-3d69-46c0-ac25-87ae7bfda576)


## Hasil Test Case
1. Test Case add_item & check_order:

   ![WhatsApp Image 2023-07-17 at 21 38 14 (1)](https://github.com/bidanuga/supercashier/assets/136604752/7094a3a3-5d25-48af-b5f0-2f1c50ad3b17)


2. Test Case delete_item:

   ![WhatsApp Image 2023-07-17 at 21 38 59 (1)](https://github.com/bidanuga/supercashier/assets/136604752/95fcd01a-4100-4264-b11c-46eb52447c5b)


3. Test Case reset_transaction:

   ![WhatsApp Image 2023-07-17 at 21 44 37 (1)](https://github.com/bidanuga/supercashier/assets/136604752/71731904-505c-4692-a553-d8d93bb5f9a2)


4. Test Case total_price:

   ![WhatsApp Image 2023-07-17 at 21 45 28 (1)](https://github.com/bidanuga/supercashier/assets/136604752/5840f1e9-fc77-4432-bc52-b6774539135a)


## Conclusion
Kode yang diberikan adalah implementasi kelas Transaction yang berfungsi sebagai aplikasi sederhana untuk membantu pengguna dalam mengatur daftar belanjaan. Aplikasi ini memiliki beberapa fitur utama yaitu penambahan item belanja, pengecekan daftar belanja, perhitungan total harga, penghapusan item belanja, pengubahan informasi item belanja (nama, jumlah, & harga item), dan reset transaksi. 

## Future Work
- Membuat sebuah database di mana pengguna dapat menyimpan daftar belanja dari sesi sebelumnya.
- Peningkatan keamanan karena pengguna tidak bisa serta merta mengubah seluruh informasi item belanja.
- Sinkronisasikan dengan barcode scan sehingga pengguna tidak perlu repot mengetik.
- Menambahkan fitur atau method yang berkaitan dengan pembayaran.

