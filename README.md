# Analisis Segmentasi dan Channel Pelanggan June 2012 - June 2014: Kunci Efisiensi Pemasaran Carrefour

## 📌 Latar Belakang

Carrefour menghadapi persaingan yang semakin ketat, terutama dalam efisiensi biaya pemasaran. Strategi promosi yang masih bersifat umum membuat biaya tinggi namun hasil kurang optimal. Padahal, sebagian besar pendapatan justru berasal dari pelanggan bernilai tinggi.

Selain itu, perbedaan perilaku belanja melalui channel **toko fisik, katalog, maupun online** belum pernah dievaluasi mendalam. Dengan memahami segmen pelanggan dan channel yang efektif, Carrefour dapat menekan biaya pemasaran dan meningkatkan retensi pelanggan.

## 👥 Stakeholder

* **Tim Manajemen Bisnis & Analisis Carrefour** sebagai pengambil keputusan utama terkait strategi pelanggan, produk, dan distribusi.

## ❓ Permasalahan Utama

1. Bagaimana cara mengurangi pengeluaran pemasaran dengan segmentasi pelanggan?
2. Produk mana yang paling relevan untuk dipromosikan ke segmen tertentu?
3. Channel pembelian mana yang paling berkontribusi terhadap penjualan & loyalitas pelanggan?

## 🎯 Goal

* Mengidentifikasi segmen pelanggan bernilai tinggi.
* Menentukan produk relevan untuk tiap segmen.
* Mengevaluasi channel (toko fisik, katalog, online) paling efektif dalam meningkatkan penjualan dan retensi.

## 🛠️ Analytical Approach

1. **Data Understanding & Preprocessing**

   * Cleaning: imputasi pendapatan, menangani outlier, normalisasi status pernikahan, konversi tanggal bergabung → *tenure*.
   * Feature engineering: variabel `Total_Spending`, `OverallResponse`.

2. **Segmentasi Pelanggan**

   * Analisis pelanggan yang merespons vs tidak merespons kampanye.
   * Clustering berbasis demografi, perilaku belanja, dan pendapatan.

3. **Analisis Produk**

   * Pola pengeluaran pada kategori (wine, daging, buah, ikan, manisan, emas).
   * Identifikasi produk unggulan tiap segmen.

4. **Analisis Channel**

   * Evaluasi kontribusi toko fisik, katalog, dan online.
   * Hubungan channel dengan karakteristik pelanggan.

5. **Rekomendasi Strategis**

   * Integrasi hasil segmentasi + produk + channel → strategi pemasaran yang tepat sasaran.

## 📂 Dataset

Periode data: **Juni 2012 – Juni 2014**
Dataset: [Supermarket Customers](https://drive.google.com/file/d/1lGG2nBWS5lVEpmmBZp2r0Koesa4t6c7W/view?usp=drive_link)

**Variabel utama:**

* Demografi: `Year_Birth`, `Education`, `Marital_Status`, `Income`
* Spending: `MntWines`, `MntMeatProducts`, `MntFruits`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`
* Channel: `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`, `NumWebVisitsMonth`
* Campaign response: `AcceptedCmp1–5`, `Response`

## 📊 Insight Utama

* Ditemukan beberapa **segmen pelanggan** dengan perilaku belanja berbeda (misalnya: *high spender*, *budget-conscious*, *online-oriented*).
* Produk unggulan tiap segmen berbeda, misalnya **wine & meat** untuk pelanggan premium, sedangkan **fruits & sweets** untuk keluarga muda.
* Channel **toko fisik** tetap dominan, tetapi **online** tumbuh signifikan untuk segmen tertentu.

## 🛠️ Tools

* Python: `pandas`, `numpy`
* Visualisasi: `matplotlib`, `seaborn`
* Machine Learning: `scikit-learn` (clustering & evaluasi)

## 🚀 Cara Menjalankan

1. Clone repository

   ```bash
   git clone https://github.com/username/repo-name.git
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook

   ```bash
   jupyter notebook Dian\ Margaretha\ Nainggolan_Capstone\ Project\ Module\ 2_Supermarket\ Customers.ipynb
   ```

## ✨ Author

Dian Margaretha Nainggolan
