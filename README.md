# Dataset Putusan Perkara Narkotika (Non-BHT) Pengadilan Negeri Jakarta Utara

Repositori ini disusun untuk memenuhi **Tugas 2 - Temu Kembali Informasi (Information Retrieval)**, Program Studi Informatika, Fakultas Teknik, Universitas Muhammadiyah Malang (UMM).

---

## Deskripsi Dataset
Dataset ini berisi dokumen resmi putusan perkara pengadilan tingkat pertama yang diakuisisi dari portal Direktori Putusan Mahkamah Agung RI dengan ketentuan:
- **Lembaga Peradilan:** Pengadilan Negeri Jakarta Utara (PN Jakarta Utara)
- **Klasifikasi Perkara:** Tindak Pidana Khusus - Narkotika dan Psikotropika
- **Status Putusan:** Non-BHT (Belum Berkekuatan Hukum Tetap)
- **Tahun Putusan:** 2026
- **Format Dokumen:** Dokumen resmi PDF asli dari Mahkamah Agung RI
- **Jumlah Berkas:** Total 55 berkas putusan resmi (.pdf) yang terdiri atas 5 putusan manual utama dan 50 putusan penunjang.

---

## Susunan Direktori Repositori

Sesuai ketentuan penugasan UTS IR 2026, susunan direktori repositori ini adalah:

```text
Dataset-Narkotika_<NIM1>_<NIM2>/
├── Dataset/
│   └── Narkotika.zip          # Berkas arsip ZIP berisi 55 dokumen putusan asli (.pdf)
├── Overview/
│   └── Overview.xlsx          # Tabel ringkasan metadata 55 putusan perkara
└── README.md                  # Dokumentasi resmi dataset repositori
```

---

## Cuplikan Ringkasan Putusan Perkara (Overview)

Tabel berikut merupakan cuplikan ringkasan metadata dari berkas `Overview/Overview.xlsx` (Total 55 perkara):

| No | No Putusan | Lembaga Peradilan | Status | Barang Bukti | Amar Putusan |
|:--:|:---|:---|:---:|:---|:---|
| 1 | `530/Pid.Sus/2026/PN Jkt Utr` | PN Jakarta Utara | Non-BHT | 1 bungkus plastik klip bening berisi narkotika jenis sabu berat brutto 0,42 gram, 1 unit handphone Samsung. | Menyatakan Terdakwa terbukti bersalah melanggar Pasal 112 ayat (1) UU No. 35/2009. Pidana penjara 4 tahun dan denda Rp 800.000.000 subsidair 3 bulan. |
| 2 | `746/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Non-BHT | 1 bungkus plastik klip narkotika jenis sabu berat brutto 0,35 gram, 1 buah pipet kaca, 1 korek api gas, 2 unit handphone. | Menyatakan Para Terdakwa terbukti bersalah melanggar Pasal 127 ayat (1) huruf a UU No. 35/2009 jo Pasal 55 ayat (1) ke-1 KUHP. Pidana penjara masing-masing 1 tahun 6 bulan. |
| 3 | `618/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Non-BHT | 1 bungkus plastik klip bening metamfetamina (sabu) berat netto 0,18 gram, 1 unit handphone Redmi. | Menyatakan Terdakwa terbukti bersalah melanggar Pasal 114 ayat (1) UU No. 35/2009. Pidana penjara 5 tahun dan denda Rp 1.000.000.000 subsidair 3 bulan. |
| 4 | `620/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Non-BHT | 2 bungkus plastik klip bening sabu total berat brutto 1,12 gram, 1 timbangan digital, 1 unit handphone Infinix. | Menyatakan Terdakwa terbukti bersalah melanggar Pasal 114 ayat (1) UU No. 35/2009. Pidana penjara 6 tahun dan denda Rp 1.000.000.000 subsidair 6 bulan. |
| 5 | `627/Pid.Sus/2026/PN Jkt.Utr` | PN Jakarta Utara | Non-BHT | 1 bungkus kertas coklat berisi ganja berat netto 12,4 gram, 1 unit sepeda motor Honda Beat, 2 unit handphone. | Menyatakan Para Terdakwa terbukti bersalah melanggar Pasal 111 ayat (1) jo Pasal 132 ayat (1) UU No. 35/2009. Pidana penjara masing-masing 4 tahun dan denda Rp 800.000.000 subsidair 2 bulan. |
| ... | *408/Pid.Sus/... s.d. 476/Pid.Sus/...* | *PN Jakarta Utara* | *Non-BHT* | *Rincian barang bukti 50 perkara termuat lengkap dalam berkas Overview.xlsx* | *Amar putusan lengkap 50 perkara termuat dalam berkas Overview.xlsx* |

---

## Sumber Data
Seluruh naskah putusan pengadilan diperoleh secara sah dan resmi dari:  
**Direktori Putusan Mahkamah Agung Republik Indonesia**  
 [https://putusan3.mahkamahagung.go.id/](https://putusan3.mahkamahagung.go.id/)
