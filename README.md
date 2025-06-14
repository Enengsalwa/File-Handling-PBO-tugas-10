File Handling adalah kemampuan program untuk berinteraksi dengan file di sistem operasi. Ini mencakup operasi dasar seperti membuat, membaca, menulis, mengubah, dan menghapus file. Dalam pemrograman, file handling memungkinkan aplikasi menyimpan data secara permanen, mengakses informasi dari file eksternal, dan berbagi data antar program. Proses ini melibatkan pembukaan file, pemrosesan data, dan penutupan file dengan penanganan error yang tepat untuk mengatasi masalah seperti file tidak ditemukan atau akses yang ditolak. File handling sangat penting untuk aplikasi yang memerlukan penyimpanan data jangka panjang atau pertukaran informasi dengan sistem lain.

1. CSVReader.java
Kelas untuk membaca file CSV dengan fungsi utama:
Membuka dan membaca file CSV baris per baris
Parsing data dengan delimiter (biasanya koma)
Mengkonversi setiap baris menjadi array string atau objek
Menangani exception seperti FileNotFoundException dan IOException
Menutup file setelah selesai dibaca

2. CSVWriter.java
Kelas untuk menulis data ke file CSV dengan fungsi utama:
Membuat atau membuka file CSV untuk ditulis
Mengkonversi data dari array/list menjadi format CSV
Menambahkan delimiter dan menangani karakter khusus (escape characters)
Menulis header dan data baris per baris
Flush dan close file untuk memastikan data tersimpan

3. FileMerge.java
Kelas untuk menggabungkan beberapa file dengan fungsi utama:
Membaca multiple file secara berurutan atau bersamaan
Menggabungkan konten berdasarkan kriteria tertentu (append, merge by column, dll)
Menangani perbedaan format atau struktur file
Menulis hasil gabungan ke file output baru
Optimasi memory untuk file berukuran besar
