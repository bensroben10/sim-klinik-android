# SIM Klinik Android Wrapper

APK ringan berbasis WebView untuk:
https://sim-klinik.krianapps.biz.id/

Tujuan:
- satu codebase: aplikasi web tetap menjadi sumber utama
- splash screen segera tampil
- WebView menggunakan cache normal agar pembukaan berikutnya lebih cepat
- JavaScript dan localStorage/DOM storage aktif karena aplikasi SIM Klinik membutuhkannya
- tombol Back Android bekerja seperti navigasi browser
- link di luar domain aplikasi dibuka di browser Android

Build APK melalui GitHub Actions:
1. Upload seluruh folder proyek ini ke repository GitHub.
2. Push ke branch `main`.
3. Buka tab Actions.
4. Pilih workflow `Build SIM Klinik APK`.
5. Setelah selesai, ambil artifact `SIM-KLINIK-debug`.
