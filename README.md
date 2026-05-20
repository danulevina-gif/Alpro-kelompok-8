# 📚 Sistem Manajemen Perpustakaan Sederhana

Program Python berbasis terminal untuk mengelola data buku perpustakaan sederhana.  
Program ini dibuat sebagai Proyek Akhir (UAS) mata kuliah Algoritma dan Pemrograman II.

---

# 👥 Anggota Kelompok

| Nama | NIM |
|---|---|
| Muhammad Toro Haikal | 2530801086 |
| Muhammad Adhitya Ramadan | 2530108099 |

---

# 🎯 Deskripsi Program

Sistem Manajemen Perpustakaan Sederhana adalah program berbasis terminal yang digunakan untuk mengelola data buku dan transaksi peminjaman.

Program memiliki fitur:
- Menambahkan buku
- Menampilkan daftar buku
- Mencari buku
- Meminjam buku
- Mengembalikan buku
- Menampilkan jumlah buku

Program dibuat menggunakan bahasa pemrograman Python dengan penerapan konsep-konsep dasar Algoritma dan Pemrograman II.

---

# ⚙️ Konsep Python yang Digunakan

| Konsep | Implementasi |
|---|---|
| List Multidimensi | Riwayat peminjaman |
| Tuple | Identitas buku `(kode, tahun)` |
| Dictionary | Penyimpanan data buku |
| Rekursif | Fungsi pencarian buku |
| Exception Handling | Validasi input user |

Konsep tambahan:
- Looping
- Function
- Conditional
- Dictionary iteration

---

# 🚀 Cara Menjalankan Program

## 1. Clone Repository

```bash
git clone https://github.com/username/nama-repository.git
```

## 2. Masuk ke Folder Project

```bash
cd nama-repository
```

## 3. Jalankan Program

```bash
python main.py
```

---

# 💻 Versi Python

Program dibuat menggunakan:

```text
Python 3.x
```

---

# 📦 Library yang Digunakan

Program ini tidak menggunakan library eksternal.

---

# 📋 Struktur Menu Program

```text
=== SISTEM PERPUSTAKAAN ===
1. Tambah Buku
2. Tampilkan Buku
3. Cari Buku
4. Pinjam Buku
5. Kembalikan Buku
6. Jumlah Buku
7. Keluar
```

---

# 🧩 Tabel Pembagian Fungsi

| Nama Fungsi | Deskripsi | Input | Output | Konsep Python | Penanggung Jawab |
|---|---|---|---|---|---|
| `tambah_buku()` | Menambahkan data buku baru | kode, judul, stok | data buku baru | dictionary, tuple, exception handling | Muhammad Toro Haikal |
| `tampilkan_buku()` | Menampilkan seluruh buku | data buku | daftar buku | dictionary, looping | Muhammad Toro Haikal |
| `cari_buku_rekursif()` | Mencari buku dengan rekursif | judul buku | data buku | rekursif | Muhammad Toro Haikal |
| `jumlah_buku()` | Menghitung total buku | data buku | total buku | function, len() | Muhammad Toro Haikal |
| `pinjam_buku()` | Melakukan peminjaman buku | kode buku | transaksi peminjaman | list multidimensi, dictionary | Muhammad Adhitya Ramadan |
| `kembalikan_buku()` | Mengembalikan stok buku | kode buku | update stok | list multidimensi, dictionary | Muhammad Adhitya Ramadan |
| `validasi_input()` | Validasi input angka | input user | integer | exception handling | Muhammad Adhitya Ramadan |
| `menu_utama()` | Mengatur alur program | pilihan menu | alur program | looping, conditional | Muhammad Adhitya Ramadan |

---

# 🖥️ Contoh Output Program

```text
=== SISTEM PERPUSTAKAAN ===
1. Tambah Buku
2. Tampilkan Buku
3. Cari Buku
4. Pinjam Buku
5. Kembalikan Buku
6. Jumlah Buku
7. Keluar

Pilih menu:
```

---

# ⚠️ Penanganan Error

Program sudah menggunakan exception handling untuk:
- Input selain angka
- Buku tidak ditemukan
- Stok buku habis

---

# 📌 Catatan

Program ini dibuat untuk memenuhi tugas Proyek Akhir (UAS)
mata kuliah Algoritma dan Pemrograman II.
