# Kalkir Kamera

Tools tracing berbasis kamera HP. Sketsa tampil tembus pandang di atas tampilan kamera, jadi tinggal diikuti garisnya di kertas.

Satu file statis (`index.html`), tanpa build dan tanpa dependensi. Kamera hanya jalan lewat **https** (atau localhost), jadi harus di-hosting.

## Fitur
- Overlay sketsa dengan slider transparansi
- Mode Garis (latar putih dihapus, pilih warna garis)
- Geser, cubit-zoom, dan putar dengan gestur; tombol Kunci, Balik, Grid, Reset
- Senter (kalau didukung HP) dan ganti kamera depan/belakang

## Hosting
- **GitHub Pages:** Settings > Pages > Deploy from a branch > `main` / `(root)`
- **Vercel / Netlify:** import repo ini, tanpa build command, output directory `.`
