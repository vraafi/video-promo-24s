**Masalah**
Video promosi 24 detik butuh 6 kartu teks, transisi, musik senyap, dan resolusi 1280x720. Tidak ada berkas video final; yang tersedia hanya skrip pembuat dan dokumentasi.

**Yang Dibangun**
Saya membangun `buat_video.py` (1091 B) untuk merangkai kartu teks, transisi, dan musik senyap secara terprogram. `README.md` (819 B) mendokumentasikan cara pakai dan parameter. Hasilnya adalah pipeline yang dapat direproduksi untuk video promosi 24 detik.

**Keputusan Teknis**
Saya memisahkan logika pembuatan video ke dalam skrip Python dan menaruh instruksi di README. Saya memilih musik senyap agar tidak bergantung pada aset berhak cipta. Saya menetapkan resolusi 1280x720 dan durasi 24 detik sebagai parameter tetap. Saya tidak menambahkan dependensi di luar yang diperlukan.

**Bukti**
QC lapis kode dan media lulus. Waktu QC 0,69 detik. Temuan 0. Berkas kode: 1 Python, 1 JSON, 12 lain, 0 JS, 0 Lua.

**Batasan**
Tidak ada video final yang diuji. Tidak ada pengguna, klien, atau metrik eksternal. Angka QC hanya mencakup lapis kode dan media, bukan hasil tontonan.