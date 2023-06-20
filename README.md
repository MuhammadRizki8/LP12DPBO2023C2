# LP12DPBO2023C2

##### Saya Muhammad Rizki NIM 2107922 mengerjakan Latihan 12 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

### Alasan Pakai MVP
dari kode awal, Controller berfungsi sebagai pengendali input pengguna dan menghubungkan antara Model dan View layaknya presenter. Game.java bertindak sebagai presenter utama yang mengatur alur permainan dan berinteraksi dengan Controller, Model, dan View. Handler.java bertanggung jawab untuk mengelola objek-objek dalam permainan dan menangani logika permainan.<br>
1. Model:
- GameInterface.java: Mendefinisikan antarmuka untuk permainan.
- GameObject.java: Representasi objek dalam permainan.
- Player.java: Model untuk pemain dalam permainan.
- Target.java: Model untuk target dalam permainan.
2. View:
- Display.java: Menampilkan tampilan grafis permainan kepada pengguna.
3. Presenter:
- Controller.java: Mengontrol input pengguna dan berinteraksi dengan model dan tampilan.
- Game.java: Berperan sebagai presenter utama yang mengatur alur permainan dan menghubungkan antara Controller, Model, dan View.
- Handler.java: Mengelola objek-objek dalam permainan dan menangani logika permainan.

### Perbedaan setelah TMD
arsitektur programnya berubah menjadi MVVM karena Arsitektur MVVM lebih cocok dalam pengembangan game ini. Dengan pemisahan yang jelas antara Model, View, dan ViewModel, proses coding dapat dilakukan secara terpisah pada bagian-bagian tersebut. Ini memungkinkan untuk pengerjaan yang paralel, meningkatkan efisiensi, dan mempercepat proses pengembangan.
