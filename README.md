# ⚖️ Penal Code & Incident Report — San Andreas

Sistem informasi hukum berbasis web untuk **San Andreas Law Information Institute**. Berisi seluruh **Penal Code** & **Vehicle Code** lengkap dengan kalkulator hukuman, dan generator **Incident Report** resmi yang bisa di-export ke JPG.

> 🧑‍💻 **Watermark / Credit:** [**Moch Gilang**](https://github.com/mochgilang17) — [`@mochgilang17`](https://github.com/mochgilang17)

---

## 🔗 Demo

Buka langsung: **[https://mochgilang17.github.io/Penal-code-and-Incident-Report/](https://mochgilang17.github.io/Penal-code-and-Incident-Report/)**

---

## ✨ Fitur

### 📖 Statutory Index (Penal & Vehicle Code)
- **149 pasal lengkap**: Penal Code (PEN 101–809) dan Vehicle Code (VEH 001–605).
- **Sub-ayat expandable** — klik pasal untuk membuka varian (a)(b)(c) dengan hukuman masing-masing.
- **Badge klasifikasi warna**: 🔴 Felony (F) · 🟠 Misdemeanor (M) · 🔵 Infraction (I).
- **Pencarian real-time** berdasarkan kode, nama pasal, kata kunci, atau isi sub-ayat.
- **Filter kategori**: Penal / Vehicle / Felony / Misdemeanor / Infraction.
- **Sorting**: kode, hukuman tertinggi, denda tertinggi, nama A–Z.
- **† Catatan kaki pasal** — penjelasan tambahan & catatan praktik penegakan pada pasal tertentu (muncul di detail pasal).
- **🌐 Terjemahan English** — toggle ID/EN mengubah judul & deskripsi pasal ke bahasa Inggris.

### 🧮 Sentence Calculator
- Tambahkan pasal/ayat mana pun lewat tombol `+`.
- **Total denda**, **total penjara**, **jumlah charge**, dan **estimasi waktu** otomatis.
- **Grafik distribusi** hukuman per kelas (Felony / Misdemeanor / Infraction).
- **Salin Laporan** ke clipboard dengan satu klik (termasuk catatan kaki).

### ⌨️ Keyboard Shortcuts
| Tombol | Fungsi |
|--------|--------|
| `/` | Fokus ke kolom pencarian |
| `L` | Ganti bahasa ID / EN |
| `C` | Kosongkan pilihan |
| `R` | Buat Incident Report |
| `Esc` | Tutup modal / keluar dari search |

### 📄 Incident Report Generator
- **Header otomatis** sesuai departemen (dropdown):
  - **LSSD** — Los Santos County Sheriff's Department
  - **LSPD** — Los Santos Police Department
  - **SAHP** — San Andreas Highway Patrol
- **Station diisi manual** (input bebas).
- **Charges otomatis** ditarik dari kalkulator — pasal terpilih muncul lengkap dengan denda & hukuman, plus baris **TOTAL**.
- Field lengkap: URN, DR#, Incident Info, Victim/Suspect, Narrative, Reporting Officer, Disposition, dan tanda tangan.
- **Export ke JPG** (via html2canvas) atau **Print** langsung.

---

## 🚀 Cara Pakai

### Online
Cukup buka link demo di atas.

### Lokal
1. Clone repo ini:
   ```bash
   git clone https://github.com/mochgilang17/Penal-code-and-Incident-Report.git
   ```
2. Buka `index.html` dengan browser (double-click atau klik kanan → Open with).

> **Catatan:** Fitur **Export JPG** memerlukan koneksi internet karena memuat library `html2canvas` dari CDN.

---

## 🗂️ Struktur

```
Penal-code-and-Incident-Report/
├── index.html      # Web app (Penal Code + Incident Report)
├── SA_Seal.webp    # Logo / Seal of the State of San Andreas
└── README.md
```

---

## 📋 Alur Cepat

1. Cari pasal → klik untuk membuka sub-ayat → tekan `+` pada varian yang tepat.
2. Buka panel kanan untuk melihat total denda & hukuman.
3. Klik **📄 Buat Incident Report** → isi data → **💾 EXPORT JPG**.

---

## 🛠️ Teknologi

- **HTML + CSS + JavaScript** murni (tanpa framework, tanpa build step).
- [`html2canvas`](https://html2canvas.hertzen.com/) untuk export gambar.
- Data pasal disematkan langsung (embedded) di dalam `index.html`.

---

## 📜 Sumber Data

Seluruh teks pasal & hukuman bersumber dari dokumen **San Andreas Law Information Institute** (Penal Code & Vehicle Code).

> ⚠️ **Disclaimer:** Proyek ini bersifat **unofficial** dan dibuat untuk keperluan **roleplay**. Bukan dokumen hukum resmi.

---

## 📄 Lisensi

Bebas digunakan untuk keperluan roleplay & pembelajaran. Mohon cantumkan kredit bila membagikan ulang.

---

<p align="center">
  Dibuat &amp; dipelihara oleh <a href="https://github.com/mochgilang17"><b>Moch Gilang</b></a><br>
  <sub>San Andreas Law Information Institute — Unofficial Roleplay Legal Database</sub>
</p>
