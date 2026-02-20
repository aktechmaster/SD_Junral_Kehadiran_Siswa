# 📱 Smart Attendance System v2.0
> Sistem Manajemen Kehadiran Siswa Modern berbasis Web dengan integrasi Google Sheets API.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/naereen/StrapDown.js/graphs/commit-activity)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Platform](https://img.shields.io/badge/Platform-Web-blue)

Sistem Jurnal Kehadiran Siswa ini dirancang dengan antarmuka **High-Fidelity UX** menggunakan font *Plus Jakarta Sans* dan desain kartu modern. Sangat cocok untuk instansi pendidikan yang menginginkan digitalisasi presensi secara cepat, akurat, dan ringan.

---

## ✨ Fitur Utama
* **Modern Card Interface**: Setiap nama siswa dipisahkan dalam kartu untuk meningkatkan keterbacaan.
* **Dynamic Data Sync**: Mengambil daftar kelas dan siswa secara *real-time* dari Google Sheets.
* **One-Tap Interaction**: Input kehadiran (Hadir, Sakit, Izin, Alpha) yang dioptimalkan untuk perangkat layar sentuh (Mobile Friendly).
* **Persistent Login**: Fitur penyimpanan email otomatis di browser untuk efisiensi waktu guru.
* **Smart Loading Animation**: Indikator proses yang halus saat memuat data dan mengirim laporan.

---

## 🛠️ Spesifikasi Teknologi
| Komponen | Teknologi |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom Grid & Flexbox) |
| **Typography** | Plus Jakarta Sans (Google Fonts) |
| **Icons** | Font Awesome 6.4.0 |
| **Backend** | Google Apps Script (GAS) |
| **Database** | Google Sheets API |

---

## 🚀 Cara Pemasangan (Deployment)

1.  **Clone Repositori**
    ```bash
    git clone [https://github.com/username/attendance-system.git](https://github.com/username/attendance-system.git)
    ```
2.  **Konfigurasi Google Sheets**
    * Buat Google Sheet baru dengan tab untuk daftar siswa.
    * Buka menu **Extensions > Apps Script**.
    * Masukkan kode backend Apps Script milik Anda.
    * Deploy sebagai **Web App** dan setel akses ke "Anyone".
3.  **Update Endpoint**
    * Buka file `index.html`.
    * Cari variabel `SCRIPT_URL`.
    * Ganti dengan URL hasil deploy Web App Anda.

---

## 🎨 Panduan Status Kehadiran
Sistem menggunakan kode warna standar untuk memudahkan verifikasi visual:
* 🟢 **H** - Hadir (Success Green)
* 🟡 **S** - Sakit (Warning Orange)
* 🔵 **I** - Izin (Info Blue)
* 🔴 **A** - Alpha (Danger Red)

---

## 📸 Tampilan Antarmuka
*(Anda bisa mengunggah screenshot aplikasi Anda di sini)*
> **Catatan:** Desain menggunakan pendekatan *Mobile-First*, memberikan pengalaman terbaik bagi guru yang melakukan absen langsung melalui smartphone.

---

## 🤝 Kontribusi
Kontribusi selalu terbuka! Silakan lakukan *fork* repositori ini dan kirimkan *pull request* dengan perubahan yang Anda usulkan.

---

## 📄 Lisensi
Didistribusikan di bawah lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

Developed with ❤️ by **aktechmaster**
