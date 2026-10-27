# Kalkulator Anuitas Pro

Aplikasi web modern untuk simulasi dan perhitungan **Anuitas Pinjaman / Kredit** secara interaktif dengan visualisasi grafik total pembayaran, pembagian porsi pokok dan bunga, serta tabel jadwal angsuran bulanan lengkap (amortisasi).

Dibangun dengan palet warna **Biru Red Bull & Ford Racing**, aksen **Silver metalik**, serta ornamen **Kuning dan Merah** yang memberikan kesan profesional, presisi, dan modern.

---

## Fitur Utama

- ⚡ **Input Pinjaman Interaktif**:
  - **Pokok Pinjaman**: Penggeser (*slider*) dinamis hingga miliaran Rupiah, input teks otomatis berformat Rupiah (`Rp`), dan tombol pintas cepat (25 Jt, 50 Jt, 100 Jt, 250 Jt, 500 Jt, 1 M, 2 M).
  - **Suku Bunga**: Pengaturan persentase tahunan (% p.a.), tombol stepper presisi (±0.25%), dan kalkulasi bunga bulanan real-time.
  - **Durasi / Tenor**: Pilihan durasi berbasis Tahun (1 s/d 30 Tahun) dengan pintas cepat.
  - **Preset Skenario**: KPR Rumah, Kredit Mobil Baru, Modal Usaha UMKM, dan Pinjaman Multiguna.
  - **Simulasi Pelunasan Dipercepat**: Input pembayaran pokok ekstra bulanan untuk menghitung penghematan bunga dan percepatan pelunasan.

- 📊 **Visualisasi Grafik Interaktif**:
  - **Donut Chart**: Komposisi Total Pembayaran (Porsi Pokok Pinjaman vs Total Beban Bunga).
  - **Grafik Amortisasi SVG**:
    - Mode Kurva Saldo Sisa Pokok (*Remaining Balance Curve*).
    - Mode Bar Porsi Angsuran Bulanan (Porsi Pokok yang membesar vs Porsi Bunga yang mengecil).
    - Dilengkapi *interactive hover/scrubbing* untuk melihat rincian bulan tertentu.

- 📋 **Tabel Angsuran Bulanan Lengkap**:
  - Kolom lengkap: Periode Bulan, Tahun, Saldo Awal, Angsuran Bulanan, Porsi Pokok, Porsi Bunga, Akumulasi Bunga, dan Sisa Pokok.
  - Pilihan tampilan: **Rincian Per Bulan** atau **Ringkasan Tahunan (*Yearly Rollup*)**.
  - Pencarian nomor bulan / tahun, sortir urutan, dan paginasi rapi.
  - **Ekspor CSV / Excel** langsung siap pakai (dengan delimiter semicolon standar IDR).
  - Dukungan **Cetak PDF / Print View**.

- ⚖️ **Komparasi Metode Bunga**:
  - Perbandingan langsung antara **Anuitas (Cicilan Tetap)**, **Bunga Efektif (Menurun)**, dan **Bunga Flat**.

---

## Teknologi yang Digunakan

- **React 19**
- **TypeScript**
- **Vite**
- **Tailwind CSS v4**
- **Lucide Icons**
- **Plus Jakarta Sans & JetBrains Mono** (Tabular Numerals)
