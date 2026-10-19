# KIMPUL TWEAKS V2

Proyek sumber aplikasi Android KIMPUL TWEAKS.

- Workflow GitHub Actions menggunakan Node.js 24, Java 17, Android SDK 35, dan Gradle 8.9.
- `minSdk` disetel ke Android API 24 karena dependensi `dev.rikka.shizuku:api:13.1.5` memerlukan minimal API 24.
- Perangkat Android dengan API di bawah 24 tidak dapat memasang aplikasi ini.

## Build APK
1. Unggah isi proyek dan `.github/workflows/android.yml` ke repositori GitHub.
2. Jalankan workflow **Build KIMPUL TWEAKS APK** di tab Actions.
3. Jika berhasil, unduh artifact `KIMPUL-TWEAKS-v2-debug`.

APK hanya siap diunduh jika workflow selesai tanpa error.
