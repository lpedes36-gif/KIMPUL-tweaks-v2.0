# KIMPUL TWEAKS V2

Proyek sumber aplikasi Android KIMPUL TWEAKS.

Workflow GitHub Actions memakai Node.js 24 untuk actions yang membutuhkan Node, Java 17, Android SDK 35, dan Gradle 8.9. Workflow akan mencari `settings.gradle` lalu menjalankan `:app:assembleDebug` dari folder proyek yang sesuai, termasuk jika proyek tersimpan di subfolder.

## Build APK
1. Unggah folder proyek ke repositori GitHub dan pastikan workflow `.github/workflows/android.yml` ikut diunggah.
2. Buka tab Actions dan jalankan **Build KIMPUL TWEAKS APK**.
3. Jika berhasil, unduh artifact `KIMPUL-TWEAKS-v2-debug`.

APK belum dianggap berhasil dibuat sampai workflow selesai tanpa error.
