# 🦀 Krabat Isyarat

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)](#)

Game edukasi untuk belajar Bahasa Isyarat Indonesia (SIBI), dibungkus jadi mini game supaya belajarnya nggak terasa seperti belajar.

## Apa itu Krabat Isyarat?

Krabat Isyarat adalah aplikasi Android yang mengajak kamu belajar SIBI lewat kamus visual, mini game tebak isyarat, dan sistem level. Ditemani karakter Crabi, kamu belajar alfabet, angka, dan kosakata dasar sambil main — bukan sambil menghafal dari buku.

Cocok untuk siapa saja: anak-anak yang baru mulai mengenal SIBI, remaja yang penasaran, sampai orang dewasa yang ingin lebih memahami cara berkomunikasi dengan teman-teman Tuli.

## Fitur

- **Kamus Isyarat Interaktif** — alfabet, angka, dan kosakata dasar SIBI
- **Mini Game Tebak Isyarat** — latihan mengenali gerakan lewat permainan
- **Sistem Level & Poin** — materi bertahap, makin lama makin menantang
- **Crabi** — karakter pendamping yang menemani proses belajarmu

## Download

📱 [**Unduh APK v1.0.1**](https://github.com/Raka-Mahendra/Krabat-Isyarat/releases/download/v1.0.1/Kravat.Isyarat.apk)

Setelah diunduh, izinkan instalasi dari sumber tidak dikenal di pengaturan Android kamu, lalu install seperti biasa.

## Screenshot

<p float="left">
  <img src="assets/home.jpeg" width="250" alt="Halaman utama"/>
  <img src="assets/kamus.jpeg" width="250" alt="Kamus isyarat"/>
  <img src="assets/game.jpeg" width="250" alt="Mini game"/>
</p>

---

## Untuk Developer

Krabat Isyarat dibangun sebagai aplikasi web yang di-bundle jadi Android lewat [Capacitor](https://capacitorjs.com/).

**Tech stack:**
- HTML/JS (folder `www/`)
- Capacitor untuk wrapping ke Android
- Android Studio untuk build & signing APK

**Menjalankan project secara lokal:**

```bash
git clone https://github.com/Raka-Mahendra/Krabat-Isyarat.git
cd Krabat-Isyarat
npm install
npx cap sync android
npx cap open android
```

Dari situ, project bisa dibuka dan di-build lewat Android Studio.

### Kontribusi

Ada ide fitur baru, nemu bug, atau mau nambah kosakata isyarat? Kontribusi sangat terbuka. Lihat [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan lengkapnya sebelum bikin pull request.

## Lisensi

Proyek ini menggunakan [Apache License 2.0](LICENSE). Singkatnya: bebas dipakai, dimodifikasi, dan disebarluaskan — termasuk untuk keperluan komersial — selama kamu menyertakan notice hak cipta asli dan mencantumkan perubahan yang kamu buat pada file yang dimodifikasi.

---

Dibuat untuk mendukung komunikasi yang lebih inklusif. 🤟
