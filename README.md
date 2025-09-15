*Deskripsi Program*

Program Manajemen Koleksi Fashion adalah aplikasi berbasis Java yang dibuat untuk membantu mengelola data koleksi fashion pribadi seperti pakaian, sepatu, dan aksesori. Program ini menyediakan fitur CRUD serta dilengkapi fitur filter untuk mempermudah pengelompokan koleksi. Dengan adanya program ini, pengguna dapat menyimpan dan menata informasi koleksi secara lebih rapi dan efisien dibanding mencatat manual, sehingga memudahkan pencarian maupun pembaruan data fashion yang dimiliki.

<img width="352" height="413" alt="image" src="https://github.com/user-attachments/assets/255a18a5-9bb8-47d5-b67a-a3c491dfbe9a" />

Saat program dijalankan, pertama kali ditampilkan judul program dan menu utama. Bagian ini menjadi awal bagi pengguna untuk memilih fitur yang tersedia dalam program.

Fungsi Setiap Menu:
1. Tambahkan Koleksi Item → input data item baru (nama, kategori, ukuran, warna, brand, tahun).
2. Tampilkan Daftar Item → menampilkan seluruh data koleksi dalam bentuk tabel rapi.
3. Cari (ID/Nama) → mencari item tertentu berdasarkan ID atau sebagian nama
4. Ubah Data Koleksi → mengedit data item yang sudah ada.
5. Hapus Koleksi → menghapus item dari daftar koleksi dengan konfirmasi.
6. Filter Koleksi → menampilkan data sesuai kategori atau tahun tertentu.
7. Keluar dari Program → program selesai

<img width="416" height="462" alt="image" src="https://github.com/user-attachments/assets/15de34cd-7f95-4832-a8fd-5fcd9211c835" />

Pada output tersebut, user memilih menu Tambahkan Koleksi Item sehingga muncul judul bertuliskan "TAMBAHKAN KOLEKSI ITEM" sebagai penanda fitur yang sedang digunakan. Program kemudian meminta input detail koleksi berupa nama, kategori, ukuran, warna, brand/desainer, dan tahun koleksi. Seperti pada output tersebut yaitu Kemeja Flanel, Atasan, S, Abu-Abu, Uniqlo, 2025. Data yang dimasukkan secara otomatis disimpan ke dalam daftar koleksi yang dikelola program. Setelah proses berhasil, ditampilkan konfirmasi "Item ditambahkan." sebagai bukti bahwa data telah tersimpan. Terakhir, muncul instruksi "(Enter untuk kembali ke menu utama)" yang berfungsi sebagai jeda agar user bisa membaca hasil sebelum sistem menampilkan menu utama kembali, sehingga alur penggunaan program tetap jelas.

<img width="922" height="536" alt="image" src="https://github.com/user-attachments/assets/2e1c8ffb-ea8d-4254-9491-4890a778f72c" />

Output di atas ditampilkan ketika user memilih menu Tampilkan Daftar Item. Program menampilkan judul “DAFTAR KOLEKSI” diikuti tabel rapi yang berisi seluruh data koleksi fashion. Setiap item ditampilkan dengan atribut ID, Nama, Kategori, Ukuran, Warna, Brand, dan Tahun, sehingga informasi tersusun jelas dan mudah dibaca. Dari tabel terlihat koleksi awal seperti Jaket Denim, Sneakers Canvas, Kaos Graphic hingga tambahan terbaru Kemeja Flanel. Tampilan tabel ini memudahkan pengguna untuk melihat keseluruhan koleksi sekaligus memastikan data sudah tersimpan dengan benar sebelum kembali ke menu utama.

<img width="534" height="276" alt="image" src="https://github.com/user-attachments/assets/f89a6b17-10cd-4874-a5d9-0201c97bd5a5" />

pada output tersebut, user menuliskan keduanya sekaligus (9 Cardigan Rajut), sehingga sistem tidak dapat mengenali input tersebut. Akibatnya, program menampilkan pesan “Masukkan ID/Nama Produk.” sebagai penanda bahwa format input salah, dan user harus mengulang dengan hanya mengetikkan salah satu, misalnya ID saja (9) atau Nama saja (Cardigan Rajut).

<img width="804" height="299" alt="image" src="https://github.com/user-attachments/assets/3dfbef14-d0bc-4461-8bd7-74301348b590" />

Output di atas muncul ketika user memilih menu Cari (ID/Nama) dan memasukkan input yang benar, yaitu hanya angka ID 9. Program kemudian menampilkan tabel hasil pencarian yang memuat data item dengan ID tersebut. Terlihat bahwa item dengan ID 9 menunjukka detail kategori koleksi tersebut. Tampilan tabel ini menunjukkan bahwa sistem berhasil menemukan dan menampilkan data sesuai input yang diberikan user.

<img width="727" height="432" alt="image" src="https://github.com/user-attachments/assets/040cfb80-f939-4e09-ae8b-ea0874ee62fc" />

