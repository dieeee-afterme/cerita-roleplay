# 🌟 Cerita Roleplay Assets

Selamat datang di repository resmi untuk berbagai custom assets, baju, kendaraan, dan skrip untuk server **Cerita Roleplay**.

## 📁 Struktur Direktori

- `[assets]/` - Berisi berbagai resource visual dan model 3D.
  - `[clothing]/` - Custom EUP / Pakaian untuk berbagai sub-fraksi dan warga.
  - `[vehicles]/` - Custom kendaraan, handling, dan tekstur mobil.
  - `[maps]/` - Custom MLO dan map modifications.
- `[scripts]/` - Skrip kustom atau modifikasi sistem pendukung server.

## 🚀 Cara Pemasangan

1. Pindahkan folder resource (misalnya di dalam `[assets]`) ke dalam folder `resources` di FiveM server Anda.
2. Pastikan file terstruktur dengan benar dan tambahkan baris berikut di file `server.cfg` Anda:
   ```cfg
   ensure [assets]
   ensure [scripts]
   ```
3. Restart server atau jalankan command `refresh` dari konsol, kemudian jalankan mod-nya.

## ✍️ Kontribusi
Gunakan standar *commit message* yang rapi jika ada developer lain yang ingin berkontribusi, contoh:
- `feat: Menambahkan mobil patroli baru`
- `fix: Memperbaiki tekstur jaket yang error`

## 📌 Catatan Tambahan
Jangan lupa selalu catat setiap *update* fitur, mobil, maupun baju terbaru di file `CHANGELOG.md` ya!
