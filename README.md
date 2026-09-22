# Presensi — Unduhan Siap Pakai (APK & EXE)

Repo ini **hanya berisi berkas siap pakai** dari aplikasi **Presensi** — aplikasi
presensi (kehadiran) dengan **pengenalan wajah** untuk guru, murid, dan karyawan:

- 🪟 **`presensi.exe`** — Windows x64, portable (tanpa instalasi)
- 🤖 **`Presensi-<versi>-android-unsigned.apk`** — Android

Kode sumber, dokumentasi, dan riwayat pengembangan ada di repo utama:
**https://github.com/arwankhoiruddin/presensi**

---

## ⬇️ Unduhan — v1.0.4 (terbaru)

| Platform | Berkas | Ukuran | Unduh |
| --- | --- | --- | --- |
| Windows x64 | `presensi.exe` | 117 MB | [**⬇ Unduh EXE**](https://github.com/arwankhoiruddin/presensi-release/releases/download/v1.0.4/presensi.exe) |
| Android | `Presensi-1.0.4-android-unsigned.apk` | 61 MB | [**⬇ Unduh APK**](https://github.com/arwankhoiruddin/presensi-release/releases/download/v1.0.4/Presensi-1.0.4-android-unsigned.apk) |

Halaman rilis lengkap (semua berkas + catatan rilis):
**https://github.com/arwankhoiruddin/presensi-release/releases**

### Checksum SHA-256

```
8e91909b01cf6ab272c805cab288abca28ea25c349297d404c994fd6216a5dbe  presensi.exe
53ddf5791b4b335e956284b9416bc6a936eb3f943d29ac1163b6c8b9d7c15e76  Presensi-1.0.4-android-unsigned.apk
```

Verifikasi (opsional):

```bash
shasum -a 256 presensi.exe                       # macOS / Linux
certutil -hashfile presensi.exe SHA256           # Windows (PowerShell/cmd)
```

---

## 🖥️ Cara memasang — Windows

1. Unduh **`presensi.exe`** dari tabel di atas.
2. Klik ganda berkasnya — tidak perlu instalasi.
3. Izinkan akses **kamera** saat diminta.
4. Bila Windows Defender menampilkan *"unrecognized app"* (berkas belum
   ditandatangani secara digital), pilih **More info → Run anyway**.

Aplikasi bekerja **offline** penuh; koneksi internet hanya diperlukan untuk
sinkronisasi data ke server madrasah.

## 📱 Cara memasang — Android

1. Unduh berkas **APK**.
2. Buka berkasnya dari pengelola berkas/notifikasi.
3. Izinkan **"Install unknown apps"** untuk aplikasi yang membuka berkas itu.
4. APK ini **unsigned**, sehingga Google Play Protect akan menampilkan
   peringatan — pilih **Install anyway** lalu beri izin kamera.

---

## ℹ️ Catatan

- Berkas di repo ini **identik** dengan aset rilis di repo utama (nama, isi, dan
  checksum sama) — repo ini hanya memudahkan menemukan berkas rilis tanpa
  kode sumber.
- Repo ini **tidak** memuat kode sumber, hanya hasil build.
- Aplikasi ini dilisensikan **MIT** — lihat
  [LICENSE repo utama](https://github.com/arwankhoiruddin/presensi/blob/main/LICENSE).
