## 📊 Analisis Hasil SKD SPMB STIS 2024

Proyek ini menganalisis hasil Seleksi Kompetensi Dasar (SKD) dari SPMB Politeknik Statistika STIS 2024, dengan total peserta 6.788 orang. Tujuannya adalah mengklasifikasikan peserta berdasarkan kelulusan dan merangkum pola nilai menggunakan bantuan AI.

---

### ✅ Peserta Lulus (1.702 orang)

| Subtes | Rata-rata | Q1 (25%) | Q3 (75%) | Min | Max |
|--------|-----------|----------|----------|-----|-----|
| TWK    | 93.05     | 85.00    | 100.00   | 65  | 135 |
| TIU    | 142.76    | 130.00   | 150.00   | 90  | 175 |
| TKP    | 192.49    | 187.25   | 198.00   |161  | 222 |
| Total  | 428.25    | 416.25   | 440.00   |348  | 486 |

---

### ❌ Peserta Tidak Lulus (5.086 orang)

| Subtes | Rata-rata | Q1 (25%) | Q3 (75%) | Min | Max |
|--------|-----------|----------|----------|-----|-----|
| TWK    | 58.08     | 50.00    | 65.00    | 10  | 135 |
| TIU    | 84.26     | 65.00    | 100.00   | 10  | 165 |
| TKP    | 175.39    | 167.00   | 188.00   | 80  | 217 |
| Total  | 317.73    | 294.00   | 343.00   | 80  | 424 |

---

## 🧠 Insight AI (Summarization)

> Dari hasil analisis terhadap data peserta, ditemukan bahwa TKP adalah subtes paling menentukan kelulusan. Peserta yang lulus cenderung memiliki nilai TKP yang tinggi dan stabil (rata-rata di atas 190), sementara kelompok tidak lulus memiliki variasi besar pada TWK dan TIU, bahkan banyak peserta yang mendapat nilai ekstrem rendah (< 50). Perbedaan rata-rata total nilai antara dua kelompok mencapai lebih dari 100 poin.

> TKP menjadi faktor penentu utama kelulusan, karena peserta lulus memiliki nilai TKP yang konsisten tinggi dan stabil.

> Nilai TWK dan TIU pada kelompok tidak lulus sangat bervariasi, dengan ratusan peserta memiliki skor < 50 — menunjukkan kurangnya kesiapan di materi dasar kebangsaan & logika.

> Pola distribusi total nilai menunjukkan bahwa peserta yang lulus hampir tidak pernah memiliki total < 400, sedangkan mayoritas tidak lulus berkisar di 300-an.

---

## 💡 Rekomendasi

1. Fokuskan latihan pada **subtes TKP**, karena memiliki margin yang tinggi terhadap kelulusan.
2. Hindari **nilai jeblok di satu subtes**: meskipun skor tinggi di TKP, jika TWK atau TIU terlalu rendah, peluang lolos tetap kecil.
3. Usahakan total nilai minimal **di atas 400** untuk memiliki peluang besar lolos SKD.

---

_Analisis ini menggunakan Python, Scikit-learn, Pandas, dan teknik summarization berbasis AI untuk menghasilkan insight dari data seleksi nasional._
