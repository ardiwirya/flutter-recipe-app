# Resep Makanan — Flutter Recipe App

Aplikasi katalog resep makanan, dibuat sebagai submission kelas [Belajar Membuat Aplikasi Flutter untuk Pemula](https://www.dicoding.com/academies/159) — Dicoding. Submission ini mendapat rating **5/5**.

## Preview

![Screencapture](/images/Screenshot.png)

## Tentang Aplikasi

Aplikasi ini menampilkan daftar resep makanan dan minuman yang dapat dicari dan difilter berdasarkan kategori, lengkap dengan rating dan fitur tandai favorit. Dibangun dengan Flutter, sehingga satu basis kode yang sama dapat berjalan di berbagai platform.

## Fitur

- Daftar resep dengan gambar, kategori, dan rating
- Pencarian resep berdasarkan nama
- Filter berdasarkan kategori (Makanan Utama, Minuman, dsb.)
- Tandai resep sebagai favorit
- Navigasi antar halaman (daftar resep → detail resep)
- Layout responsif, menyesuaikan ukuran layar mobile maupun desktop/web

## Platform yang Didukung

Proyek ini dikonfigurasi untuk berjalan di enam target platform dari satu basis kode Dart yang sama:

`Android` · `iOS` · `Web` · `Windows` · `macOS` · `Linux`

## Aspek Teknis

- Kombinasi **Stateless Widget** (untuk komponen statis seperti layout kartu resep) dan **Stateful Widget** (untuk state pencarian, filter, dan status favorit).
- **Navigation** antar minimal dua halaman (daftar resep dan detail resep).
- Layout dibangun agar tidak overflow dan tetap rapi di berbagai ukuran layar.

## Menjalankan Proyek

1. Install dependencies

   ```bash
   flutter pub get
   ```

2. Jalankan aplikasi (pilih device/emulator yang tersedia)

   ```bash
   flutter run
   ```

## Build untuk Web

Karena proyek ini juga menyasar platform web, aplikasi dapat di-build menjadi aset statis dan di-deploy ke layanan hosting seperti Firebase Hosting, Netlify, atau Vercel:

```bash
flutter build web
```

Hasil build akan tersedia di folder `build/web`, siap diunggah ke layanan hosting pilihan.
