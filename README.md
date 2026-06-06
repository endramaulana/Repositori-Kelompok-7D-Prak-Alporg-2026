# 📊 Analisis Data Kebahagiaan Dunia

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data kebahagiaan dunia (*Happiness and Satisfaction Dataset*) menggunakan metode statistik dan visualisasi data. Analisis difokuskan pada hubungan antara tingkat kebahagiaan, pendapatan, kepuasan hidup, dan faktor ekonomi lainnya.

## 🎯 Tujuan Analisis
1. Menghitung standar deviasi **Happy Score (0–10)** berdasarkan wilayah (*Region*)  
2. Memfilter negara dari **Asia & Eropa** dengan **Adjusted Satisfaction > 60**  
3. Membuat matriks korelasi antar variabel numerik dalam bentuk **Heatmap**  
4. Menampilkan distribusi **Median Income** dalam bentuk **Histogram + KDE**  

## 📈 Hasil Visualisasi
![Hasil Analisis](WhatsApp%20Image%202026-06-06%20at%2022.45.33.jpeg)

## 🧾 Penjelasan Grafik

**A. Standar Deviasi Happy Score per Region**  
Menunjukkan variasi kebahagiaan antar wilayah. Wilayah dengan variasi tertinggi adalah *Middle East and Northern Africa*, sedangkan *North America* memiliki variasi yang lebih rendah.

**B. Negara Asia & Eropa dengan Kepuasan > 60**  
Menampilkan negara dengan tingkat kepuasan tinggi, didominasi oleh negara Eropa seperti Denmark, Finland, dan Iceland.

**C. Heatmap Korelasi**  
- GDP dan income memiliki korelasi sangat kuat  
- Happy Score berkorelasi positif dengan kepuasan  
- Income inequality cenderung berdampak negatif  

**D. Distribusi Median Income**  
Distribusi tidak merata (skewed ke kanan), mayoritas negara berada di pendapatan rendah–menengah.

## ⚙️ Metodologi
- Data cleaning (menghapus missing values)  
- Filtering data  
- Analisis statistik (standar deviasi & korelasi)  
- Visualisasi data (Bar Chart, Heatmap, Histogram, KDE)  

## 🛠️ Tools & Library
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📂 Struktur Project
