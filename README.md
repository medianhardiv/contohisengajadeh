# Program Database Perpustakaan
## Fitur 1: Tambah Buku (create_book)
Fungsi create_book() meminta pengguna untuk memasukkan judul dan penulis buku baru.
Melakukan loop melalui setiap buku dalam daftar books untuk memeriksa apakah judul buku sudah ada. Jika sudah ada, mencetak pesan bahwa data sudah ada dan fungsi berakhir.
Jika judul buku belum ada, mengonfirmasi penambahan buku baru dengan meminta input dari pengguna ('Y' atau 'N').
Jika konfirmasi adalah 'Y' atau 'y', menambahkan buku baru ke dalam daftar books dengan format yang sesuai, kemudian mencetak pesan bahwa buku telah ditambahkan.
Jika konfirmasi bukan 'Y' atau 'y', mencetak pesan bahwa penambahan buku dibatalkan.

## Fitur 2: Lihat Semua Buku (read_all_books)
Fungsi read_all_books() mencetak semua buku yang tersedia dalam daftar books, serta buku yang sedang dipinjam dalam daftar borrowed_books.
Menggunakan variabel available_books dan borrowed_books_found untuk menentukan apakah ada buku yang tersedia atau sedang dipinjam.
Jika tidak ada buku yang tersedia, mencetak pesan bahwa tidak ada buku yang tersedia.
Jika tidak ada buku yang sedang dipinjam, mencetak pesan bahwa tidak ada buku yang sedang dipinjam.

## Fitur 3: Cari Buku (read_specific_book)
Fungsi read_specific_book() meminta pengguna untuk memasukkan judul buku yang ingin dicari.
Melakukan iterasi melalui setiap buku dalam daftar books.
Jika judul buku cocok dengan input pengguna, mencetak detail buku. Jika buku tersebut sedang dipinjam, detail buku dicetak dalam warna yang berbeda.
Jika buku tidak ditemukan, mencetak pesan bahwa buku tidak ditemukan.

[Sumber Infromasi](https://www.google.com)
