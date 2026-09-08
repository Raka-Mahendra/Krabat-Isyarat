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

---

## Untuk Developer

Krabat Isyarat dibuat di **Scratch** dan di-package jadi APK Android lewat [TurboWarp Packager](https://packager.turbowarp.org/) + [Capacitor](https://capacitorjs.com/).

**Tech stack:**
- Scratch project — `krabat-isyarat.sb3` (source utama, di root repo)
- [TurboWarp](https://turbowarp.org/) — editor untuk buka & edit `.sb3` (lebih cepat dan lebih banyak fitur dibanding editor Scratch resmi, dan tetap kompatibel)
- TurboWarp Packager — export project jadi build web (masuk ke folder `www/`)
- Capacitor + Android Studio — bungkus hasil export jadi APK

**Alur kontribusi:**

1. Clone repo ini
2. Buka `krabat-isyarat.sb3` lewat [Scratch offline editor](https://scratch.mit.edu/download) atau [TurboWarp](https://turbowarp.org/editor) (tinggal drag file `.sb3` ke browser)
3. Edit project sesuai kebutuhan, lalu simpan/export ulang jadi `.sb3` dengan nama yang sama
4. Kalau perubahanmu perlu di-build ulang jadi APK untuk ditest, pakai [TurboWarp Packager](https://packager.turbowarp.org/) untuk export project ke HTML/JS, lalu:
   ```bash
   # salin hasil export ke folder www/, lalu:
   npx cap sync android
   npx cap open android
   ```
5. Build & test APK lewat Android Studio

### Kontribusi

Ada ide fitur baru, nemu bug, atau mau nambah kosakata isyarat? Kontribusi sangat terbuka. Lihat [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan lengkapnya sebelum bikin pull request.

## Lisensi

Proyek ini menggunakan [Apache License 2.0](LICENSE). Singkatnya: bebas dipakai, dimodifikasi, dan disebarluaskan — termasuk untuk keperluan komersial — selama kamu menyertakan notice hak cipta asli dan mencantumkan perubahan yang kamu buat pada file yang dimodifikasi.

---

Dibuat untuk mendukung komunikasi yang lebih inklusif.
