# Catatan Diskusi — Presentasi Awalussanah SMP ABBS TA 2026/2027

## Tujuan
Membuat presentasi HTML slide interaktif untuk Awalussanah calon siswa baru SMP ABBS Surakarta TA 2026/2027.

## Sumber Referensi
| File | Isi |
|------|-----|
| `Awwalussanah.pptx` (10 slide) | Presentasi tahun lalu: ICT Class Program, TCP (Tahfidz Class Program), timeline awalussanah |
| `AWALUSSANAH T.A. 20252026.pdf` | PDF Canva (gambar), tidak bisa diekstrak |
| `SISWA BARU 2026 2027 MR AMMAR2.xlsx` | Data siswa + No. WA Orang Tua (133 siswa, sumber WA) |
| `Pembagian_Kelas_2026.xlsx` | Pembagian resmi 5 kelas (132 siswa, Ringkasan + tiap sheet per kelas) |
| `SISWA BARU 2026 2027 MR AMMAR.xlsx` | File lama (sebelum update WA) |

## File Aktif
| File | Fungsi |
|------|--------|
| `index.html` | Halaman utama presentasi (slide + Cari Kelas) |
| `pembagian-kelas.html` | Halaman referensi tabel pembagian kelas per tab |
| `data/siswa.json` | Data siswa (nama, gender, asal sekolah, kelas, WA) — 132 siswa |
| `vercel.json` | Konfigurasi Vercel (rewrite `/pembagian-kelas`) |

## Data Siswa
- **Total**: 132 siswa (semua sumber sync)
- **Pembagian**:
  - 7 Putra A (7A): 28 L
  - 7 Putra B (7B): 28 L
  - 7 Putra C (7C): 28 L
  - 7 Putri A (7D): 24 P
  - 7 Putri B (7E): 24 P
- **Sumber kelas**: `Pembagian_Kelas_2026.xlsx` (5 sheet)
- **Sumber WA**: `AMMAR2.xlsx` (kolom "NO HP ORTU")
- **Sync status**: `siswa.json` == inline DATA di `pembagian-kelas.html` == data yg di-fetch `index.html` ✅

## Wali Kelas
| Kelas | Label | Wali Kelas |
|-------|-------|------------|
| 7 Putra A | 7A | Ifan Destya Adi Tama, S.Pd, Gr. |
| 7 Putra B | 7B | Daffa Danendra Rizqi Nugraha, S.Pd. |
| 7 Putra C | 7C | Hang Sakti Abdullah, S.Pd. |
| 7 Putri A | 7D | Aulia Qisthi Rosyada, S.Pd., Gr. |
| 7 Putri B | 7E | Charlieta Nova Putri Fedito, S.Kom |

## Catatan Penting
- `index-sinergi.html` dan `index - Copy (2).html` adalah file cadangan/arsip, tidak digunakan
- File mockup (`mockup*.html`) tidak dipakai
- Yafi' Akhtartsany Sedayu (L, SDIT Azahra Sragen, WA: 85791077933) ada di AMMAR2.xlsx tapi belum masuk `siswa.json`, `pembagian-kelas.html`, dan `Pembagian_Kelas_2026.xlsx`

## Deployment Vercel
| Item | Nilai |
|------|-------|
| Project name | `awwalussanahsmpabbs` |
| Team | `smpabbs-projects` |
| Production URL | `https://awwalussanahsmpabbs.vercel.app` |
| Hanya alias itu | ✅ — alias lain (`awalussanah-2026.vercel.app` dll) sudah dihapus |
| GitHub repo | `smpabbs/awalussanah-2026` |

## Riwayat Perubahan Sesi Ini
1. Analisis sinkronisasi data siswa dan walas antar file
2. Project `harunysa` dibuat & di-deploy (tidak dipakai — dihapus/ditinggalkan)
3. Kembali ke project `awwalussanahsmpabbs`
4. Alias `awalussanah-2026.vercel.app` & alias lain dihapus
5. Hanya `awwalussanahsmpabbs.vercel.app` yang aktif

## Perbaikan Sebelumnya
- WALAS disinkronkan: HTML (Ifan→7A, Daffa→7B, Hang→7C)
- WA numbers jadi clickable wa.me links
- Ahmad Rafi' Asyraf: WA dipisah `/` (81227566272/081227566242)
- KELAS_LABEL: 7A, 7B, 7C, 7D, 7E
- `vercel.json`: rewrite `/pembagian-kelas` tanpa `.html`

---

*Dibuat: 18 Juni 2026 — Diperbarui: 20 Juni 2026*
