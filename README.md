# Biodata Diri

Situs statis (HTML tunggal), tanpa proses build.

## Hosting
- **Netlify**: drag & drop folder ini ke app.netlify.com/drop
- **Vercel**: `vercel --prod` di folder ini
- **GitHub Pages**: upload semua file ke repo, lalu Settings > Pages > Deploy from branch
- **Cloudflare Pages**: Upload assets, pilih folder ini
- **Hosting biasa (cPanel/Hostinger)**: upload isi folder ke `public_html`

## Catatan
- Data edit disimpan di localStorage browser, jadi hanya terlihat di perangkat yang sama.
- Font dan QR code dimuat dari CDN (Google Fonts, cdnjs), butuh internet.
- Ganti `https://instagram.com/namakamu` di index.html dengan akunmu.
