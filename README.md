# Jobsheet-2 Node.Js-Module System dan Command Line Arguments
### Sistem Modul Node.js
Sistem modul dalam Node.js memungkinkan pengembang untuk mengorganisasi kode mereka menjadi unit yang lebih kecil dan dapat digunakan kembali yang disebut "modul." Beberapa konsep kunci:

- **CommonJS**: Node.js mengikuti spesifikasi CommonJS, mendefinisikan cara modul didefinisikan, diimpor, dan digunakan dalam lingkungan Node.js.
- **Modul**: Unit kode independen dalam Node.js, setiap file JavaScript dianggap sebagai modul yang dapat digunakan dan diimpor dalam modul lain.
- **Fungsi `require()`**: Mengimpor modul lain ke dalam kode Node.js.
- **`module.exports`**: Objek untuk mengekspor kode atau data dari suatu modul.
- **Modul Bawaan**: Node.js menyertakan modul bawaan seperti `fs` dan `http` yang dapat diimpor dan digunakan.

### Node Package Manager (NPM)
Node Package Manager (NPM) adalah alat pengelola paket yang digunakan untuk mengelola, menginstal, dan mendistribusikan paket perangkat lunak dalam proyek-proyek Node.js. Konsep utama melibatkan paket, `package.json`, instalasi paket, dan penerbitan paket.

1. **Paket (Package)**: Unit perangkat lunak terdiri dari kode JavaScript dan konfigurasi.
2. **`package.json`**: Berkas konfigurasi proyek Node.js mencatat dependensi dan informasi proyek.
3. **Instalasi Paket**: Pengembang menginstal paket dengan `npm install`.
4. **Publikasi Paket**: Pengembang dapat menerbitkan paket mereka sendiri ke repositori NPM.

### Command Line Arguments pada Node.js
Command line arguments pada Node.js memungkinkan pengguna memberikan input tambahan saat menjalankan skrip. `process.argv` adalah array berisi informasi cara skrip dijalankan dan argumen yang diberikan oleh pengguna.

Argumen ini berguna untuk mengkonfigurasi atau mengoperasikan program Node.js sesuai kebutuhan aplikasi. 

Dalam bahasa pemrograman, ini dikenal sebagai "argument parsing." 

### Tugas: Membuat Aplikasi Buku Catatan
Berikut langkah-langkah untuk membuat aplikasi buku catatan:

#### 1. Membuat catatan baru
- Buka terminal dan jalankan program `app.js` dengan perintah `node app.js tambah --judul="Catatan 1" --isi="Isi catatan 1"`.
- Perhatikan bahwa file `catatan.json` akan dibuat dengan data catatan yang ditambahkan.

#### 2. Menghapus catatan
- Jalankan program `app.js` dengan perintah `node app.js hapus --judul="Catatan 1"`.
- Lihat hasilnya dan perhatikan bahwa catatan dengan judul "Catatan 1" telah dihapus.

#### 3. Menampilkan semua catatan (list)
- Jalankan program `app.js` dengan perintah `node app.js list`.
- Lihat hasilnya dan perhatikan daftar semua catatan yang ada.

#### 4. Membaca catatan (read)
- Jalankan program `app.js` dengan perintah `node app.js read --judul="Catatan 1"`.
- Lihat hasilnya dan perhatikan isi dari catatan dengan judul "Catatan 1".
