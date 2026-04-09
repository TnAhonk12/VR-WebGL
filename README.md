# VR WebGL (WebXR - Unity)

## Deskripsi
Fitur Virtual Reality (VR) berbasis web menggunakan Unity WebGL dengan tampilan panorama 360 derajat.

Aplikasi memungkinkan pengguna menjelajahi lingkungan virtual menggunakan sensor perangkat atau gesture sentuh.

---

## Teknologi
- Unity (WebGL)
- WebXR Device API
- JavaScript (sensor integration)

---

## Struktur Project
- `/fixVR` → Berisi hasil build WebGL (deploy-ready)
- `/Assets` → Asset Unity (scene, script, material)
- `/ProjectSettings` → Konfigurasi project Unity

---

## Cara Kerja
- Scene menggunakan panorama 360°
- Kamera berada di dalam environment
- Arah pandangan dikontrol oleh gyroscope atau gesture sentuh

---

## Sensor (Gyroscope)
- Digunakan untuk navigasi VR secara real-time
- Pada beberapa perangkat (terutama iOS), diperlukan interaksi awal (tap) untuk mengaktifkan sensor

---

## Fallback Control
Jika gyroscope tidak tersedia atau tidak diizinkan:
- User dapat menggunakan gesture swipe untuk navigasi

---

## Cara Menjalankan
1. Buka link demo melalui browser mobile
2. Berikan izin sensor jika diminta
3. Gerakkan perangkat atau swipe untuk melihat 360°

---

## Integrasi dengan Flutter
VR dapat dijalankan di dalam WebView Flutter dengan memuat URL aplikasi.

---

## Catatan
- Tidak semua browser mendukung WebXR secara penuh
- Disarankan menggunakan browser modern (Chrome / Safari)
- Fallback control disediakan untuk menjaga kompatibilitas

---

## Demo

[Link Demo](https://lustrous-dragon-3a2d54.netlify.app/)
