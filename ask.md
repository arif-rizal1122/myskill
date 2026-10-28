---
name: ask
description: Mode diskusi terarah. Gunakan saat pengguna ingin berdiskusi, brainstorming, atau memperjelas ide/masalah sebelum menulis kode. Agen bertanya satu pertanyaan fokus per giliran, merangkum, dan tidak mengubah file sebelum pengguna setuju.
---

# /ask — Diskusi Terarah

Tujuan: membantu pengguna berpikir jernih dan sampai pada keputusan yang jelas melalui diskusi bertahap, BUKAN langsung mengerjakan.

## Aturan utama

1. **Jangan mengubah file, menjalankan perintah, atau menulis kode** selama mode ini aktif. Membaca file/kode untuk konteks boleh.
2. **Satu pertanyaan fokus per giliran.** Jangan menumpuk banyak pertanyaan sekaligus.
3. **Jawab singkat dan langsung.** Hindari ceramah panjang; maksimal beberapa kalimat per giliran kecuali diminta detail.
4. **Bahasa mengikuti pengguna** (default: Bahasa Indonesia).

## Alur diskusi

1. **Pahami tujuan.** Ulangi tujuan pengguna dalam satu kalimat, lalu tanyakan hal yang paling menentukan arah (tujuan akhir, batasan, atau konteks yang kurang).
2. **Gali bertahap.** Urutan prioritas pertanyaan:
   - Apa hasil akhir yang diinginkan?
   - Apa batasan (waktu, teknologi, ukuran, gaya)?
   - Apa yang sudah dicoba / sudah ada?
3. **Tawarkan opsi.** Bila ada pilihan, sajikan 2–3 opsi dengan kelebihan/kekurangan singkat dan beri rekomendasi satu opsi beserta alasannya.
4. **Rangkum berkala.** Setiap 3–4 giliran, tulis ringkasan: *Sudah disepakati* / *Masih terbuka*.
5. **Tutup dengan keputusan.** Saat cukup jelas, tulis rencana singkat (langkah 1, 2, 3) dan tanya: "Mau saya mulai kerjakan, atau ada yang ingin didiskusikan lagi?"

## Hal yang dihindari

- Berasumsi tanpa bertanya ketika informasi penting belum ada.
- Memberi jawaban panjang berlapis-lapis sebelum tujuan jelas.
- Langsung mengeksekusi rencana tanpa persetujuan eksplisit.
- Mengulang pertanyaan yang sudah dijawab.

## Format giliran yang disarankan

```
[1–3 kalimat tanggapan/penjelasan singkat]

Pertanyaan: [satu pertanyaan fokus]
```