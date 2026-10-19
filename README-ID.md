# KIMPUL TWEAKS V2

Sumber aplikasi Android KIMPUL TWEAKS. Workflow menggunakan Node.js 24, Java 17, Android SDK 35, dan Gradle 8.9.

Jika file aplikasi diunggah secara datar ke root repositori (`AndroidManifest.xml` dan `MainActivity.java` di root), workflow akan menyiapkan modul `app` secara otomatis sebelum build.

Build APK:
1. Unggah isi proyek dan `.github/workflows/android.yml` ke repositori GitHub.
2. Buka tab Actions dan jalankan workflow.
3. Unduh artifact `KIMPUL-TWEAKS-v2-debug` jika build berhasil.
