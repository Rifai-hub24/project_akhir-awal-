
# 📌 Project Akhir Tahap Awal UKK - Aplikasi Flutter + Laravel

Projek ini merupakan **project akhir tahap awal** dalam rangka persiapan **Uji Kompetensi Keahlian (UKK)**.  
Aplikasi ini menggunakan **Flutter** sebagai frontend (mobile app) dan **Laravel** sebagai backend (API).  

---

## 👤 Identitas
- Nama  : Muhammad Irfan Rifai  
- Sekolah: SMK Negeri 1 Bantul  
- Jurusan: Rekayasa Perangkat Lunak (RPL)  

---

## 🚀 Fitur Utama
- Autentikasi (Register, Login, Logout)  
- Ganti Password  
- CRUD Data (Contoh: To-Do List, Produk, dll)  
- Desain tampilan modern dengan Flutter  

---

## 🛠️ Teknologi yang Digunakan
### Frontend
- [Flutter](https://flutter.dev/) (Dart)  
- State management sederhana dengan `setState`  

### Backend
- [Laravel](https://laravel.com/) (PHP Framework)  
- RESTful API  
- MySQL/MariaDB  

---

## 📱 Dokumentasi (Screenshots)

### 🔐 Autentikasi
- **Login Page**  
  ![Login Page](https://github.com/Rifai-hub24/project_akhir-awal-/blob/06cec47604210687e22b8cf8a69b7f4b67d5aa2e/Screenshot%202025-08-28%20075624.png)

- **Register Page**  
  ![Register Page](docs/screenshots/register.png)

- **Ganti Password**  
  ![Change Password](docs/screenshots/change_password.png)

---

## ⚙️ Cara Menjalankan
### Backend (Laravel)
1. Clone repository ini  
2. Masuk folder `backend/`  
3. Jalankan perintah:
   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   php artisan migrate --seed
   php artisan serve
````

Laravel akan berjalan di `http://127.0.0.1:8000`

### Frontend (Flutter)

1. Masuk folder `frontend/`
2. Jalankan:

   ```bash
   flutter pub get
   flutter run
   ```

   Pastikan device emulator atau HP terkoneksi.

---

## 📝 Catatan

* Project ini masih **tahap awal** dan akan dikembangkan lebih lanjut untuk keperluan **UKK**.
* Backend dan frontend sudah saling terhubung.
* Screenshot disimpan di folder `docs/screenshots/`.

---

## 📌 Lisensi

Projek ini dibuat untuk **pembelajaran** dan **ujian kompetensi**.
Dilarang keras memperjualbelikan tanpa izin.

```

---

Mau saya sekalian bikinkan **struktur folder docs/screenshots/** di project ini biar nanti tinggal isi gambarnya?
```

