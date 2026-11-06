# Uang Manager

Aplikasi pengelola uang berbasis web/PWA.

## Fitur
- Tiga kategori awal: Uang Makan, Uang Jajan, Uang Kuliah.
- Tambah kategori sendiri dan atur nama serta saldo awal.
- Catat pemasukan dan pengeluaran per kategori.
- Edit transaksi kapan saja: kategori, jenis, nominal, keterangan, dan tanggal.
- Hapus transaksi; saldo kategori dan total otomatis dihitung ulang.
- Riwayat transaksi dan penyimpanan lokal.
- Service worker untuk dukungan offline setelah situs pertama kali dibuka.

## Upload ke GitHub Pages
1. Ekstrak ZIP ini.
2. Upload **isi folder** ke root repository GitHub. Jangan upload ZIP-nya saja.
3. Pastikan `index.html`, `manifest.json`, `sw.js`, dan folder `icons` berada langsung di root repository.
4. Buka Settings > Pages.
5. Pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.
6. Buka URL GitHub Pages melalui HTTPS. Di Chrome Android, buka menu ⋮ lalu pilih Install app atau Add to Home screen jika tersedia.

## Catatan
Data disimpan di localStorage perangkat/browser dan tidak otomatis tersinkron antarperangkat. Jangan hapus data situs sebelum membuat cadangan.
