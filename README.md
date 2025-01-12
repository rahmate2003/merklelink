1. MerkleLink - React + Vite

MerkleLink adalah aplikasi berbasis web yang dibuat dengan React dan Vite yang memungkinkan pengguna untuk membuat halaman profil dengan menampilkan berbagai link penting dalam satu tempat. Aplikasi ini mirip dengan **Linktree**.

2. Fitur

- **Mudah untuk menambahkan link**: Pengguna dapat menambahkan beberapa link yang akan ditampilkan di halaman profil mereka.
- **Desain responsif**: Aplikasi ini dirancang untuk tampil dengan baik di berbagai perangkat, termasuk ponsel. 
- **Dukungan ikon**: Setiap link dapat menampilkan ikon untuk memudahkan navigasi.

3. Setup Proyek

3.1. Persiapkan Proyek
Buat proyek baru dengan menggunakan template Vite dan React:

npm create vite@latest merklelink --template react
cd merklelink
npm install

3.2. Instalasi Dependensi Tambahan
Untuk menambah ikon dan styling, instal react-icons dan dependensi lain yang diperlukan:

npm install react-icons

3.3. Jalankan Proyek
Setelah menginstal dependensi, Anda dapat menjalankan aplikasi dengan perintah berikut:

npm run dev

Aplikasi akan berjalan di http://localhost:3000.

4. Struktur Proyek

/src
  /components
    LinkItem.jsx  # Menampilkan satu link
    Header.jsx    # Menampilkan header profil
  App.jsx
  index.css      # Styling untuk aplikasi

5. Mengembangkan Aplikasi

1. Menambahkan Link: Anda dapat menambahkan link dengan menambahkan objek baru di dalam array links di file App.jsx.
2. Kustomisasi Profil: Ubah gambar profil dan informasi di komponen Header.jsx untuk menyesuaikan dengan preferensi Anda.

6. Dependencies

* react-icons: Ikon untuk tombol dan elemen visual lainnya.
* vite: Alat pengembangan cepat dengan Hot Module Replacement (HMR).

7. Lisensi

Proyek ini menggunakan lisensi MIT.
