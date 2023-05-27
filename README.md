# TUGAS-2-MAHASISWA
    Pertama, kita membuat kelas Mahasiswa dengan atribut Nama, NIM, dan Jurusan. Atribut Jurusan adalah objek dari kelas Jurusan.

    Selanjutnya, dalam kelas Mahasiswa, kita memiliki metode tampilkan_info() yang digunakan untuk menampilkan informasi nama, NIM, dan nama Jurusan mahasiswa.

    Kemudian, kita membuat kelas Jurusan dengan atribut NamaJurusan dan DaftarMahasiswa. Atribut DaftarMahasiswa adalah sebuah list yang akan menyimpan objek-objek Mahasiswa yang terdaftar dalam jurusan.

    Dalam kelas Jurusan, kita memiliki metode tambah_mahasiswa(mahasiswa) yang digunakan untuk menambahkan objek Mahasiswa ke dalam daftar DaftarMahasiswa.

    Selain itu, terdapat juga metode tampilkan_daftar_mahasiswa() yang akan menampilkan daftar mahasiswa yang terdaftar dalam jurusan. Metode ini akan memanggil metode tampilkan_info() dari setiap objek Mahasiswa dalam DaftarMahasiswa.

    Terakhir, kita membuat kelas Universitas dengan atribut NamaUniversitas dan DaftarJurusan. Atribut DaftarJurusan adalah sebuah list yang akan menyimpan objek-objek Jurusan yang ada di universitas.

    Dalam kelas Universitas, kita memiliki metode tambah_jurusan(jurusan) yang digunakan untuk menambahkan objek Jurusan ke dalam daftar DaftarJurusan.

    Selain itu, terdapat juga metode tampilkan_daftar_jurusan() yang akan menampilkan daftar jurusan yang ada di universitas. Metode ini akan memanggil atribut NamaJurusan dari setiap objek Jurusan dalam DaftarJurusan.

    Untuk penggunaan program, Andi membuat objek Universitas dengan nama "XYZ University" menggunakan kode xyz_university = Universitas("XYZ University").

    Selanjutnya, Andi membuat objek Jurusan dengan nama "Teknik Informatika" menggunakan kode teknik_informatika = Jurusan("Teknik Informatika"). Objek ini kemudian ditambahkan ke dalam Universitas XYZ dengan menggunakan metode tambah_jurusan(jurusan) pada objek Universitas XYZ.

    Andi juga membuat objek Mahasiswa dengan nama "Kalian masing" dan NIM "Kalian masing" menggunakan kode mahasiswa1 = Mahasiswa("Kalian masing", "NIM kalian masing", teknik_informatika). Objek ini kemudian ditambahkan ke dalam Jurusan Teknik Informatika dengan menggunakan metode tambah_mahasiswa(mahasiswa) pada objek Jurusan Teknik Informatika.

    Terakhir, Andi menampilkan daftar jurusan yang ada di Universitas XYZ menggunakan metode tampilkan_daftar_jurusan() pada objek Universitas XYZ.

    Andi juga menampilkan daftar mahasiswa yang terdaftar dalam Jurusan Teknik Informatika di Universitas XYZ menggunakan metode `tampilkan_daftar_mahasiswa
