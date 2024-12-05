_# CCI Summit Kaggle Competition 2024  

## Kompetisi: Pendapatan Individual Berdasarkan Data Demografis  

**Tim:** **Busan Hitam**  
**Anggota Tim:**  
- Muhammad Ridho Irhamna  
- Muhammad Aga Hibatullah  
- Fatih Fikry Oktavianto  

---

## Latar Belakang  
Di era digital, kemampuan menganalisis data adalah kunci untuk pengambilan keputusan strategis di berbagai bidang. Kompetisi ini bertujuan untuk membangun model machine learning yang memprediksi pendapatan seseorang (di atas atau di bawah $50K per tahun) berdasarkan data demografis dan pekerjaan.  

---

## Dataset Description  
Dataset yang digunakan memiliki beberapa kolom fitur dengan deskripsi berikut:  

- **Tahun Kelahiran**: Variabel integer yang mewakili tahun lahir pekerja.  
- **Kelas Pekerjaan**: Variabel string yang berisi kelas atau tipe pekerjaan dari pekerja.  
- **FNLWGT**: Variabel float yang merepresentasikan skala orang dengan karakteristik serupa.  
- **Pendidikan**: Variabel string yang merepresentasikan tingkat pendidikan terakhir pekerja dalam bentuk gelar.  
- **Jenjang Pendidikan**: Variabel string yang merepresentasikan tingkat pendidikan pekerja.  
- **Status**: Variabel string yang mengelompokkan status pernikahan pekerja.  
- **Pekerjaan**: Variabel string yang berisi pekerjaan spesifik atau jabatan pekerja.  
- **Hubungan**: Variabel string yang mempresentasikan status pekerja dalam keluarga.  
- **Etnis**: Variabel string yang berisi etnis atau suku pekerja.  
- **Sex**: Variabel string untuk mewakili jenis kelamin pekerja.  
- **Pendapatan**: Variabel string dalam bentuk dollar yang merepresentasikan penghasilan sampingan.  
- **Pengeluaran**: Variabel string dalam bentuk dollar untuk menunjukan uang yang telah hilang karena kebutuhan pekerjaan sampingan.  
- **Hours-per-week**: Variabel integer yang mewakili jumlah waktu pekerjaan dalam tiap minggu.  
- **Asal Negara**: Variabel string yang menunjukan asal negara pekerja.  
- **Income**: Variabel string yang mengkategorikan range dari pendapatan pekerja.  
- **Jumlah Anak**: Variabel integer yang berisi jumlah anak tiap pekerja.  

**Files:**  
- `train.csv`: Dataset untuk pelatihan model.  
- `test.csv`: Dataset untuk pengujian model.  

---

## Tujuan  
- Membuat model machine learning dengan akurasi prediksi terbaik.  
- Mengasah keterampilan dalam data science, EDA, dan model deployment.  
- Meningkatkan inovasi dan kreativitas dalam pengolahan data.  

---

## Evaluasi  

Kompetisi ini menggunakan **F1 Score** untuk mengevaluasi keseimbangan antara **precision** dan **recall**, terutama pada dataset yang tidak seimbang.  

### Rumus F1 Score:  
F1 = 2 * (Precision * Recall) / (Precision + Recall)

### Komponen Evaluasi:  
- **Accuracy**:  
  Accuracy = (TP + TN) / (TP + TN + FP + FN)

- **Precision**:  
  Precision = TP / (TP + FP)

- **Recall**:  
  Recall = TP / (TP + FN)

**Penilaian:**  
- **70% Leaderboard:** Berdasarkan hasil prediksi terbaik pada leaderboard.  
- **30% Notebook:** Kriteria meliputi:  
  - **Kerapihan Kode:** Code terstruktur dan jelas.  
  - **Exploratory Data Analysis (EDA):** Mendapatkan pola dan insight dari dataset.  
  - **Reproducibility:** Kode menghasilkan output yang konsisten setiap dijalankan.  
  - **Pipeline Structure:** Terdiri dari preprocessing, pelatihan model, dan evaluasi.  

---

## Struktur Notebook  
1. **Data Preprocessing:** Membersihkan dan mempersiapkan data untuk pelatihan.  
2. **Exploratory Data Analysis (EDA):** Menemukan pola dan insight dari dataset.  
3. **Model Development:** Membuat dan melatih model machine learning untuk prediksi.  
4. **Evaluation:** Menggunakan F1 Score untuk menilai performa model.  
5. **Documentation:** Menyediakan penjelasan rinci dan kode yang dapat direproduksi.  

---

**Tim Busan Hitam**  
_CCI Summit Kaggle Competition 2024_  
_
