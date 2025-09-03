
# SIPKADES v1.3
SIPKADES — Sistem Informasi Penilaian Kinerja Aparatur Desa (Desa Keling).
Single-file static web app (index.html) + assets; dapat di-deploy di GitHub Pages / Vercel (static).

Fitur utama v1.3:
- Login (username/password) dengan LocalStorage
- Registrasi admin awal jika belum ada user (default admin created)
- Admin dapat membuat/hapus pengguna
- Role-based dashboard (BUMDes, Pemdes, BPD, Admin)
- Penilaian 360°, unggah rekap kehadiran (Excel/CSV), export slip & data ke Excel

Catatan keamanan:
- Password disimpan sebagai hash SHA-256 di LocalStorage (bukan plaintext) — tetap hanya untuk testing/demo.
- Untuk produksi, gunakan backend & database yang aman.
