# Portfolio Website 2025

## Deskripsi

Website portofolio personal statis berbasis `HTML`, `CSS`, dan `JavaScript`. Tampilan telah dirapikan dengan pendekatan UI yang lebih konsisten: layout lebih terstruktur, hierarki visual lebih jelas, dan tema retro pastel yang terinspirasi dari referensi desain.

## Fitur

- Layout retro-card dengan border tegas dan warna pastel hangat
- Responsif untuk desktop, tablet, dan mobile
- Navigasi section yang lebih rapi
- Showcase project, pendidikan, pengalaman, sertifikat, dan kontak
- Form kontak yang membuka draft Gmail secara otomatis

## Struktur File

- `index.html` untuk struktur halaman utama
- `styles.css` untuk styling utama
- `assets/` untuk gambar, ikon, dan media pendukung

## Cara Menjalankan

Karena ini project statis, ada 2 cara termudah:

### Opsi 1 - Buka langsung

Klik dua kali file `index.html`, lalu website akan terbuka di browser.

### Opsi 2 - Jalankan local server

Masuk ke folder project, lalu jalankan command berikut di terminal:

```powershell
py -m http.server 5500
```

Jika command `py` tidak tersedia, coba:

```powershell
python -m http.server 5500
```

Setelah itu buka browser dan akses:

```text
http://localhost:5500
```

## Catatan

- Project ini tidak perlu `npm install`
- Tidak perlu build process
- Cocok dijalankan langsung sebagai website statis

## Kustomisasi

- Edit konten di `index.html`
- Ubah warna, layout, dan komponen di `styles.css`
- Ganti gambar pada folder `assets/` sesuai kebutuhan

## Kredit

Dibuat oleh Nadia Ayu R
