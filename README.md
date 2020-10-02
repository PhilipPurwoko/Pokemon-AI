# Pokemon-AI
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

Diberikan data pokemon berupa informasi karakteristik masing masing. Dilakukan sebuah preprocessing dan analisis data. Tugasnya adalah apa saja yang dapat dilakukan dengan data tersebut ?

## :ticket: Project Step by Step
- [x] Preprocessing data (Cleaning data, data conversion, feature selection, feature extraction)
- [x] Visualiasi data (Membuat grafik, bar, memvisualisasikan korelasi antar data)
- [x] Analisis data (Diperoleh kesimpulan, apa saja yang dapat dilakukan dengan data tersebut)
- [x] Machine Learning (Membuat permodelan dan melakukan tugas yang bisa dilakukan)

# :sparkles: Tugas Ditemukan
## Binary Classification
Melakukan Klasifikasi binary body style pokemon. Apakah pokemon tersebut memiliki body style `bipedal_tailed` atau `quadruped` berdasarkan data `['HP','Attack','Defense','Sp_Atk','Sp_Def','Speed']`

**Step by Step**
- [x] Memilah dataframe sesuai data yang diperlukan
- [x] Mengkonversi kategori data (string) dengan encoding (menjadi int)
- [x] Menggunakan `RandomForestClassifier` sebagai machine learning model
- [x] Melatih Model dan membuat prediksi
- [x] Mengkonversi ulang prediksi ke dalam data kategori (string)
- [x] Evaluasi model, untuk meningkatkan akurasi model
- [x] Resolusi

## Regression
Prediksi berat pokemon berdasarkan data `['HP','Attack','Defense','Sp_Atk','Sp_Def','Speed']`

**Step by Step**
- [x] Memilah dataframe sesuai data yang diperlukan
- [x] Menggunakan `RandomForestRegressor` sebagai machine learning model
- [x] Melatih Model dan membuat prediksi
- [x] Evaluasi model, untuk meningkatkan akurasi model
- [x] Resolusi