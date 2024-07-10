# 📚 Bookshelf API
Proyek ini adalah submission untuk kelas **Belajar Membuat Aplikasi Back-End untuk Pemula** di Dicoding. Pada tugas ini, peserta diminta untuk membangun sebuah **Bookshelf API** dengan menggunakan framework Hapi dan memenuhi berbagai kriteria yang telah ditetapkan.

## 📝 Deskripsi
Bookshelf API adalah aplikasi back-end yang memungkinkan pengguna untuk mengelola data buku dengan melakukan operasi CRUD (Create, Read, Update, Delete). API ini dirancang untuk menangani berbagai permintaan terkait buku, mulai dari menambahkan buku baru hingga mencari buku berdasarkan query parameters. Aplikasi ini juga telah menerapkan **CORS** untuk keamanan dan menggunakan **ESLint dengan Airbnb style guide** untuk menjaga konsistensi kode.

## 🚀 Fitur Utama
* **Menyimpan Buku:** Menambahkan buku baru dengan detail seperti nama, tahun terbit, penulis, dan status bacaan
* **Menampilkan Buku:** Menampilkan daftar seluruh buku yang tersimpan.
* **Menampilkan Detail Buku:** Melihat informasi detail buku berdasarkan ID.
* **Mengubah Data Buku:** Memperbarui informasi buku yang sudah ada.
* **Menghapus Buku:** Menghapus buku dari daftar berdasarkan ID.
* **CORS:** Mengatur CORS untuk mengizinkan akses dari domain lain.
* **ESLint:** Menggunakan **Airbnb style guide** untuk memastikan konsistensi dan kualitas kode JavaScript

## 🔧 Fitur Tambahan
* Query Parameters untuk **GET** /books:
    * `?name=`: Mencari buku berdasarkan nama.
    * `?reading=`: Menampilkan buku berdasarkan status bacaan (0 atau 1)
    * `?finished=`: Menampilkan buku berdasarkan status selesai dibaca (0 atau 1)

## 👨🏻‍💻 Tech Stack
* **Backend:** **`Node.js`** dengan framework **`Hapi`**
* **Database:** Data buku disimpan dalam memori (untuk keperluan submission)
* **Dependency Management:** **`npm`**, **`nanoid`** untuk pembuatan ID unik
* **Linting:** **`ESLint`** dengan **Airbnb style guide** untuk konsistensi kode
* **Testing:** Postman untuk pengujian otomatis dan validasi fitur API

## ⚙️ Cara Menjalankan Aplikasi
1. Clone Repository:
    ```sh
    git clone https://github.com/ChristiantoKape/submission_bookshelf_api
    cd submission_bookshelf_api
    ```
2. Instalasi Dependensi:
    ```sh
    npm install
    ```
3. Menjalankan Aplikasi:
    ```sh
    npm run start
    ```
    Aplikasi akan berjalan pada port `9000`.
4. Untuk Pengembangan:
    Jika ingin menggunakan `nodemon` selama pengembangan, jalankan:
    ```sh
    npm run start-dev
    ```
    
### Author
[Christianto Kurniawan Priyono](https://www.linkedin.com/in/chriskape/)

### Rating & Certificate
![ads](https://i.ibb.co.com/PTFjMd6/Screenshot-2024-07-11-021135.png)
[Sertifikat Kompetensi Kelas Belajar Membuat Aplikasi Back-End untuk Pemula](https://www.dicoding.com/certificates/0LZ06NM6KZ65)