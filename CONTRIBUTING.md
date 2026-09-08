# Kontribusi untuk Krabat Isyarat

Makasih sudah tertarik buat berkontribusi! Berikut alur singkatnya.

## Cara mulai

1. Fork repository ini
2. Clone hasil fork kamu: `git clone https://github.com/<username-kamu>/Krabat-Isyarat.git`
3. Buat branch baru: `git checkout -b fitur/nama-fitur-kamu`
4. Buka file `krabat-isyarat.sb3` di root repo lewat [Scratch offline editor](https://scratch.mit.edu/download) atau [TurboWarp](https://turbowarp.org/editor) — keduanya bisa langsung buka file `.sb3`
5. Edit project, lalu simpan ulang sebagai `.sb3` dengan nama file yang sama

Kalau perubahanmu perlu ditest dalam bentuk APK, lihat panduan build di README bagian "Untuk Developer" (TurboWarp Packager → `www/` → Capacitor → Android Studio).

## Sebelum bikin pull request

- Pastikan file `.sb3` bisa dibuka tanpa error di Scratch/TurboWarp
- Kalau ikut update build APK (folder `www/`, `android/`), pastikan itu juga tetap bisa di-build (`npx cap sync android`)
- Jelaskan perubahan yang kamu buat di deskripsi PR — cukup singkat, yang penting jelas
- Kalau menambahkan kosakata isyarat baru, sertakan sumber referensinya (misalnya rujukan SIBI resmi)
- Satu PR untuk satu perubahan/fitur, biar lebih gampang direview

## Melaporkan bug atau mengusulkan fitur

Buka [Issues](https://github.com/Raka-Mahendra/Krabat-Isyarat/issues) dan jelaskan:
- Apa yang terjadi vs. apa yang diharapkan (untuk bug)
- Kenapa fitur itu berguna (untuk usulan fitur)
- Screenshot atau video kalau relevan

## Kode etik

Bersikap baik dan hormat ke sesama kontributor. Proyek ini dibuat untuk mendukung komunikasi yang inklusif — jadi mari mulai dari cara kita berdiskusi di sini juga.
