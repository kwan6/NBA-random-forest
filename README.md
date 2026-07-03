# NBA Random Forest

Project ini merupakan implementasi algoritma Random Forest untuk melakukan analisis dan prediksi data NBA menggunakan pendekatan machine learning. Tujuan utama dari project ini adalah mengeksplorasi bagaimana statistik pemain atau pertandingan NBA dapat digunakan untuk membangun model prediksi berbasis data. Random Forest merupakan salah satu metode ensemble learning yang banyak digunakan karena mampu menangani data kompleks dengan baik dan relatif tahan terhadap overfitting. :contentReference[oaicite:0]{index=0}

## Latar Belakang

Dalam beberapa tahun terakhir, analisis data telah menjadi bagian penting dalam dunia olahraga, termasuk NBA. Statistik pemain dan tim dapat dimanfaatkan untuk mendapatkan insight mengenai performa pemain maupun memprediksi hasil di masa mendatang. Machine learning, khususnya Random Forest, sering digunakan dalam analisis olahraga karena mampu mempelajari pola dari data historis secara efektif. :contentReference[oaicite:1]{index=1}

## Tujuan Project

- Menerapkan algoritma Random Forest pada dataset NBA.
- Melakukan eksplorasi dan analisis data NBA.
- Membangun model prediksi berdasarkan statistik pemain atau pertandingan.
- Mengevaluasi performa model menggunakan metrik evaluasi yang sesuai.

## Dataset

Dataset yang digunakan berisi statistik NBA yang digunakan sebagai fitur dalam proses pelatihan model.

Contoh atribut yang digunakan antara lain:

- Points (PTS)
- Assists (AST)
- Rebounds (REB)
- Field Goal Percentage (FG%)
- Minutes Played (MP)
- Dan statistik lainnya

## Metodologi

Tahapan yang dilakukan dalam project ini meliputi:

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Data Splitting (Train-Test Split)
6. Model Training menggunakan Random Forest
7. Model Evaluation

## Algoritma

Model utama yang digunakan:

- Random Forest

Random Forest merupakan algoritma ensemble berbasis decision tree yang bekerja dengan membangun banyak pohon keputusan dan menggabungkan hasil prediksinya untuk meningkatkan akurasi model. :contentReference[oaicite:2]{index=2}

## Tools dan Library

Project ini dikembangkan menggunakan:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Struktur Project

```bash
NBA-random-forest/
│
├── data/
├── notebooks/
├── model/
├── results/
├── README.md
└── requirements.txt
```

## Cara Menjalankan

Clone repository:

```bash
git clone https://github.com/kwan6/NBA-random-forest.git
```

Masuk ke folder project:

```bash
cd NBA-random-forest
```

Install dependency:

```bash
pip install -r requirements.txt
```

Jalankan notebook atau script utama sesuai kebutuhan.

## Evaluasi

Model dievaluasi menggunakan metrik evaluasi machine learning seperti:

- Accuracy
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

*(Sesuaikan kembali dengan metrik yang benar-benar digunakan pada project.)*

## Hasil

Hasil eksperimen menunjukkan bahwa Random Forest mampu mempelajari pola dari data NBA dan menghasilkan prediksi dengan performa yang cukup baik pada dataset yang digunakan.

## Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan:

- Menambahkan dataset dengan musim NBA terbaru.
- Mencoba algoritma lain seperti XGBoost atau Gradient Boosting.
- Melakukan hyperparameter tuning.
- Membuat dashboard visualisasi hasil prediksi.

## Author

**Muhammad Noer Attalah Dzahkwan**

Universitas Amikom Yogyakarta

## License

Project ini dibuat untuk keperluan pembelajaran dan akademik.
