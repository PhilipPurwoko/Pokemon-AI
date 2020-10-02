# Pokemon-AI
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
Diberikan data pokemon berupa informasi karakteristik masing masing. Dilakukan sebuah preprocessing dan analisis data. Tugasnya adalah apa saja yang dapat dilakukan dengan data tersebut ?

## :ticket: Project Step by Step
1. Preprocessing data (Cleaning data, data conversion, feature selection, feature extraction)
3. Visualiasi data (Membuat grafik, bar, memvisualisasikan korelasi antar data)
4. Analisis data (Diperoleh kesimpulan, apa saja yang dapat dilakukan dengan data tersebut)
5. Machine Learning (Membuat permodelan dan melakukan tugas yang bisa dilakukan)

# :sparkles: Tugas Ditemukan
## Binary Classification
Melakukan Klasifikasi binary body style pokemon. Apakah pokemon tersebut memiliki body style `bipedal_tailed` atau `quadruped` berdasarkan data `['HP','Attack','Defense','Sp_Atk','Sp_Def','Speed']`

### Step by Step
1. [x] Memilah dataframe sesuai data yang diperlukan
2. [x] Mengkonversi kategori data (string) dengan encoding (menjadi int)
3. [x] Menggunakan `RandomForestClassifier` sebagai machine learning model
4. [x] Melatih Model dan membuat prediksi
5. [x] Mengkonversi ulang prediksi ke dalam data kategori (string)
6. [x] Evaluasi model, untuk meningkatkan akurasi model
7. [x] Resolusi

## Regression
Prediksi berat pokemon berdasarkan data `['HP','Attack','Defense','Sp_Atk','Sp_Def','Speed']`

### Step by Step
1. [x] Memilah dataframe sesuai data yang diperlukan
2. [x] Menggunakan `RandomForestRegressor` sebagai machine learning model
3. [x] Melatih Model dan membuat prediksi
4. [x] Evaluasi model, untuk meningkatkan akurasi model
5. [x] Resolusi