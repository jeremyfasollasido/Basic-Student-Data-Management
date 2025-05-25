# Sistem Manajemen Data Mahasiswa

---

Aplikasi desktop sederhana untuk manajemen data mahasiswa, dilengkapi dengan sistem login dan fungsionalitas CRUD (Create, Read, Update, Delete) data presensi dan nilai. Aplikasi ini dibangun menggunakan pustaka grafis Tkinter dan mengelola data dalam format CSV.

## ✨ Fitur

* **Sistem Login:** Pengguna harus login dengan username dan password yang tersimpan di `login.csv`.
* **Manajemen Data Mahasiswa (CRUD):**
    * **Show All Data:** Menampilkan semua data mahasiswa dari `presensi.csv` dalam tabel.
    * **Delete Data:** Menghapus baris data mahasiswa yang dipilih dari tabel.
    * **Add Data:** Menambahkan data mahasiswa baru ke `presensi.csv`, dengan validasi untuk mencegah duplikasi NIM atau Nama.
    * **Replace Data:** Mengganti data NIM dan Nama mahasiswa yang sudah ada.
* **Manajemen Nilai:**
    * **Input Nilai:** Memasukkan nilai ujian (Ujian 1, 2, 3) untuk mahasiswa berdasarkan NIM dan Nama, dengan validasi nilai (0-100).
    * **Calculate Avg Nilai:** Menghitung rata-rata nilai ujian untuk mahasiswa tertentu.
* **Antarmuka Pengguna Grafis (GUI):** Dibangun menggunakan pustaka Tkinter untuk interaksi yang mudah.
* **Penyimpanan Data CSV:** Data login dan presensi disimpan dalam file CSV (`login.csv` dan `presensi.csv`).

## 🚀 Teknologi yang Digunakan

* **Python 3**
* **Tkinter:** Pustaka standar Python untuk membuat antarmuka pengguna grafis.
* **`csv` module:** Untuk membaca dan menulis file CSV.
* **`tkinter.messagebox`:** Untuk menampilkan pesan informasi dan error.
* **`tkinter.ttk`:** Untuk widget bergaya modern (misalnya `Treeview` untuk tabel).

## 💻 Instalasi & Pengaturan

Untuk menjalankan aplikasi ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1.  **Pastikan Python Terinstal:**
    Pastikan Anda memiliki Python 3 terinstal di sistem Anda. Anda dapat mengunduhnya dari [python.org](https://www.python.org/).

2.  **Kloning Repositori (jika dari Git):**
    Jika proyek ini ada di GitHub, kloning repositori:
    ```bash
    git clone [https://github.com/](https://github.com/)[YourUsername]/[YourRepositoryName].git
    cd [YourRepositoryName]
    ```
    Atau unduh file proyek secara langsung.

3.  **Pastikan Dependensi Terinstal:**
    Tkinter dan modul `csv` biasanya sudah termasuk dalam instalasi standar Python. Anda tidak perlu menginstal pustaka tambahan untuk ini.

4.  **Siapkan File CSV:**
    Aplikasi ini membutuhkan dua file CSV di direktori yang sama dengan `main.py`:
    * `login.csv`: Berisi data username dan password untuk login.
        * Contoh format:
            ```csv
            admin,password123
            user,qwerty
            ```
    * `presensi.csv`: Berisi data mahasiswa (NIM, Nama, Nilai Ujian 1, Nilai Ujian 2, Nilai Ujian 3).
        * Contoh format (penting: header harus sama persis seperti ini):
            ```csv
            NIM,NAMA,Nilai Ujian 1,Nilai Ujian 2,Nilai Ujian 3
            12345,Budi Santoso,80,75,90
            67890,Siti Aminah,90,85,95
            ```
        * Pastikan file ini memiliki header yang persis seperti yang disebutkan (`NIM`, `NAMA`, `Nilai Ujian 1`, `Nilai Ujian 2`, `Nilai Ujian 3`).

5.  **Jalankan Aplikasi:**
    Buka terminal atau command prompt, navigasikan ke direktori tempat file `main.py` berada, lalu jalankan:
    ```bash
    python main.py
    ```

## 🌐 Penggunaan

1.  Aplikasi akan menampilkan jendela login. Masukkan username dan password yang ada di `login.csv`.
2.  Setelah login berhasil, Anda akan masuk ke menu utama.
3.  Gunakan tombol-tombol yang tersedia untuk:
    * Melihat semua data mahasiswa.
    * Menambah data mahasiswa baru.
    * Menghapus data mahasiswa.
    * Mengganti data mahasiswa.
    * Menginput nilai ujian mahasiswa.
    * Menghitung rata-rata nilai mahasiswa.
    * Keluar dari aplikasi.

## 📸 Tangkapan Layar (Opsional)

Anda dapat menambahkan tangkapan layar (screenshots) di sini untuk memberikan gambaran visual aplikasi Anda.

---
[Gambar Jendela Login]
*Deskripsi singkat tentang apa yang ditunjukkan tangkapan layar ini.*

[Gambar Menu Utama]
*Deskripsi singkat lainnya.*

[Gambar Tampilan Data Mahasiswa]
*Deskripsi singkat lainnya.*
---

## 👋 Berkontribusi

Kontribusi dipersilakan! Jika Anda memiliki saran atau menemukan isu, silakan buka *issue* atau kirim *pull request*.

## 📄 Lisensi

Proyek ini tidak memiliki lisensi eksplisit yang ditentukan. Anda dapat menambahkan lisensi pilihan Anda (misalnya MIT, GPL) di sini.

## 📧 Kontak

Nama Anda - [Email Anda/Tautan Profil LinkedIn/Tautan Portofolio]
