# BESI KITA — Landing Page (Varian Gradasi)

Landing page statis untuk **CV Indo Jaya**, pembeli limbah besi dan logam skala industri (B2B).

Varian ini memakai transisi **gradasi menyatu**: section kontak berlatar putih, peta full-bleed, dan gradient gelap menyatu mulus ke section berikutnya tanpa garis batas.

## Struktur

```
index.html      # seluruh halaman (HTML + CSS + JS inline, tanpa framework/CDN)
assets/
  hero/         # foto hero
  gallery/      # 7 foto galeri (slider horizontal)
  materials/    # 6 foto jenis limbah
robots.txt
sitemap.xml
```

## Menjalankan lokal

Tidak ada build step.

Buka `index.html` langsung di browser, atau:

```powershell
python -m http.server 8000
```

lalu buka http://localhost:8000

## Status: DEMO

- Nomor WhatsApp, email, telepon, alamat, sosial media, dan pin peta masih **placeholder**.
- Foto material dan galeri masih **foto stok (Wikimedia)** — ganti dengan foto asli sebelum publish.
- Domain di canonical, Open Graph, JSON-LD, `robots.txt`, dan `sitemap.xml` masih `besikita.co.id`.

## Deploy

Vercel: Framework Preset **Other**, Build Command kosong, Output Directory `./`.
