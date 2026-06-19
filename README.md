# AWALUSSANAH 2026/2027

Portal informasi matrikulasi siswa baru SMP ABBS Surakarta.

## Fitur

- 🔍 **Cari Kelas** — Ketik nama siswa untuk melihat kelas, wali kelas, dan link grup WhatsApp
- 📚 **Kurikulum** — Diagram Venn sinergi Kurmer + ICT + TCP
- 💻 **ICT Class Program** — 3 level (L7/L8/L9) dengan materi lengkap
- 📖 **Tahfidz Class Program** — Target 10 Juz dengan program pendukung
- 📅 **Timeline Matrikulasi** — Jadwal kegiatan dari Juni hingga MPLS

## Teknologi

- HTML5, CSS3, JavaScript (vanilla)
- Dark theme dengan aksen gold/teal
- Responsive design
- Scroll-snap navigation

## Cara Menggunakan

1. Buka `index.html` di browser
2. atau jalankan server lokal:
   ```bash
   python -m http.server 8765
   ```
3. Akses `http://localhost:8765`

## Struktur File

```
├── index.html          # Halaman utama
├── data/
│   ├── siswa.json      # Data 132 siswa
│   └── walas/          # Foto wali kelas
├── wall/               # Foto wali kelas (watercolor)
└── README.md
```

## Author

SMP ABBS Surakarta — Kurikulum
