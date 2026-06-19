# Catatan Diskusi — Presentasi Awalussanah SMP ABBS TA 2026/2027

## Tujuan
Membuat presentasi HTML slide interaktif untuk Awalussanah calon siswa baru SMP ABBS Surakarta TA 2026/2027.

## Sumber Referensi
| File | Isi |
|------|-----|
| `Awwalussanah.pptx` (10 slide) | Presentasi tahun lalu: ICT Class Program, TCP (Tahfidz Class Program), timeline awalussanah |
| `kurikulum.html` | Presentasi Final Project Exhibition ICT — **template style** (green theme, navigasi slide) |
| `AWALUSSANAH T.A. 20252026.pdf` | PDF Canva (gambar), tidak bisa diekstrak |

## KONSEP FINAL v3 (18 Juni 2026) — "Elegan Gelap, berbasis aset & fakta asli"
> File aktif: **`awwalussanah.html`**. Versi sebelumnya (`presentasi-awalussanah.html`, `awwalussanah-dua-sayap.html`) ditolak user — diabaikan/akan dihapus.

**Prinsip v3 (permintaan user):**
- **Tidak ada konten kosong/placeholder.** Bagian tanpa sumber DIHAPUS (visi-misi, sambutan, profil/prestasi).
- **Tidak menyampaikan apa pun tanpa sumber** (PPTX/PDF/HTML/pernyataan user).
- Gaya: **elegan gelap (mewah)**, full-bleed (tanpa kartu krem mengambang).
- Memakai **aset asli** dari `Awwalussanah.pptx`: logo resmi (image12), foto siswa (image13), foto Tahfidz ICT Camp/ETHIC (image91) — ditanam base64.
- Nama sekolah BENAR: **SMP Al-Abidin (ABBS) Surakarta** (logo: "al-abidin", domain alabidin.sch.id). Catatan: "Ar-Risalah Bil Battul" di draf lama SALAH/ngarang — sudah dibuang.
- Warna brand asli logo: hijau–kuning–toska–navy.

**Struktur 11 slide (semua bersumber):** Cover · TCP Overview · TCP Komponen · Kenapa ICT (stat +23% dari PPTX) · ICT Roadmap · Level 7 · Level 8 · Level 9 · Program Pendukung (foto ETHIC) · Matrikulasi (tgl dari pernyataan user) · Cari Kelas (search) · Penutup.

**Fitur Cari Kelas:** siswa ketik nama → muncul hanya nama yang cocok (≥3 huruf, maks 8, privasi) → klik nama → kartu detail: kelas + wali kelas + no WA + link grup. Data nama→kelas dari pembagian acak (seed 20262027): 7 Putra A/B/C (28/28/27) & 7 Putri A/B (24/24), total 131.

**MENUNGGU DATA dari user** (objek `KELAS` di `<script>` masih kosong): untuk tiap 5 kelas → nama **wali kelas**, **nomor WA**, **link grup WA**.

---
### (Arsip) Konsep v2 "Dua Sayap" — DITOLAK
> File HTML lama (`presentasi-awalussanah.html`) **DIABAIKAN** atas permintaan user. Mulai dari nol.

