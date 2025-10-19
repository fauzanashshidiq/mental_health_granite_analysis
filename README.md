# 🧠 mental_health_granite_analysis

Proyek ini mendemonstrasikan penggunaan IBM Granite (melalui Replicate / LangChain wrapper) untuk menghasilkan insight dari dataset kesehatan mental.

Output berupa analisis pola umum, faktor risiko, serta prediksi berbasis profil individu.

Seluruh eksperimen dilakukan di lingkungan notebook (Google Colab / Jupyter) menggunakan Python.

Author: Muhammad Fauzan Ashshidiq

## 📂 Isi Repository

mental_health_granite_analysis.ipynb - notebook utama berisi seluruh workflow: setup, load dataset, EDA, Granite insight, dan prediksi demo.

dataset/survey.csv - dataset Mental Health in Tech Survey (Kaggle).

## 📊 Ringkasan Proyek

- Load & preprocess dataset.

  -- Kolom relevan yang digunakan: Age, Gender, Country, family_history, treatment, work_interfere, remote_work.

- Eksplorasi data (EDA).

  -- Analisis distribusi, korelasi antar variabel, serta visualisasi untuk memahami pola awal.

- Memanggil IBM Granite untuk:

  -- Menghasilkan insight dari sampel data (general patterns, key factors, dan tren).

  -- Membuat prediksi risiko.

  -- contoh: apakah profil individu Perlu Treatment atau Tidak Perlu Treatment, lengkap dengan alasan model.

## ⚙️ Teknologi yang digunakan

- Python (pandas, numpy, matplotlib, seaborn)

- LangChain Community + Replicate API

- IBM Granite model (ibm-granite/granite-3.3-8b-instruct)

- Google Colab (untuk token handling & runtime)

## Etika & Disclaimer

- Hasil model LLM bukan diagnosis klinis. Gunakan sebagai alat bantu analisis, bukan pengganti profesional.

- Jangan unggah atau gunakan data pribadi yang sensitif.

- Proyek ini dibuat untuk keperluan pembelajaran dan dokumentasi IBM skillsbuild x Hacktiv8 (Data).
