## Masalah

Promo 24 detik butuh video yang cepat dirender dan mudah diperiksa. Enam kartu teks, transisi, musik senyap, dan resolusi 1280x720 harus konsisten. Tanpa skrip yang jelas, waktu habis di pengecekan manual.

## Yang Dibangun

Skrip `buat_video.py` berukuran 1065 B. Skrip ini menyusun enam kartu teks, transisi, dan trek musik senyap ke kanvas 1280x720 selama 24 detik. Berkas tunggal, tanpa dependensi berlebih. Jalankan ulang, hasilnya sama.

## Keputusan Teknis

Kami memilih satu skrip Python kecil daripada pipeline bertingkat. Ukuran 1065 B menjaga ruang kesalahan tetap sempit. Enam kartu diatur berurutan; transisi dan musik ditangani di dalam skrip yang sama. Konfigurasi resolusi dikunci di 1280x720 agar keluaran tidak melenceng.

## Bukti (angka QC)

QC menyelesaikan 1,2 detik dengan 0 temuan. Lapis aktif: kode dan media. Lapis lulus: kode dan media. Rincian kode: py 1, js 0, json 0, lua 0, lain 8.

## Batasan

Video tidak memuat narasi suara, hanya musik senyap. Durasi tetap 24 detik dan resolusi tetap 1280x720. Skrip belum diuji untuk variasi jumlah kartu di luar enam.