MyPath360 PWA - fail deploy

Upload SEMUA fail dalam folder ini ke root hosting mypath360.cikgumuiez.com:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

PENTING:
1. Laman mesti menggunakan HTTPS (subdomain Cikgu sudah menggunakan HTTPS).
2. Service worker hanya berfungsi apabila fail service-worker.js berada pada root yang sama dengan index.html.
3. Selepas deploy, buat hard refresh sekali.
4. Android/Chrome: butang “Pasang App” akan muncul apabila pelayar mengesahkan syarat PWA.
5. iPhone/iPad: butang “Pasang App” akan memberi arahan Share > Add to Home Screen.

Versi ini mengekalkan statistik MyPath360 read-only dan live chat Tawk.to sedia ada.
