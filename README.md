# 🏫 Sistem E-Hadir Guru (Face Recognition)

Sistem kehadiran berasaskan web yang menggunakan kecerdasan buatan (AI) untuk mengecam wajah, pengesahan lokasi (Geofencing), dan pelaporan masa nyata.

## 🚀 Ciri-Ciri Utama
- **Imbasan Wajah Auto:** Menggunakan `face-api.js` (Tiny Face Detector) yang dioptimumkan untuk peranti mudah alih.
- **Geofencing:** Hanya membenarkan kehadiran jika guru berada dalam radius sekolah.
- **PIN Harian:** Langkah keselamatan tambahan sebelum kamera diaktifkan.
- **Dashboard Pentadbir Real-time:** Memaparkan kehadiran serta-merta menggunakan Firebase Firestore.
- **Export Excel:** Membolehkan admin memuat turun laporan bulanan/harian.

## 📂 Struktur Fail
- `index.html`: Laman utama untuk guru (Imbasan Wajah).
- `admin.html`: Laman rahsia pentadbir (Daftar Staf & Laporan).
- `/models`: Folder yang mengandungi model AI face-api.js.

## 🛠️ Cara Akses (GitHub Pages)
1. **Laman Guru:** `https://[username].github.io/[repo-name]/`
2. **Laman Pentadbir:** `https://[username].github.io/[repo-name]/admin.html`

## ⚠️ Nota Penting
- Pastikan anda membenarkan akses **Kamera** dan **Lokasi (GPS)** pada pelayar web.
- Gunakan pelayar **Chrome** atau **Safari** versi terkini untuk prestasi terbaik.