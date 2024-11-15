Nama : Hilmy Syaddad Ramzy

NIM : 312210162

TI22A1

=============Tabel Abnormal dari Proyek Sistem Informasi Manufakturing==============

![Cuplikan layar_15-11-2024_10052_www perplexity ai](https://github.com/user-attachments/assets/26fce522-d597-4383-ac92-fe02ce44cfaf)

Contoh Anomali dan Redundansi

Anomali Penyisipan: Jika ada pemasok baru, misalnya PT. Santosa dengan kode pemasok P55, informasi ini hanya dapat dimasukkan jika sudah ada produk yang dipasok. Hal ini menyebabkan kesulitan dalam menambahkan data pemasok baru tanpa harus menambahkan data produk terlebih dahulu.

Anomali Pengubahan: Jika lokasi pemasok dengan kode P22 diubah dari Bogor ke Bekasi, tetapi tidak semua baris yang berisi kode P22 diperbarui, akan terjadi ketidakkonsistenan data. Misalnya, satu baris mungkin masih mencantumkan lokasi Bogor.

Anomali Penghapusan: Ketika menghapus data barang tertentu, misalnya Gearbox A, data pemasok yang terkait juga ikut terhapus. Ini dapat menyebabkan hilangnya informasi penting tentang pemasok tersebut.

=====Tabel Normalisasi=====

Tabel 1NF (First Normal Form)

Tabel ini memenuhi syarat bahwa setiap kolom berisi nilai atomik dan setiap baris adalah unik.

![Cuplikan layar_15-11-2024_10554_www perplexity ai](https://github.com/user-attachments/assets/2a1098be-5dfa-4b36-a39d-b5b696d29a48)

Tabel 2NF (Second Normal Form)

Tabel ini memenuhi syarat dari 1NF dan semua atribut non-kunci bergantung sepenuhnya pada kunci primer.

![Cuplikan layar_15-11-2024_1088_www perplexity ai](https://github.com/user-attachments/assets/317406dc-7ec1-4511-870c-162ea425fc3d)

Tabel Pemasok:

![Cuplikan layar_15-11-2024_10937_www perplexity ai](https://github.com/user-attachments/assets/a31b59cd-5ccb-4b2e-8fe7-c7a2ed4d8e76)

Tabel 3NF (Third Normal Form)

Tabel ini memenuhi syarat dari 2NF dan tidak ada ketergantungan transitif antar atribut non-kunci.

Tabel Produk:

![Cuplikan layar_15-11-2024_101042_www perplexity ai](https://github.com/user-attachments/assets/4a69b589-e053-455d-bdb1-3019ab5ddf90)

Tabel Harga:

![Cuplikan layar_15-11-2024_101211_www perplexity ai](https://github.com/user-attachments/assets/707cec16-a6e9-4f3d-99ca-9a00c5c3a122)

Tabel Pemasok:

![Cuplikan layar_15-11-2024_101248_www perplexity ai](https://github.com/user-attachments/assets/0411918b-e666-4583-a7d8-21ab088488e1)

Tabel Lokasi:

![Cuplikan layar_15-11-2024_101339_www perplexity ai](https://github.com/user-attachments/assets/1a8c6cea-a5fb-468e-b22d-604fbe0deaf8)

Dengan normalisasi ini, kita mengurangi redundansi dan menghindari anomali yang terjadi pada tabel abnormal sebelumnya.











