
| Profile     | Anggota                     |
| --------- | ----------------------------- |
| **312310632** | Fakhri Afif Muhaimin      |
| **312blabla** | Taufik Hidayat            |
| **312310617** | Fadil Aditya Adzima       |
| **312310608** | Habib Suprayoga           |
| **Mata Kuliah** | Pemrograman Web 2       |

---

```markdown
# 💼 Invoice Management System

Sistem Manajemen Invoice berbasis PHP ini dikembangkan untuk membantu pelaku usaha kecil dan menengah (UKM) dalam mengelola transaksi, data pelanggan, produk, dan pembuatan invoice secara efisien. Aplikasi ini berjalan secara lokal menggunakan XAMPP dan didesain dengan struktur kode yang modular serta mudah dikembangkan.

---

## 🧠 Latar Belakang

Masalah umum yang sering dihadapi UKM adalah pencatatan transaksi yang masih dilakukan secara manual. Hal ini dapat menyebabkan kesalahan data, kehilangan catatan transaksi, serta ketidakteraturan dalam pengelolaan pelanggan dan produk.

Invoice Management System ini hadir sebagai solusi digital sederhana yang dapat digunakan secara offline untuk mencatat, menyimpan, dan mengelola semua proses transaksi penjualan dengan tampilan yang user-friendly.

---

## 🚀 Fitur Lengkap

### 🔐 Autentikasi
- Login dan logout user
- Validasi session pengguna
- Role dasar sebagai admin

### 👥 Manajemen Pelanggan
- Tambah, ubah, hapus, dan lihat daftar pelanggan
- Data pelanggan tersimpan di database MySQL

### 📦 Manajemen Produk
- Tambah, ubah, hapus, dan lihat daftar produk
- Input data seperti nama produk, harga, dan deskripsi

### 🧾 Manajemen Invoice
- Buat invoice baru berdasarkan pelanggan dan produk
- Tampilkan daftar semua invoice yang telah dibuat
- Cetak dan simpan invoice sebagai dokumen digital

### 📊 Dashboard
- Tampilan dashboard dengan informasi ringkas jumlah pelanggan, produk, dan invoice

### 📧 Email Notifikasi (Opsional)
- Menggunakan PHPMailer untuk mengirim invoice melalui email ke pelanggan

---

## 📁 Struktur Folder

```

## 📁 Struktur Folder

```bash
invoice/
├── css/                  # File CSS untuk tampilan aplikasi
├── js/                   # File JavaScript untuk interaksi halaman
├── images/               # Gambar pendukung aplikasi
├── fonts/                # Font tambahan
├── includes/             # File konfigurasi dan fungsi umum PHP
├── functions.php         # Fungsi umum aplikasi
├── class.phpmailer.php   # File library PHPMailer untuk email
├── customer-add.php      # Halaman untuk menambah data pelanggan
├── product-list.php      # Halaman untuk menampilkan daftar produk
├── invoice-create.php    # Halaman untuk membuat invoice baru
├── login.php             # Halaman login pengguna
└── DATABASE FILE/        # Folder berisi file SQL untuk database


````

---

## ⚙️ Teknologi & Tools

- **Bahasa**: PHP (Native)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Email**: PHPMailer
- **Server Lokal**: XAMPP (Apache & MySQL)

---

Berikut adalah versi yang sudah **dirapikan, diperbaiki format markdown-nya**, dan bebas dari kesalahan seperti block code yang tidak ditutup atau penulisan dobel ikon/email:

---

````markdown
## 🛠️ Cara Instalasi

1. **Clone atau Unduh Project**
   ```bash
   git clone https://github.com/FadilAdz/InvoiceWeb.git
````

2. **Letakkan Folder di XAMPP**
   Pindahkan folder hasil clone ke:

   ```
   C:\xampp\htdocs\invoice
   ```

3. **Import Database**

   * Jalankan XAMPP dan buka `phpMyAdmin`
   * Buat database baru, misalnya: `invoice_db`
   * Import file SQL dari folder `DATABASE FILE/`

4. **Sesuaikan Koneksi Database**

   * Edit file koneksi di `includes/config.php` (atau sesuai struktur file kamu)
   * Contoh:

     ```php
     $host = "localhost";
     $user = "root";
     $pass = "";
     $dbname = "invoice_db";
     ```

5. **Jalankan Aplikasi di Browser**
   Akses melalui URL:

   ```
   http://localhost/invoice
   ```

---

## 🔐 Informasi Login

| Role  | Username | Password      |
| ----- | -------- | ------------- |
| Admin | admin    | Password\@123 |

> 📌 Disarankan untuk mengganti username/password default demi keamanan.

---

## 📸 Screenshot Tampilan

> *(Tambahkan screenshot jika ada. Misalnya: halaman login, dashboard, daftar invoice, dsb.)*

---

## 🧾 Catatan Tambahan

* Pastikan modul PHP seperti `mysqli`, `mbstring`, dan `openssl` aktif di XAMPP
* PHPMailer dapat dikonfigurasi menggunakan SMTP Gmail untuk mengirim email otomatis
* Jangan upload file konfigurasi atau kredensial ke repository publik untuk menjaga keamanan

---

