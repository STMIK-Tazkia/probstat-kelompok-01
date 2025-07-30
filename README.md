<!-- ⌨️ Typing Title -->
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&color=0A0A0A&center=true&vCenter=true&width=700&lines=Klasifikasi+Insomnia+berdasarkan+Data+Tidur+dan+Gejala;Machine+Learning+untuk+Deteksi+Risiko+Insomnia" alt="Typing SVG" />
</h1>

# Klasifikasi Insomnia Berdasarkan Data Pola Tidur dan Gejala

Proyek ini bertujuan untuk membangun model klasifikasi untuk mendeteksi risiko **insomnia** berdasarkan data gejala dan kebiasaan tidur. Data bersumber dari dataset terbuka dan digunakan untuk pelatihan model machine learning seperti **Logistic Regression** dan **Decision Tree Classifier**.

## Struktur Proyek

- `Insomniac_data.xlsx` : Dataset berisi fitur-fitur gejala dan pola tidur.
- `thanksinsomnia.ipynb` : Notebook Jupyter berisi proses preprocessing, modeling, evaluasi, dan visualisasi.
- `Proposal-Modeling-Dataset-Insomnia.docx` : Dokumen proposal berisi penjelasan latar belakang, metodologi, dan rencana modeling.

## Deskripsi Dataset

- **Sumber**: [Mendeley Data - Dataset of Insomniac and Normal People](https://data.mendeley.com/datasets/jr5n4prgfv/1)
- **Jumlah Fitur**: 10 fitur dan 1 target (`Disorder`: 1 = insomnia, 0 = normal)
- **Contoh Fitur**:
  - `Total_sleep_time(hour)`
  - `Satisfaction_of_sleep`
  - `Late_night_sleep`
  - `Wakeup_frequently_during_sleep`
  - `Sleep_at_daytime`
  - `Recent_psychological_attack`

## Metodologi

### 1. Preprocessing
- Mengubah nilai kategorikal (ya/tidak) menjadi numerik (1/0)
- Normalisasi nilai fitur numerik
- Split data: 70% training, 30% testing

### 2. Modeling
- Algoritma: Logistic Regression, Decision Tree Classifier
- Tools: `pandas`, `scikit-learn`, `seaborn`
- Evaluasi: Akurasi, Confusion Matrix, Precision, Recall

### 3. Visualisasi
- Heatmap korelasi antar fitur
- Scatter plot fitur vs target

## Tujuan Proyek
- Membangun model machine learning untuk deteksi dini gangguan insomnia
- Menyediakan solusi berbasis data yang dapat dimanfaatkan di bidang kesehatan mental dan kebiasaan tidur

## Penulis
- Bilal (241552010004)
- Muhammad Thoriqurrahman Akrami (241552010014)

## Institusi
Sekolah Tinggi Manajemen Informatika dan Komputer Tazkia, Fakultas Teknik Informatika

## Lisensi Dataset
Lisensi: Creative Commons CC BY 4.0

---

> *Proyek ini dibuat sebagai bagian dari tugas besar UTS untuk mata kuliah yang diampu oleh Bapak Hendri Kharisma, S.Kom, M.T.*
