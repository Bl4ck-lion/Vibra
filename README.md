# Vibra Music 🎵

Pemutar musik untuk Android dengan playlist, antrean, dan chat pribadi.

🌐 **Website:** https://vibra-music.vercel.app  
📥 **Unduh APK:** https://github.com/Bl4ck-lion/Vibra/releases

## Fitur

- Cari dan putar musik.
- Buat, impor, dan ekspor playlist.
- Simpan lagu favorit dan kelola antrean.
- Geser lagu ke kanan untuk menambahkan ke playlist atau antrean.
- Chat pribadi dengan kutip/balas pesan.
- Cari percakapan dan tandai chat favorit.

## Instalasi Android

1. Buka halaman **Releases**.
2. Unduh APK dari bagian **Assets** jika rilis sudah tersedia.
3. Buka berkas APK dan ikuti petunjuk instalasi Android.
4. Aktifkan izin notifikasi saat membuka Vibra.

### Informasi APK

| Keterangan | Detail |
|---|---|
| Versi yang disiapkan | 5.3.3 |
| Jenis build | Debug |
| Dukungan perangkat | Universal 32-bit dan 64-bit, ARM dan x86 |
| Android minimum | Android 6.0 |

APK belum diuji pada perangkat Android fisik. Android atau Google Play Protect tetap dapat melakukan pemindaian saat instalasi.

## Verifikasi SHA-256

Setiap rilis menyertakan `SHA256SUMS.txt` untuk memeriksa integritas APK.

**Windows PowerShell:**

    Get-FileHash .\Vibra-5.3.3-debug-universal.apk -Algorithm SHA256

**Linux:**

    sha256sum Vibra-5.3.3-debug-universal.apk

**macOS:**

    shasum -a 256 Vibra-5.3.3-debug-universal.apk

Cocokkan hasilnya dengan checksum pada berkas rilis.

## Catatan

- Koneksi internet diperlukan.
- Tampilan aplikasi dimuat dari website Vibra.
- Notifikasi pesan memerlukan Vibra tetap terbuka; pengiriman push saat aplikasi ditutup belum tersedia.
- Favorit percakapan disimpan per akun pada perangkat yang digunakan.
- Ekspor CSV berisi daftar lagu, bukan berkas audio.

## Tentang repositori

Repositori ini digunakan untuk mendistribusikan APK dan informasi rilis.

**Source code aplikasi, kredensial, data akun, dan kunci penandatanganan tidak dipublikasikan di repositori ini.**
