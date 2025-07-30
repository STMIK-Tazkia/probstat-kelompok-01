<!-- Banner -->
<p align="center">
  <img src="https://media.giphy.com/media/fxsqOYnIMEefC/giphy.gif" width="100%" alt="sleep banner">
</p>

<!-- Typing Text -->
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4B0082&center=true&vCenter=true&width=700&lines=Klasifikasi+Insomnia+dengan+Machine+Learning;Data+Gejala+dan+Pola+Tidur;Deteksi+Dini+Gangguan+Tidur+Insomnia+😴💤" alt="Typing SVG" />
</h1>

---

## Deskripsi Proyek

Proyek ini membangun model klasifikasi untuk mendeteksi **insomnia** berdasarkan **gejala dan kebiasaan tidur** menggunakan algoritma machine learning seperti **Logistic Regression** dan **Decision Tree**.

---

## Struktur Proyek

- ` Insomniac_data.xlsx` : Dataset gejala & pola tidur  
- ` thanksinsomnia.ipynb` : Notebook Jupyter (preprocessing, modeling, evaluasi, visualisasi)  
- ` Proposal-Modeling-Dataset-Insomnia.docx` : Penjelasan latar belakang, metodologi, dan perencanaan  

---

## Deskripsi Dataset

- **Sumber**: [Mendeley Data – Dataset of Insomniac and Normal People](https://data.mendeley.com/datasets/jr5n4prgfv/1)  
- **Fitur**: 10 fitur + 1 target (`Disorder`)  
- **Contoh Fitur**:
  - `Total_sleep_time(hour)`
  - `Satisfaction_of_sleep`
  - `Late_night_sleep`
  - `Wakeup_frequently_during_sleep`
  - `Sleep_at_daytime`
  - `Recent_psychological_attack`

---

## Metodologi

### 1. Preprocessing
- Konversi nilai kategorikal (`ya/tidak`) ke numerik (`1/0`)  
- Normalisasi data numerik  
- Split: 70% data latih, 30% data uji  

### 2. Modeling
- Algoritma: `Logistic Regression`, `Decision Tree Classifier`  
- Tools: `pandas`, `scikit-learn`, `seaborn`  
- Evaluasi: Akurasi, Confusion Matrix, Precision, Recall  

### 3. Visualisasi
- Korelasi antar fitur (heatmap)  
- Scatter plot fitur terhadap target  

---

## Tujuan Proyek

- Deteksi dini gangguan **insomnia** dengan **data-driven model**  
- Memberi kontribusi terhadap solusi kesehatan berbasis teknologi  

---

## Tim Pengembang

- **Bilal** (241552010004)  
- **Thoriqurrahman Akrami** (241552010014)

---

## Institusi

Sekolah Tinggi Manajemen Informatika dan Komputer Tazkia  
Fakultas Teknik Informatika

---

## Lisensi Dataset

Lisensi: [Creative Commons CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

>  *Proyek ini dibuat sebagai bagian dari tugas besar UTS untuk mata kuliah yang diampu oleh Bapak Hendri Kharisma, S.Kom, M.T.*

