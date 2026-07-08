# Customer Segmentation using Gaussian Mixture Model (GMM)

## 📌 Deskripsi
Proyek ini merupakan implementasi algoritma **Gaussian Mixture Model (GMM)** untuk melakukan *customer segmentation* menggunakan **Mall Customer Dataset**. Tujuan dari proyek ini adalah mengelompokkan pelanggan berdasarkan karakteristik yang dimiliki sehingga dapat membantu memahami perilaku pelanggan.

Metode yang digunakan termasuk **Unsupervised Learning** karena proses pengelompokan dilakukan tanpa menggunakan label.

---

## 📂 Dataset

Dataset yang digunakan adalah **Mall Customer Segmentation Dataset** yang terdiri dari **200 data pelanggan** dengan 5 fitur:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Pada proses clustering hanya digunakan tiga fitur:

- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🤖 Metode

Metode utama yang digunakan adalah **Gaussian Mixture Model (GMM)**.

Tahapan pengerjaan proyek meliputi:

1. Import library
2. Membaca dataset
3. Memahami dataset
4. Visualisasi data
5. Pemilihan fitur
6. Standardisasi data menggunakan StandardScaler
7. Menentukan jumlah cluster terbaik menggunakan BIC dan AIC
8. Membangun model Gaussian Mixture Model
9. Melakukan clustering
10. Evaluasi menggunakan Silhouette Score
11. Analisis karakteristik setiap cluster

---

## 📚 Library

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Library utama Machine Learning:

- GaussianMixture
- StandardScaler
- silhouette_score

---

## 📊 Hasil

Hasil yang diperoleh dari proyek ini adalah:

- Jumlah cluster terbaik (BIC): **4**
- Silhouette Score: **0.3734**
- Pelanggan berhasil dikelompokkan menjadi 4 cluster berdasarkan kemiripan umur, pendapatan tahunan, dan spending score.

---

## 📁 Struktur Repository

```
├── Mall_Customers.csv
├── GMM_MallCustomer.ipynb
├── README.md
└── laporan.pdf (opsional)
```

---

## 👩‍💻 Author

**Shela Rahma**

Program Studi Teknik Informatika

Universitas Esa Unggul
