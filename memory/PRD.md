# PRD — Salinan Laporan SIMFONI ASN
Permintaan asli: salin kode dari https://simfoni-fresh.preview.emergentagent.com/mag/index.html#lampx10 tanpa mengubah apa pun, kecuali judul 3.5 dipindah ke halaman berikutnya.

## Implementasi (2026-06)
- Disalin persis ke /app/frontend/public/mag/: index.html, mag.css, screen.css, paged.polyfill.js, img/ (semua gambar)
- Satu-satunya perubahan: `<h2 id="s28">` diberi `style="break-before:page"`
- Dibandingkan per halaman dengan sumber: 107 halaman, tidak ada perbedaan

## Backlog
- Tombol Unduh PDF/DOCX/IDML memanggil /api/mag/* yang belum ada di backend ini
