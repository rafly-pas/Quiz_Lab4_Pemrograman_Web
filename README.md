# Todo List – React.js

Aplikasi To-Do List frontend menggunakan React.js (Vite) untuk Kuis Praktikum.

## Fitur
- Menampilkan daftar tugas (data dummy)
- Melihat detail tugas (`/todo/:id`)
- Menambah tugas lewat modal form
- Memperbarui tugas lewat modal form
- Menghapus tugas dengan konfirmasi + notifikasi (toast)
- Perubahan tampil langsung tanpa reload (React State + Context)

## Struktur Data
```js
{ id, title, description, priority, deadline, status }
```

## Cara Menjalankan
```bash
npm install
npm run dev
```
Buka http://localhost:5173

## Screenshot
> Tambahkan screenshot hasil aplikasi di sini (letakkan gambar di folder `screenshots/`).

| Halaman | Screenshot |
|---|---|
| Daftar Todo | ![list](screenshots/list.png) |
| Tambah Todo | ![add](screenshots/add.png) |
| Detail Todo | ![detail](screenshots/detail.png) |
| Update Todo | ![update](screenshots/update.png) |
| Konfirmasi Hapus | ![delete](screenshots/delete.png) |
