# Kartu Keluarga Extractor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Google Apps Script](https://img.shields.io/badge/Made%20with-Google%20Apps%20Script-blue.svg)](https://developers.google.com/apps-script)

Aplikasi berbasis Google Apps Script yang memungkinkan ekstraksi data dari Kartu Keluarga (KK) Indonesia menggunakan teknologi AI. Unggah gambar KK, dapatkan data terstruktur, dan simpan ke Google Spreadsheet secara otomatis.

![Demo KK Extractor](https://via.placeholder.com/800x450.png?text=KK+Extractor+Demo)

## 🌟 Fitur Utama

- 📋 Ekstraksi otomatis data dari gambar Kartu Keluarga
- 🔍 Validasi dokumen untuk memastikan gambar adalah Kartu Keluarga yang valid
- 📊 Visualisasi statistik demografis (jenis kelamin, agama, status perkawinan, dll)
- 🔎 Pencarian cepat berdasarkan NIK, nama, atau nomor KK
- 📂 Penyimpanan gambar KK ke Google Drive
- 📈 Penyimpanan data KK terstruktur ke Google Spreadsheet
- 📱 Antarmuka responsif yang dapat diakses dari perangkat mobile
- 📝 Pencatatan log aktivitas untuk audit

## 🚀 Cara Menggunakan

### Persyaratan

- Akun Google
- Akses ke Google Drive dan Google Sheets
- Google Apps Script Editor

### Instalasi

1. Buka [Google Apps Script](https://script.google.com/) dan buat proyek baru
2. Copy-paste file berikut ini ke proyek Anda:
   - `Code.gs`
   - `Index.html`
   - `JavaScript.html`
   - `CSS.html`
3. Deploy aplikasi sebagai web app
   - Klik `Deploy > New deployment`
   - Pilih `Web app`
   - Setel akses sesuai kebutuhan Anda
   - Klik `Deploy`
4. Salin URL aplikasi yang diberikan dan akses aplikasi

### Konfigurasi

1. Buka aplikasi dan navigasikan ke tab `Pengaturan`
2. Masukkan ID Google Spreadsheet tempat data akan disimpan
3. Masukkan URL API ekstraksi data KK (opsional jika Anda menggunakan API eksternal)
4. Simpan pengaturan

## 📊 Contoh Penggunaan

### Ekstraksi Data KK

1. Unggah gambar KK melalui antarmuka drag-and-drop atau tombol unggah
2. Sistem akan memproses gambar dan menampilkan hasil ekstraksi
3. Data secara otomatis disimpan ke Google Spreadsheet yang telah dikonfigurasi

### Analisis Statistik

1. Navigasikan ke tab `Statistik`
2. Lihat distribusi demografi berbasis data yang telah diekstraksi
3. Gunakan tombol refresh untuk memperbarui data statistik

### Pencarian Data

1. Navigasikan ke tab `Cari Data`
2. Masukkan nomor KK, NIK, atau nama untuk mencari
3. Sistem akan menampilkan hasil yang cocok dari database

## 🧱 Struktur Proyek

- `Code.gs`: Berisi logika backend dan fungsi utama aplikasi
- `Index.html`: File HTML utama untuk antarmuka pengguna
- `JavaScript.html`: Berisi kode JavaScript untuk interaktivitas aplikasi
- `CSS.html`: Berisi stylesheet untuk tampilan aplikasi

## 🤝 Kontribusi

Kontribusi selalu dipersilakan! Jika Anda ingin berkontribusi:

1. Fork repositori ini
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📜 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.
