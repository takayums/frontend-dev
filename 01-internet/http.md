# HTTP

Http merupakan alat komunikasi antara server dan klien. Http bergantung pada TCP/IP untuk mendapatkan reques dan response dari client dan server.

### Http 0.9

Http pertama kali dibuat pada tahun 1991 dan hanya bisa menggunakan GET request dengan version http 0.9. Pada versi ini hanya bisa menerima response HTML saja.

### Http 1.0

Setelah itu pada tahun 1996 muncul version http 1.0. pada versi ini memiliki method baru yaitu POST dan HEAD. Dan tidak hanya meresponse HTML saja melainkan bisa untuk gambar, video, teks, dll. Dan response header tetap menggunakan ASCII. Kelemahan pada version ini yaitu tidak dapat menggunakan banyak permintaan koneksi. Jadi setiap koneksi haru membutuhkan TCP baru. Dampak dari ini yaitu koneksi semakin lambat jika permintaan yang ada terlalu banyak.

### Three way Handshake

Pada proses ini ada tiga tahapan yang harus dilalui sebelum aplikasi / web menerima data yaitu SYN -> SYN ACK -> ACK. Pada pembaruan ini juga masih memiliki kekurangan yaitu masih memiliki koneksi lemah dan untuk lokasi client tidak ada.

### HTTP 1.1

Ini adalah perubah update besar pada HTTP karena terdapat penambahan fitur baru yaitu:

- Adanya mehtod tambahan PUT, OPTIONS, DELETE, dan PATCH.
- Identifikasi host tidak ada melainkan menjadi wajib ada.
- Koneksi presisten artinya akan ada sampai client menutup koneksi tersebut.
- Peplining yaitu client melakukan beberapa permintaan tanpa harus menunggu response dalam koneksi yang sama. untuk mengetahui koneksi pertama selesai maka dibutuhkannya yaitu Content-Lenth.
- Transer terpish jika konten dinamis.
- Autentikai proxy dan digest.
- Chacing.
- Byte Range.
- Karakter.
- Bahasa.
- Client Cookies.
- Dukungan kompresi.
- New status code.

### SDY

Merupakan protokol yang dibuat oleh Google pada tahun 2009. dan memiliki fitur yaitu multiplexing, compression, prioritas dan keamanan dll. SDY ini akan menjadi inspirasi untuk pembuatan HTTP 2. Google menggabungkan SDY ke HTTPS 1 untuk membantu pengembangan.

### HTTP 2

HTTP 2 dibuat pada tahun 2015 untuk melakukan perbaikan dari versio HTTP 1. Fitur baru dalam HTTP 2 ini yaitu:

- Binary bukan Textual (Frames dan Streams)
- Multiplexing
- Header compression using HPACK
- Server push
- Request Prioritas
- Security