Output di atas muncul ketika user memilih menu Ubah Data Koleksi dan memasukkan ID item yang ingin diubah, yaitu 9. Program kemudian menampilkan data lama item tersebut (Cardigan Rajut) dan memberi kesempatan bagi user untuk mengganti setiap atribut. Jika field dibiarkan kosong dan hanya menekan Enter, maka nilai sebelumnya tetap dipertahankan. Pada contoh ini, user mengubah ukuran dari S menjadi L serta warna dari Hijau menjadi Hitam, sedangkan atribut lain tetap sama. Setelah perubahan selesai, program menampilkan pesan konfirmasi “Item berhasil diperbarui.” sebagai tanda bahwa data telah diperbarui dalam sistem.

<img width="405" height="269" alt="image" src="https://github.com/user-attachments/assets/88d798f9-a5ee-4243-8ce1-a619ef0c2df0" />

Output ini muncul saat user memilih menu 5) Hapus Koleksi lalu memasukkan ID 12. Program kemudian mengecek daftar koleksi, tetapi tidak menemukan item dengan ID tersebut. Karena itu, sistem menampilkan pesan di dalam kotak “ID tidak ditemukan.”. Hal ini menjadi penanda bahwa penghapusan gagal dilakukan karena data yang dimaksud memang tidak ada dalam koleksi.

<img width="434" height="303" alt="image" src="https://github.com/user-attachments/assets/88c7cf43-142f-4562-9e07-56eee35db41b" />

Output ini muncul ketika user memilih menu Hapus Koleksi dan memasukkan ID item yang ingin dihapus, yaitu 11. Program menampilkan nama item terkait (Kemeja Flanel) dan memberikan konfirmasi dengan pertanyaan “Yakin hapus (y/n)”. User kemudian mengetikkan y sebagai tanda persetujuan. Setelah itu, sistem menampilkan pesan “Data dihapus.” dalam kotak, yang berarti item tersebut sudah berhasil dihapus dari daftar koleksi. Proses ini memastikan bahwa penghapusan tidak terjadi secara tidak sengaja, karena user diminta konfirmasi terlebih dahulu sebelum data benar-benar dihapus.

<img width="759" height="354" alt="image" src="https://github.com/user-attachments/assets/132cb449-bb43-40cd-9df8-8df1b7c9af94" />

<img width="830" height="475" alt="image" src="https://github.com/user-attachments/assets/4ccc0234-6eaa-4dfc-a29e-90e29dc5ea0c" />

Output ini ditampilkan ketika user memilih menu Filter Koleksi. Program memberikan pilihan untuk melakukan filter, misalnya berdasarkan kategori. Pada output di atas, user memilih opsi “1) Berdasarkan Kategori” lalu mengetikkan kategori Sepatu dan Atasan. Program kemudian menampilkan tabel hasil filter yang hanya berisi item dengan kategori tersebut. Dengan fitur ini, user dapat lebih mudah melihat koleksi tertentu tanpa harus menelusuri seluruh daftar, sehingga pencarian data menjadi lebih cepat dan terarah.

<img width="383" height="396" alt="image" src="https://github.com/user-attachments/assets/661fe86e-0fbc-40ad-9c0c-0af700ccdfab" />

Ketika user memasukkan pilihan di luar menu 1–7, program mendeteksi bahwa input tidak sesuai dengan daftar menu yang tersedia. Karena itu, program menampilkan pesan peringatan “Menu tidak valid. Coba lagi.” seperti pada gambar. Setelah pesan muncul, program tidak berhenti ia tetap berada di dalam perulangan utama dan kembali menampilkan Menu Utama, sehingga user bisa memasukkan pilihan yang benar tanpa harus menjalankan ulang aplikasi.

<img width="455" height="658" alt="image" src="https://github.com/user-attachments/assets/5d17d960-d8d3-4874-9500-47c1d3b2b9f7" />

Output ini muncul saat user memilih menu 7) Keluar dari Program. Program menampilkan pesan penutup berupa kotak berisi teks “Terima kasih. Program selesai.” yang menandakan bahwa seluruh proses telah dihentikan dengan benar. Setelah itu, sistem menampilkan informasi dari Maven berupa status BUILD SUCCESS, total waktu eksekusi program, dan waktu selesai dijalankan. Hal ini menunjukkan bahwa program tidak mengalami error dan berhasil ditutup secara normal sesuai perintah user.

1. Package com.mycompany.koleksifashion.model

- Isi: Item.java

- Fungsi: Package ini merepresentasikan Model pada arsitektur MVC.

- Model berisi class yang mendefinisikan data atau entitas yang digunakan dalam aplikasi, beserta atribut dan method dasar.

- Contohnya: Item.java menyimpan informasi tentang koleksi fashion (misalnya: id, nama, kategori, ukuran, warna, brand, tahun).

- Peran: Menjadi representasi data utama yang diproses aplikasi.
