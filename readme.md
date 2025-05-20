## Soal Nomor 1
Program ini dimulai dengan meminta pengguna memasukkan jumlah total belanja. Nilai yang dimasukkan dikonversi menjadi tipe data desimal (float) agar bisa menangani nominal uang yang memiliki angka di belakang koma. Setelah itu, program menetapkan nilai awal diskon sebesar nol karena tidak semua pembelian otomatis mendapatkan potongan harga.

Selanjutnya, program memeriksa apakah total belanja melebihi Rp500.000 menggunakan struktur percabangan if. Jika syarat tersebut terpenuhi, maka diskon sebesar 10% dari total belanja dihitung dan ditampilkan pesan bahwa pengguna mendapatkan diskon. Jika tidak memenuhi syarat, diskon tetap nol.

Kemudian, program menghitung jumlah akhir yang harus dibayar dengan mengurangi nilai diskon dari total belanja. Hasil akhirnya ditampilkan dengan dua angka di belakang koma menggunakan format :.2f, supaya lebih rapi dan sesuai dengan tampilan nominal uang.

Metode ini digunakan karena sederhana, mudah dipahami, dan cukup untuk kasus perhitungan diskon berdasarkan batas minimum belanja. Struktur if memungkinkan pengambilan keputusan yang jelas, dan penggunaan tipe float menjamin akurasi penghitungan uang.


## Soal Nomor 2
Berikut penjelasan alur program secara mengalir dan cukup ringkas, sesuai permintaanmu:

Program ini dimulai dengan meminta pengguna memasukkan total belanja, yang kemudian dikonversi ke tipe float agar bisa menangani nilai desimal. Ini penting karena jumlah uang sering kali tidak selalu bilangan bulat.

Setelah itu, program mengatur nilai awal diskon sebesar nol. Kemudian, digunakan struktur percabangan if untuk memeriksa apakah total belanja lebih dari Rp500.000. Jika iya, program menghitung diskon sebesar 10% dari total belanja dan menampilkan pesan bahwa pengguna mendapatkan diskon.

Selanjutnya, total yang harus dibayar dihitung dengan mengurangi diskon dari total belanja. Hasil akhir ditampilkan dengan dua angka di belakang koma agar lebih rapi dan sesuai dengan format mata uang.

Metode ini dipilih karena sederhana, jelas, dan efektif untuk kasus perhitungan diskon berdasarkan syarat tertentu. Cocok digunakan dalam program skala kecil seperti ini, tanpa perlu struktur yang lebih kompleks.

## Soal Nomor 3

Program ini menggunakan fungsi rekursif untuk menghitung nilai faktorial dari suatu bilangan bulat. Fungsi faktorial(n) didefinisikan dengan logika dasar rekursi, yaitu memanggil dirinya sendiri dengan nilai n - 1 hingga mencapai kondisi dasar.

Di dalam fungsi, ada pengecekan kondisi: jika n bernilai 0 atau 1, maka fungsi akan mengembalikan nilai 1. Ini sesuai dengan definisi matematis bahwa faktorial dari 0 atau 1 adalah 1. Jika nilai n lebih dari 1, maka fungsi akan mengembalikan hasil perkalian n dengan hasil pemanggilan fungsi faktorial(n - 1). Proses ini akan terus berulang hingga mencapai nilai dasar tadi.

Setelah fungsi selesai didefinisikan, program meminta pengguna memasukkan sebuah angka. Angka ini dikonversi ke bentuk bilangan bulat (int) agar bisa diproses dalam fungsi faktorial.

Terakhir, program mencetak hasil dari pemanggilan fungsi faktorial berdasarkan input pengguna, dengan format yang rapi.

Metode rekursif ini dipilih karena secara konsep sangat cocok untuk menghitung faktorial—masalah yang secara alami bisa dipecah menjadi submasalah yang lebih kecil. Selain itu, kode menjadi lebih singkat dan mudah dipahami secara logika, meskipun untuk nilai besar, pendekatan iteratif bisa lebih efisien.

##  Soal Nomor 4

Program ini dimulai dengan membuat list kosong bernama nilai_siswa untuk menyimpan nilai dari lima siswa. Kemudian, program menggunakan perulangan for sebanyak lima kali untuk meminta pengguna memasukkan nilai setiap siswa satu per satu. Setiap nilai yang dimasukkan akan dikonversi menjadi bilangan bulat dan disimpan ke dalam list.

Setelah semua nilai dimasukkan, program mencari nilai tertinggi dengan menggunakan fungsi max(). Untuk mengetahui siswa keberapa yang mendapatkan nilai tertinggi, program menggunakan index() untuk menemukan posisi nilai tersebut dalam list, lalu menambahkan 1 agar sesuai dengan urutan siswa yang dimulai dari 1, bukan 0.

Terakhir, program menampilkan hasil berupa nilai tertinggi dan urutan siswa yang mendapatkannya. Pendekatan ini sederhana dan efisien untuk mencari nilai maksimum dari sejumlah data yang jumlahnya tetap.

## Soal Nomor 5

Program ini meminta pengguna untuk memasukkan harga dari tiga barang, satu per satu. Setiap input dikonversi menjadi tipe float agar bisa menangani angka desimal, karena harga barang bisa memiliki nilai di belakang koma.

Setelah ketiga harga dimasukkan, program menjumlahkan semuanya dan menyimpannya dalam variabel total. Kemudian, total harga pembelian ditampilkan ke layar dengan format yang langsung mencantumkan nominal dalam satuan rupiah.

Metode ini digunakan karena sederhana dan langsung. Cocok untuk situasi di mana jumlah barang tetap dan tidak memerlukan perulangan atau struktur data tambahan.
