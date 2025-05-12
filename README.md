# CI/CD Project - Amikom

Contoh proyek implementasi CI/CD berdasarkan materi dari Universitas Amikom.

## ✅ CI Pipeline
- Auto-run on push/pull request to branch `main` atau `master`
- Install dependencies (g++)
- Compile program C++ (`stack.cpp`)
- Jalankan hasil kompilasi (`main`)

## ⚠️ Simulasi Masalah
### 🔀 Konflik Git
- Buat dua branch (`fitur-a` dan `fitur-b`)
- Ubah file `simulasi-konflik.txt` pada baris yang sama
- Merge satu, lalu merge lainnya ➜ munculkan konflik

### 🛠 YAML Rusak
- Hapus indentasi atau ganti `:` dengan `-` di file `ci.yml`
- Push ➜ Pipeline gagal

## 📦 Deployment Manual (CD)
Untuk aplikasi PHP:
- Gunakan VPS (DigitalOcean, Niagahoster, dsb)
- Install: Apache/Nginx, PHP, MySQL
- Jalankan: `git pull` dari server setelah merge
