# Mangerport

**Mangerport** adalah aplikasi berbasis PHP untuk mengelola data layanan dalam format tabel, termasuk fitur pencarian, pengurutan, dan ekspor/impor CSV.

## Fitur

- **Pengelolaan Layanan**: Tambah, edit, dan hapus layanan dengan detail seperti server, nama layanan, port, nama database, IP tujuan, port tujuan, status, dan keterangan.
- **Pencarian dan Pengurutan**: Cari data berdasarkan kolom tertentu dan urutkan hasil pencarian.
- **Ekspor dan Impor CSV**: Ekspor data ke format CSV dan impor data dari file CSV.

## Struktur Folder

- `services_app/`
  - `db/` - Folder untuk menyimpan file database SQLite.
  - `includes/` - Berisi file PHP untuk koneksi database dan fungsi umum.
  - `templates/` - Berisi file template untuk header dan footer.
  - `action/` - Berisi file PHP untuk aksi CRUD dan fitur ekspor/impor.

## Pengaturan Database

File `db_connect.php` mengatur koneksi ke database SQLite dan memastikan tabel `services` ada dengan kolom yang diperlukan:

- `svr`
- `namaservice`
- `port`
- `dbname`
- `ip_tujuan`
- `port_tujuan`
- `status`
- `keterangan`

## Cara Menggunakan

1. **Clone Repository**
   ```bash
   git clone https://github.com/sawangx64/mangerport.git
   cd mangerport
 

2. **Siapkan Database**
   - Pastikan SQLite sudah terinstal di server Anda.
   - File database SQLite akan otomatis dibuat jika belum ada.

3. **Konfigurasi**
   - Sesuaikan pengaturan database di file `includes/db_connect.php` jika diperlukan.

4. **Jalankan Aplikasi**
   - Akses aplikasi melalui server web yang mendukung PHP.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan fork repository ini dan buat pull request dengan deskripsi perubahan yang Anda buat.

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat [LICENSE](LICENSE) untuk detail lebih lanjut.

## Author

- **Sawangx64** - [GitHub Profile](https://github.com/sawangx64)

## Kontak

Jika Anda memiliki pertanyaan atau membutuhkan bantuan, jangan ragu untuk menghubungi saya melalui [email](mailto:sawangx64@gmail.com).
