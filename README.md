# Jurnal Absensi Guru

Aplikasi web untuk mencatat dan mengelola jurnal serta absensi kehadiran guru di sekolah.

## Deskripsi
Website ini dibuat untuk mempermudah pencatatan kehadiran guru serta jurnal kegiatan mengajar harian, menggantikan pencatatan manual yang biasanya menggunakan buku fisik.

## Fitur
- Login untuk guru dan sekre
- Input absensi harian guru (hadir, izin, sakit, alpa)
- Input jurnal kegiatan mengajar (mata pelajaran, kelas, materi yang diajarkan)
- Lihat riwayat absensi dan jurnal
- Edit dan hapus data jurnal/absensi
- Rekap laporan absensi per guru/per periode

## Teknologi yang Dipakai
- PHP (native)
- MySQL
- HTML, CSS
- Bootstrap

## Struktur Database
Tabel utama:
- `guru` — data guru (nama, NIP, mata pelajaran)
- `kelas` — data kelas
- `jurnal_mengajar` — data jurnal kegiatan mengajar

## Cara Menjalankan
1. Clone repo ini: git clone https://github.com/Ragabod/jurnalkita5.git
2. Import database dari file `database.sql` ke MySQL
3. Sesuaikan koneksi database di `koneksi.php` (host, user, password, nama database)
4. Jalankan server: php -S localhost:8000
5. Buka `http://localhost:8000` di browser

## Kontributor
- Ragabod
- sevia-dn
- maulanaqubro
- Nevola
