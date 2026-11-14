# Dataset Putusan Perkara Narkotika (Non-BHT) Pengadilan Negeri Jakarta Utara

Repositori ini disusun untuk memenuhi **Tugas 2 - Temu Kembali Informasi (Information Retrieval)**, Program Studi Informatika, Fakultas Teknik, Universitas Muhammadiyah Malang (UMM).

---

## 📌 Deskripsi Dataset
Dataset ini berisi dokumen resmi putusan perkara pengadilan tingkat pertama yang diakuisisi secara manual dari portal Direktori Putusan Mahkamah Agung RI dengan ketentuan:
- **Lembaga Peradilan:** Pengadilan Negeri Jakarta Utara (PN Jakarta Utara)
- **Klasifikasi Perkara:** Tindak Pidana Khusus - Narkotika dan Psikotropika
- **Status Putusan:** Non-BHT (Belum Berkekuatan Hukum Tetap)
- **Tahun Putusan:** 2026
- **Format Dokumen:** Dokumen resmi PDF asli dari Mahkamah Agung RI

---

## 📁 Susunan Direktori Repositori

Sesuai ketentuan penugasan UTS IR 2026, susunan direktori repositori ini adalah:

```text
Dataset-Narkotika_<NIM1>_<NIM2>/
├── Dataset/
│   └── Narkotika.zip          # Berkas arsip ZIP berisi dokumen putusan asli (.pdf)
├── Overview/
│   └── Overview.xlsx          # Tabel ringkasan metadata putusan pengadilan
└── README.md                  # Dokumentasi resmi dataset repositori
```

---

## 📋 Ringkasan Dokumen Putusan (Overview)

Tabel berikut merupakan salinan ringkasan isi berkas `Overview/Overview.xlsx`:

| No | No Putusan | Lembaga Peradilan | Terdakwa | Status | Barang Bukti | Amar Putusan |
|:--:|:---|:---|:---|:---:|:---|:---|
| 1 | `530/Pid.Sus/2026/PN Jkt Utr` | PN Jakarta Utara | Bayaz Saedi Bin Eshghali | Non-BHT | 1 bungkus klip bening narkotika jenis sabu berat brutto 0,42 gram, 1 unit HP Samsung. | Menyatakan Terdakwa terbukti secara sah dan meyakinkan bersalah melanggar Pasal 112 ayat (1) UU No. 35/2009. Menjatuhkan pidana penjara 4 tahun dan denda Rp 800.000.000 subsidair 3 bulan kurungan. |
| 2 | `746/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Ananda Ajeng Praswati & Syamril Achmad Hambali | Non-BHT | 1 bungkus klip sabu berat brutto 0,35 gram, 1 pipet kaca, 1 korek api gas, 2 unit HP. | Menyatakan Para Terdakwa terbukti bersalah melanggar Pasal 127 ayat (1) huruf a UU No. 35/2009 jo Pasal 55 ayat (1) ke-1 KUHP. Menjatuhkan pidana penjara masing-masing 1 tahun 6 bulan. |
| 3 | `618/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Joko Eka Martanto | Non-BHT | 1 bungkus klip metamfetamina (sabu) berat netto 0,18 gram, 1 unit HP Redmi. | Menyatakan Terdakwa terbukti bersalah melanggar Pasal 114 ayat (1) UU No. 35/2009. Menjatuhkan pidana penjara 5 tahun dan denda Rp 1.000.000.000 subsidair 3 bulan kurungan. |
| 4 | `620/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Faizal Agung Syahputra | Non-BHT | 2 bungkus klip sabu total berat brutto 1,12 gram, 1 timbangan digital, 1 unit HP Infinix. | Menyatakan Terdakwa terbukti bersalah melanggar Pasal 114 ayat (1) UU No. 35/2009. Menjatuhkan pidana penjara 6 tahun dan denda Rp 1.000.000.000 subsidair 6 bulan kurungan. |
| 5 | `627/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Bagas Hakiki & Faishal Nurahman | Non-BHT | 1 bungkus kertas coklat ganja berat netto 12,4 gram, 1 unit sepeda motor Honda Beat, 2 unit HP. | Menyatakan Para Terdakwa terbukti bersalah melanggar Pasal 111 ayat (1) jo Pasal 132 ayat (1) UU No. 35/2009. Menjatuhkan pidana penjara masing-masing 4 tahun dan denda Rp 800.000.000 subsidair 2 bulan kurungan. |

---

## ⚖️ Sumber Data
Seluruh naskah putusan pengadilan diperoleh secara sah dan resmi dari:  
**Direktori Putusan Mahkamah Agung Republik Indonesia**  
🔗 [https://putusan3.mahkamahagung.go.id/](https://putusan3.mahkamahagung.go.id/)
