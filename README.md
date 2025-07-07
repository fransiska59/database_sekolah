# 📚 Database Sekolah Sederhana

Ini adalah contoh database sederhana untuk sistem informasi sekolah. Database ini dibuat menggunakan MySQL dan mencakup lima tabel utama: siswa, guru, mata_pelajaran, kelas, dan nilai.

---

## 🗂 Struktur Tabel

### 1. siswa
Menyimpan data siswa.
- id_siswa: ID siswa (primary key)
- nama: Nama lengkap siswa
- nis: Nomor Induk Siswa
- kelas: Kelas siswa
- alamat: Alamat tempat tinggal

### 2. guru
Menyimpan data guru.
- id_guru: ID guru (primary key)
- nama: Nama lengkap guru
- nip: Nomor Induk Pegawai
- mapel: Mata pelajaran yang diajar

### 3. mata_pelajaran
Menyimpan data mata pelajaran.
- id_mapel: ID mapel (primary key)
- nama_mapel: Nama mata pelajaran
- kode_mapel: Kode unik mapel

### 4. kelas
Menyimpan informasi kelas.
- id_kelas: ID kelas (primary key)
- nama_kelas: Nama kelas
- wali_kelas: Nama wali kelas

### 5. nilai
Menyimpan data nilai siswa.
- id_nilai: ID nilai (primary key)
- id_siswa: FK ke tabel siswa
- id_mapel: FK ke tabel mata_pelajaran
- nilai: Nilai akhir

---

## 💾 Cara Import Database

1. Buka aplikasi *phpMyAdmin* atau MySQL client lainnya.
2. Buat database baru dengan nama sekolah.
3. Import file database.sql dengan cara:
   - Klik tab Import
   - Pilih file database.sql
   - Klik Go

---

## 📌 Catatan
Database ini hanya contoh sederhana untuk keperluan pembelajaran. Dapat dikembangkan lebih lanjut dengan fitur-fitur seperti login, jadwal pelajaran, kehadiran, dan lainnya.
