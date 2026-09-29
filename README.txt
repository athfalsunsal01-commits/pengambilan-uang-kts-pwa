PWA PENGAMBILAN UANG & KTS

1. Upload semua isi folder ini ke hosting HTTPS (contoh: GitHub Pages). Jangan upload ZIP apa adanya.
2. Buka URL hosting di HP. URL deployment /exec sudah tertanam sebagai bawaan. Jika alamat web app berubah, tekan Atur link dan tempel URL /exec yang baru.
3. Di Chrome Android: menu ⋮ > Tambahkan ke layar utama / Instal aplikasi.
4. Di Safari iPhone: Bagikan > Tambahkan ke Layar Utama.
5. Tombol "Atur link" memungkinkan mengganti URL /exec tanpa mengubah file di hosting.

PENTING:
- Apps Script Code.gs harus memakai setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL) seperti versi proyek ini.
- Deploy Apps Script dengan akses yang sesuai pengguna. Jika iframe tertahan oleh login/cookie browser, buka URL /exec langsung di browser dan atur akses deployment.
- Service worker hanya menyimpan halaman pembuka, manifest, dan ikon. Data transaksi tetap membutuhkan internet dan tidak disimpan untuk penggunaan offline.
- Ikon PWA dalam paket ini adalah ikon sederhana buatan paket, bukan logo pondok yang berada di Google Drive. Logo pada halaman aplikasi tetap dimuat dari Apps Script.

VERSI MOBILE: toolbar PWA diperkecil dan kartu Riwayat pada Apps Script dibuat vertikal. Ganti juga Index.html pada proyek Apps Script dan deploy ulang agar perbaikan bagian dalam tampil.
