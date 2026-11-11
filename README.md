# MAX VPS Dashboard

Dashboard statis untuk mengelola tautan dan endpoint.

## Fitur
- Login password demo: `123456`
- Beranda, tambah, lihat, edit, hapus link
- Data disimpan pada `localStorage` browser

## Jalankan lokal
Buka `index.html` di browser atau jalankan server statis.

## Deploy
Dapat di-host sebagai static site di Vercel.

## Catatan keamanan dan data
Login frontend ini hanya gerbang sederhana, bukan autentikasi aman. Password berada di source frontend sehingga dapat dilihat oleh pengunjung yang memahami DevTools. Jangan gunakan untuk melindungi data sensitif. Data link tersimpan per browser/perangkat dan tidak tersinkron ke pengguna lain.