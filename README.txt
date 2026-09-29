PWA PENGAMBILAN UANG & KTS — LOCK MOBILE

1. Ganti Index.html di Apps Script dengan versi dalam tautan terpisah, lalu Deploy > Manage deployments > Edit > pilih versi baru > Deploy. Pertahankan URL /exec yang sudah digunakan.
2. Di repositori GitHub pengambilan-uang-kts-pwa, ganti index.html, sw.js, manifest.webmanifest, dan folder icons dengan file langsung dari ZIP ini (tanpa membuat subfolder). Commit dan Push dari GitHub Desktop.
3. Pastikan GitHub Pages memakai main dan /(root). Buka URL Pages pada HP, kemudian Tambahkan ke layar utama.
4. PWA langsung memuat dashboard Riwayat dari URL /exec; tidak ada pengaturan link pada layar.
5. Transaksi memerlukan internet. File yang disimpan offline hanya halaman pembuka PWA.

Jika URL Apps Script berubah di kemudian hari, ganti atribut src pada iframe di index.html dan terbitkan ulang repositori.

IKON: icon-192.png dan icon-512.png sekarang memakai logo Athfal yang diberikan. Jika ikon lama masih tampil di HP setelah Push, hapus instalasi PWA lama lalu pasang lagi dari halaman Pages.

PENTING: Di repositori GitHub, index.html harus berada sejajar dengan manifest.webmanifest dan sw.js pada root. Jika tombol Atur link masih terlihat, berarti root index.html atau cache PWA masih versi lama.