- **Konsep**: *Dua Sayap* — TCP (Tahfidz = sayap iman) & ICT (sayap teknologi) ditampilkan **SETARA**, bukan TCP diselipkan. Keduanya membentuk "Generasi Rabbani yang Melek Teknologi".
- **Format**: Slide deck (1 layar penuh per slide, navigasi panah/keyboard/swipe).
- **Visual**: Ikon & ilustrasi vektor (SVG/emoji rapi) — TANPA foto, bisa langsung jadi.
- **Style**: Ikuti `kurikulum.html` (green #6B8E4E, gold #8b6914, Newsreader + Inter, dark canvas + grid + partikel).
- **Beda dari versi lama**: alur storytelling (kenapa→apa→kapan→gabung), TCP dapat slide khusus setara ICT, hilangkan mockup placeholder yang ramai.

## Struktur 13 Slide (Baru — +slide Pembagian Kelompok)

| # | Judul | Isi |
|---|-------|-----|
| 1 | **Pembuka** | "AWWALUSSANAH TA 2026/2027", logo, emblem dua sayap, tema |
| 2 | **Sambutan & Visi** | Sambutan Waka Kurikulum, visi-misi, pengenalan konsep Dua Sayap |
| 3 | **Profil SMP ABBS** | Fasilitas, prestasi, lingkungan |
| 4 | **🕌 Sayap Iman — TCP Overview** | Filosofi tahfidz, Target 10 Juz |
| 5 | **🕌 TCP — Komponen Program** | Halaqoh, Laporan Harian, Media, Murojaah, Camping Qur'an, Motivasi, Sertifikasi Juziyah |
| 6 | **💻 Sayap Teknologi — ICT Overview** | Roadmap Level 7 → 8 → 9 |
| 7 | **ICT Level 7** | Hardware/Software, MS Office, Appsheet, Canva, Wordpress, Construct, Corel Draw |
| 8 | **ICT Level 8** | Tinkercad, Arduino, MIT App Inventor, Project RC Car |
| 9 | **ICT Level 9** | HTML, CSS, JavaScript, jQuery, Bootstrap |
| 10 | **Program Pendukung ICT** | ICT Show, ICT Camp, Workshop ICT, 5 Minutes Presentation |
| 11 | **Informasi Matrikulasi** | Timeline visual jadwal |
| 12 | **Pembagian Kelompok Kelas** | 3 kelas Putra (28/28/27) + 2 kelas Putri (24/24), dari data SISWA BARU |
| 13 | **Penutup** | QR Code / link grup WA + ajakan bergabung |

- **File baru**: `awwalussanah-dua-sayap.html`
- **Ikon**: semua emoji diganti ikon garis SVG (sprite) — lebih konsisten & profesional.
- **Data kelas**: diambil dari `SISWA BARU 2026 2027 MR AMMAR.xlsx` (131 siswa: 83 L, 48 P), dibagi acak (seed tetap). Kelas: 7 Putra A/B/C & 7 Putri A/B.

## Informasi Matrikulasi (Fix)
- **21-23 Juni**: Proses masuk grup kelas
- **24 Juni**: Meeting perdana untuk semua siswa
- **25-27 Juni**: Materi belajar mandiri
- **29 Juni - 4 Juli**: Pertemuan online per kelas (jadwal menyusul di grup)
- **6-10 Juli**: Penugasan terstruktur
- **Akhir slide**: QR code/link grup WA kelas + data siswa per kelas

## Status Pekerjaan
- [x] Konsep & struktur slide — **DONE**
- [x] Konten TCP (Tahfidz Class Program) — **DONE** (dari PPTX)
- [x] Konten ICT Level 7-9 — **DONE** (dari PPTX)
- [x] Konten Program Pendukung ICT — **DONE** (dari PPTX)
- [x] Informasi Matrikulasi — **DONE**
- [x] Konsep baru "Dua Sayap" — **DONE** (18 Juni)
- [ ] Pembuatan file HTML presentasi baru (`awwalussanah-dua-sayap.html`) — **PROSES**
- [ ] Menambahkan QR code & link grup WA — **MENUNGGU DATA**
- [ ] Data siswa per kelas — **MENUNGGU DATA**
- [ ] Nama Waka Kurikulum & teks visi-misi resmi — **MENUNGGU DATA**
- [ ] Prestasi & fasilitas spesifik untuk slide Profil — **MENUNGGU DATA**

## Konten TCP (dari PPTX)
- **Target**: 10 Juz
- **Halaqoh Al-Qur'an**: Pembelajaran kelompok
- **Laporan Harian**: Monitoring hafalan harian
- **Media Pembelajaran**: Fasilitas pendukung tahfidz
- **Murojaah Harian**: Pengulangan hafalan rutin
- **Camping Qur'an**: Program intensif
- **Motivasi Tahfidz**: Seminar/penguatan mental
- **Sertifikasi Juziyah**: Ujian per juz

## Konten ICT
| Level | Materi |
|-------|--------|
| **Level 7** | Hardware/Software, MS Office (Word, Excel), Appsheet (aplikasi APK), Canva (multimedia interaktif), Wordpress (website), Construct (game), Corel Draw (asset game/logo) |
| **Level 8** | Tinkercad (simulasi), Arduino, MIT App Inventor, Project RC Car |
| **Level 9** | HTML, CSS, JavaScript, jQuery, Bootstrap |

## Program Pendukung ICT
- ICT Show
- ICT Camp
- Workshop ICT
- 5 Minutes Presentation

---

*Dibuat: 18 Juni 2026*
