# 🎸 Band Name Generator

Proyek ini adalah aplikasi web sederhana yang dibuat dengan **Node.js, Express.js, dan EJS**.  
Aplikasi ini menghasilkan nama band acak dengan menggabungkan **kata sifat (adjective)** dan **kata benda (noun)** yang dipilih secara random.

---

## 🎯 Overview
- Halaman utama menampilkan pesan selamat datang.
- Pengguna dapat menekan tombol **Generate Name** untuk membuat nama band baru.
- Nama band dibentuk dari kombinasi **adjective + noun** secara acak.
- Menggunakan **EJS template engine** untuk menampilkan hasil.

---

## ✨ Fitur
- Generate nama band acak dengan sekali klik.
- Tampilan dinamis menggunakan **EJS**.
- Routing sederhana menggunakan **Express.js**.
- Mendukung partials EJS (`header.ejs` dan `footer.ejs`).

---

## 🛠️ Teknologi yang Digunakan
- **Node.js** → Runtime JavaScript.
- **Express.js** → Framework web backend.
- **EJS (Embedded JavaScript Templates)** → Template engine untuk render HTML.
- **Body-parser** → Middleware untuk menangani data form.

---

## 📂 Struktur Proyek
```
band-name-generator/
│── index.js # File utama server Express
│── views/
│ ├── solution.ejs # Template utama
│ └── partials/
│ ├── header.ejs
│ └── footer.ejs
│── public/ # (optional) untuk static files (CSS, JS, Images)
│── package.json
```

## 🚀 Cara Instalasi & Menjalankan
1. **Clone Repository**
```bash
git clone https://github.com/AkbarAj09/band-generator-name.git 
```
2. **Install Dependencies**
```
npm install 
```
3. **Jalankan Server**
```bash
nodemon index.js
```
Route akan jalan di **localhost:3000**

## 🖥️ Routes
```bash
GET / → Menampilkan halaman utama (welcome atau hasil generate).
POST /submit → Menghasilkan nama band acak.
```

## 👨‍💻 Author
Edited by **Akbar Abdurrahman**