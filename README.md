# UTDI THE ARCADE — Landing Page

Landing page untuk komunitas Gen Z di kampus UTDI yang menjadikan dunia digital sebagai petualangan. Dibangun sangat ringan dengan Tailwind Play CDN, fokus pada tipografi display yang bold, grid kartu yang playful, dan palet warna kontras.

## Preview
Buka file `index.html` langsung di browser atau gunakan Live Server untuk hot reload. Tampilan hero berisi headline "THE ARCADE", badge miring, dan grid 4 kartu berwarna.

## Fitur
- __Hero besar & bold__: Headline display dengan badge miring.
- __Grid kartu responsif__: 4 kartu dengan dekorasi SVG dan CTA.
- __Palet warna kustom__: primary, accent1, accent2, dan alt (hitam).
- __Zero build step__: Cukup CDN — tidak perlu tooling.

## Teknologi
- __Tailwind CSS (Play CDN)__ — tanpa setup build.
- __Google Fonts__: Unbounded (display) & Inter (body).

## Palet Warna
- __primary__: `#5B5BD6` (biru keunguan)
- __accent1__: `#FFD23F` (kuning)
- __accent2__: `#FF6A3D` (oranye)
- __alt__: `#0B0B0E` (hitam gelap)

## Mulai Cepat
1. Clone/unduh repo ini.
2. Buka `landing/index.html` di browser.
3. Opsi: pakai ekstensi Live Server (VS Code) untuk auto-reload.

## Struktur Proyek
```
landing/
├─ index.html    # Halaman utama (Tailwind CDN + komponen)
├─ README.md     # Dokumen ini
└─ LICENSE       # Lisensi
```

## Kustomisasi
- __Ganti copy__: edit teks di section hero dan kartu pada `index.html`.
- __Ubah warna__: modifikasi `tailwind.config` inline di `index.html` (objek `colors`).
- __Tambahkan kartu__: duplikasi blok kartu pada grid dan ganti kontennya.
- __Mode alt/gelap__: bungkus section dengan `bg-alt text-white` untuk nuansa cool.

## Kontribusi
Kontribusi dari teman-teman UTDI sangat ditunggu!
- Buka issue untuk ide/bug.
- Buat PR kecil dan jelas (deskripsi singkat, screenshot bila perlu).

## Lisensi
Lihat file `LICENSE`.
