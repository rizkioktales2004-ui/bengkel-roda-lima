# Roda Lima Motor — UTS Pemrograman Antarmuka Web

Situs multihalaman untuk bengkel motor fiktif (sub-tema 9). Bootstrap 5.3 (CDN), tanpa JavaScript buatan sendiri.

## Anggota

| NPM   | Nama         | Akun GitHub | Halaman                       |
| ----- | ------------ | ----------- | ----------------------------- |
| (isi) | (isi, ketua) | (isi)       | index.html, terima-kasih.html |
| (isi) | (isi)        | (isi)       | layanan.html, galeri.html     |
| (isi) | (isi)        | (isi)       | booking.html, tentang.html    |

## Sub-tema & pengguna

Bengkel motor. Nama usaha: Roda Lima Motor. Target: pekerja dan mahasiswa di Surabaya pemilik motor matic/bebek yang ingin biaya servis jelas dan tidak antre lama.

## Sitemap

index → layanan → booking → terima-kasih; galeri; tentang. Navigasi sama di semua halaman. (Tambahkan sketsa denah mobile & desktop.)

## Token (css/style.css)

| Token                            | Terang                    | Gelap   |
| -------------------------------- | ------------------------- | ------- |
| --warna-bg                       | #EEF1EC                   | #11191C |
| --warna-permukaan                | #fff                      | #1A2529 |
| --warna-teks                     | #14211F                   | #E8EDEA |
| --warna-merek                    | #0F3D4C                   | #7CCFE0 |
| --warna-aksen                    | #B4430F                   | #FF9A62 |
| --font-judul / --font-isi        | Barlow Condensed / Barlow | sama    |
| --ruang, --ruang-besar, --radius | 1rem, 3rem, .5rem         | sama    |

## Breakpoint

| Nilai          | Perubahan                                        |
| -------------- | ------------------------------------------------ |
| dasar (mobile) | 1 kolom                                          |
| 48em           | hero 2 kolom, statistik 3 kolom, tentang 2 kolom |
| 64em           | booking 2 kolom (form + info sticky)             |

## Framework vs CSS sendiri

Framework: navbar responsif + collapse, `row/col`, `card`, `btn`, `badge`, `alert`, `form-control/form-select/form-check`. CSS sendiri: token, hero & booking (grid-template-areas), galeri auto-fit, tabel, statistik, dark mode.
Perbandingan: kartu ditulis dengan Bootstrap (`card h-100` + `col-md-4`) cukup sedikit kelas, tetapi tampilan default harus ditimpa lewat token. Dengan CSS murni (`.galeri-kartu` auto-fit) kontrol penuh dan tanpa breakpoint manual. Dipakai: Bootstrap untuk komponen interaktif/form, CSS murni untuk layout khas.

## Bukti (isi sendiri)

Screenshot 360/768/1280px + dark mode, skor Lighthouse, hasil W3C Validator, catatan uji keyboard.

## Sumber & AI

Ilustrasi SVG dibuat sendiri. Font: Google Fonts (Barlow). Bootstrap 5.3.3 (MIT). AI (Claude) dipakai untuk menyusun kerangka HTML/CSS; seluruh anggota wajib memahami kode.
