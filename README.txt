KOZENI — MOBILE WIDTH + JSON EXPORT FIX

Perbaikan:
- Dashboard tidak lagi melebar keluar layar HP.
- Kondisi Keuangan dan Insight membungkus teks panjang dengan benar.
- Seluruh halaman dikunci agar tidak mengalami horizontal overflow.
- Export JSON di APK memakai Android Share sheet terlebih dahulu.
- Di browser biasa tetap menggunakan download JSON.
- Jika perangkat sama sekali tidak mendukung file export, JSON dicopy ke clipboard sebagai fallback.

Untuk APK:
Upload/replace file ini di repo GitHub Kozeni lalu commit.
GitHub Actions akan build APK baru otomatis.
