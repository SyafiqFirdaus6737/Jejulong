# J-MART Demo (J-MART 3.2)

Fail ini mengandungi demo **Jejulong Mart** siap untuk dipaparkan di Google Sites atau GitHub Pages.

## Kandungan
- `index.html` — laman demo (50 produk, carian, troli, checkout, COD, Drone vs Rider, had dron 5kg).
- README ini.

## Cara guna (Google Sites / Embed)
1. Buka Google Sites → pilih atau buat laman baru.
2. Pilih *Embed* → *Embed code* → paste kandungan `index.html` (atau host `index.html` di GitHub Pages dan embed URL).
3. Jika gambar tidak muncul, pastikan laman Google Sites membenarkan sumber luar.

## Cara publish dengan GitHub Pages (disyorkan)
1. Buat repo baru (public) di GitHub, contoh `j-mart-demo`.
2. Clone repo:
```bash
git clone https://github.com/YOURUSERNAME/j-mart-demo.git
cd j-mart-demo
```
3. Letakkan `index.html` (dan logo.png jika ada) dalam folder repo.
4. Commit & push:
```bash
git add index.html
git commit -m "Add J-MART demo"
git push origin main
```
5. Pergi ke *Settings* → *Pages* → *Source* → pilih `main` branch dan root `/` → Save.
6. Tunggu beberapa minit. Laman akan hidup di:
```
https://YOURUSERNAME.github.io/j-mart-demo/
```

## Gantikan logo
Cari baris berikut dalam `index.html`:
```html
<img id="logo-img" src="LOGO_URL_HERE" alt="J-MART Logo" onerror="showSVGLogo()" />
```
Gantikan `LOGO_URL_HERE` dengan URL hosting logo anda, contohnya:
```
https://raw.githubusercontent.com/YOURUSERNAME/j-mart-demo/main/logo.png
```
atau jika anda host di server lain, guna direct link.

## Nota
- Ini adalah demo statik (tiada backend). Semua logik pembayaran dan penghantaran hanya simulasi.
- Jika mahu saya sediakan ZIP fail siap dengan logo yang anda berikan, hantar file logo, atau beri URL hosting logo dan saya akan masukkan ke `index.html`.

Enjoy! — Jika anda mahu saya terus hasilkan GitHub repo & Pages (saya akan berikan arahan lengkap) atau masukkan logo anda, beritahu saya.