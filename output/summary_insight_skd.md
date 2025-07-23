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

1. TKP merupakan subtes paling berpengaruh terhadap kelulusan, dengan peserta lulus memiliki nilai TKP yang tinggi dan stabil (rata-rata > 190).

2. Peserta tidak lulus menunjukkan variasi besar pada nilai TWK dan TIU, termasuk banyak yang memiliki skor ekstrem rendah (< 50).

3. Nilai total peserta lulus hampir selalu di atas 400, sedangkan peserta tidak lulus mayoritas berada di kisaran 300-an.

4. Nilai TWK dan TIU rendah mencerminkan kurangnya kesiapan peserta dalam aspek kebangsaan dan logika dasar.

5. Selisih rata-rata total nilai antara peserta lulus dan tidak lulus melebihi 100 poin, mengindikasikan gap performa yang signifikan.

---

## 💡 Rekomendasi

1. Fokuskan latihan pada **subtes TKP**, karena memiliki margin yang tinggi terhadap kelulusan.
2. Hindari **nilai jeblok di satu subtes**: meskipun skor tinggi di TKP, jika TWK atau TIU terlalu rendah, peluang lolos tetap kecil.
3. Usahakan total nilai minimal **di atas 400** untuk memiliki peluang besar lolos SKD.

---

_Analisis ini menggunakan Python, Scikit-learn, Pandas, dan teknik summarization berbasis AI untuk menghasilkan insight dari data seleksi nasional._
