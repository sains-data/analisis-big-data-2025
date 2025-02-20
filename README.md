# Praktikum Analisis Big Data 2025 - Program Studi Sains Data ITERA

## 📌 Deskripsi
Repositori ini berisi Laporan dan hasil praktikum dari mata kuliah **SD4204 Analisis Big Data** yang diselenggarakan oleh **Program Studi Sains Data, Institut Teknologi Sumatera (ITERA)**. Praktikum ini dirancang untuk memberikan pemahaman mendalam tentang konsep, teknik, dan implementasi dalam analisis Big Data, mulai dari pengumpulan data hingga penerapan model pembelajaran mesin.

## 📚 Struktur Modul
Praktikum ini terdiri dari **9 modul** dengan berbagai aspek penting dalam Analisis Big Data:

### 📌 **Modul 1: Pengantar Big Data & Kompleksitas Masalah (Descriptive Analytics)**
- Definisi dan karakteristik Big Data (Volume, Variety, Velocity, Veracity, Value)
- Kompleksitas masalah dalam skala besar
- Pengenalan alat dan platform Big Data
- 🔹 Dataset Open-Source:
✅ [NYC Taxi & Limousine Commission Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page): Data perjalanan taksi dari NYC
-🔹 Indikator: 
    - Eksplorasi skala besar dengan AWS Athena menggunakan SQL query.
    - Visualisasi distribusi data dalam S3 menggunakan EDA (Exploratory Data Analysis) melalui packaging python seperti pandas, seaborn, matplotlib, dan scipy.


### 📌 **Modul 2: Koleksi & Klasifikasi Data (Descriptive & Diagnostic Analytics)**
- Sumber data dalam Big Data (API, Web Scraping, Sensor Data, dll.)
- Klasifikasi data: terstruktur, semi-terstruktur, dan tidak terstruktur
- Pengelolaan dataset besar menggunakan Python (Pandas)
-🔹 Dataset Open-Source:
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/):Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
✅ [OpenWeatherMap API](https://openweathermap.org/api): Data cuaca real-time
-🔹 Indikator:
  - Mengumpulkan dan mengklasifikasikan menggunakan Hadoop dan Hive
  - Melakukan eksplorasi dan klasifikasi data cuaca berdasarkan pola cuaca tertentu menggunakan metode statistik dasar dan visualisasi data (pandas dan matplotlib/seaborn)
  - Menjelaskan faktor penyebab perubahan cuaca ekstrem berdasarkan data historis (diagnostic)


### 📌 **Modul 3: Manajemen Data & Ekstraksi Insight (Diagnostic Analytics)**
- Manajemen Data (pengelolaan, pemrosesan, dan penyimpanan)
- Ekstraksi Insight (analisis penyebab suatu fenomena dengan Diagnostic Analytics)
- Teknik eksplorasi data (EDA) untuk ekstraksi insight
-🔹 Dataset Open-Source:
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
✅ [OpenWeatherMap API](https://openweathermap.org/api): Data cuaca real-time
-🔹 Indikator:
  - Melakukan Manajemen Data dengan Hadoop HDFS dan SparkSQL
  - Melakukan membaca & memproses data dengan PySpark
  - Analisis dengan EDA hubungan faktor data cuaca dan data gempa

### 📌 **Modul 4: Arsitektur Big Data & Siklus Analitik (Prescriptive Analytics)**
- Arsitektur sistem Big Data (Hadoop, Hive, Spark, Kafka, SparkML, PySpark )
- Siklus analitik data dalam Big Data
- Distributed computing dan cloud computing untuk analitik
-🔹 Dataset Open-Source:
✅ IoT Device with Sensor for Temperature and Humadity in ITERA
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Membangun Arsitektur Big Data
 


### 📌 **Modul 5: Business Understanding & Algoritma Big Data (Predictive & Prescriptive Analytics)**
- Perumusan masalah bisnis dalam konteks Big Data, Bagaimana kita memanfaatkan Big Data untuk memprediksi tren bisnis?
- Algoritma pemrosesan data skala besar, Algoritma apa yang efektif untuk menganalisis data skala besar?
- Bagaimana analitik preskriptif dapat membantu dalam pengambilan keputusan strategis?
-🔹 Dataset Open-Source:
✅ [BBRI.JK Stock Data](https://www.kaggle.com/datasets/cgyputra/bbri-jk-stock-data): Historical Stock Prices of BBRI.JK (Bank BRI) – Daily Trading Data
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Membangun model prediktif dengan SparkML dan PySpark
  - Menganalisis pola harga saham untuk keputusan investasi
  - Menerapkan analisis prediktif dan preskriptif dalam pengambilan keputusan bisnis

### 📌 **Modul 6: Web Scraping, Preprocessing & Visualisasi Big Data (Cognitive Analytics)**
- Teknik pengambilan data dari web (BeautifulSoup, Selenium, Scrapy)
- Data preprocessing dalam Big Data (handling missing values, scaling, encoding, dsb.)
- Visualisasi data skala besar (Matplotlib, Seaborn, Plotly, Power BI, Tableau)
-🔹 Dataset Open-Source:
✅ [Wikipedia API](https://wikimedia.org/api/rest_v1/): Data artikel Wikipedia
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Melakukan Preprocessing Data termasuk handling missing values, scaling, encoding, dan teknik pembersihan data lainnya untuk meningkatkan kualitas data
  - Menyimpan dan Mengelola Data Skala Besar menggunakan Hadoop HDFS atau Apache Spark
  - Membuat Visualisasi Data Interaktif yang dideploy pada Streamlit untuk menggambarkan pola dan insight dari data Wikipedia
  - Menganalisis tren dari data Wikipedia dan menarik kesimpulan berbasis data dengan pendekatan Cognitive Analytics


### 📌 **Modul 7: Pembelajaran Mesin dalam Big Data (Predictive & Cognitive Analytics)**
- Implementasi Machine Learning dalam Big Data
- Optimasi model menggunakan teknik distribusi (MLlib)
- Model evaluasi dalam skala besar
-🔹 Dataset Open-Source:
✅ [HANDFUL project energy data](https://www.kaggle.com/datasets/plegmalabs/handful-project-energy-data) :High-granularity electricity consumption data from a food production facility
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Mengimplementasikan Algoritma Machine Learning dalam lingkungan Big Data menggunakan Apache Spark MLlib atau PySpark
  - Melakukan Preprocessing Data seperti handling missing values, feature scaling, encoding, dan teknik pembersihan lainnya untuk meningkatkan kualitas model
  - Membangun Model Machine Learning seperti Regresi, Decision Tree, Random Forest, atau Gradient Boosting pada dataset HANDFUL project energy data
  - Menggunakan Teknik Distribusi untuk pelatihan model dalam skala besar menggunakan Apache Spark MLlib
  - Melakukan Evaluasi Model dalam Skala Besar dengan metrik evaluasi seperti RMSE, MSE, R², Precision, Recall, dan F1-score
  - Mengoptimalkan Model dengan hyperparameter tuning dan teknik distribusi untuk meningkatkan performa prediksi
  - Menganalisis dan Menginterpretasikan Hasil Model serta memberikan insight berbasis Predictive & Cognitive Analytics

### 📌 **Modul 8: Pengolahan Big Data dan Deploying Model (Prescriptive Analytics)**
- End-to-End Data Pipeline – Bagaimana data mengalir dari sumber (dataset sebelumnya) hingga siap digunakan untuk model prediksi.
- Model Deployment – Mengubah model machine learning menjadi API yang dapat diakses.
- Scalability & Performance – Bagaimana model tetap efisien saat menangani banyak permintaan.
- Monitoring & Maintenance – Bagaimana model diperbarui dan dipantau untuk mempertahankan performanya.
-🔹 Dataset Open-Source:
✅ IoT Device with Sensor for Temperature and Humadity in ITERA
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Merancang data pipeline (Spark dan Kafka)
  - Model Deployment dengan FASTAPI
  - Menerapkan strategi A/B testing atau shadow deployment untuk validasi sebelum mengganti model lama
  - Testing dan Monitoring Model


### 📌 **Modul 9: Post-Big Data & Keamanan Big Data**
- Python/PySpark untuk membuat fungsi hashing & enkripsi pada data sensitif.
- Simulasi bagaimana data masking diterapkan di Hive/Spark untuk melindungi informasi pengguna.
- Bandingkan metode enkripsi (AES, SHA256) dan terapkan pada pipeline Big Data.
-🔹 Dataset Open-Source:
✅ IoT Device with Sensor for Temperature and Humadity in ITERA
✅ [BMKG API](https://data.bmkg.go.id/prakiraan-cuaca/): Data prakiraan cuaca real-time di Indonesia
✅ [BMKG API](https://data.bmkg.go.id/gempabumi/): Data kejadian gempabumi yang terjadi di seluruh wilayah Indonesia
-🔹 Indikator:
  - Memahami perbedaan antara Data Masking dan Enkripsi dalam Big Data.
  - Mengimplementasikan masking dengan teknik regex dalam Hive/PySpark.
  - Menerapkan enkripsi AES pada data sensitif sebelum penyimpanan di HDFS.
  - Membuat pipeline data yang mengamankan informasi sensitif dalam sistem Big Data.
  - Menjelaskan bagaimana masking dan enkripsi dapat memenuhi regulasi di Indonesia

## 🏗️ **Struktur Repository**
```
/ (root)
├── index.html
├── kelompok-1/
│   ├── modul-1.html
│   ├── modul-2.html
│   ├── assets/  <-- Jika butuh gambar/grafik
│   └── styles.css (opsional)
├── kelompok-2/
│   ├── modul-1.html
│   ├── modul-2.html
│   ├── assets/
│   └── styles.css
├── kelompok-3/
│   ├── modul-1.html
│   ├── modul-2.html
│   ├── assets/
│   └── styles.css
...
└── README.md
```
📌 **Setiap folder kelompok memiliki file modul-1.html yang merupakan file hasil konversi jupyter notebook.**

## 🎯 **Kolaborasi**
1. **Kelompok Praktikum:**
   - Setiap kelas dibagi menjadi **14 tim**, masing-masing mengerjakan 9 modul.
   - Tiap tim memiliki folder khusus dalam repository untuk menyimpan hasil kerja.
   - Tugas Kolaboratif adalah setiap tim mengerjakan kode di lab bersama sesuai pembagian tugas
   - Mengunggah hasil praktikum dalam format **HTML** ke GitHub Pages.
   
2. **Laporan Individu:**
   - Mengembangkan solusi analitik menggunakan teknik analitik berdasarkan hasil yang ditemukan ketika mengerjakan tugas kolaboratif.
   - Membuat laporan individu sesuai dengan hasil yang dikerjakan bersama dengan tim ketika di lab
   
   
## 🚀 **Akses GitHub Pages**
Hasil kerja tiap kelompok dapat diakses melalui:
```
https://orgname.github.io/praktikum-bigdata-2025/kelompok-1/modul-1.html
https://orgname.github.io/praktikum-bigdata-2025/kelompok-2/modul-2.html
...
```

## 📌 **Kontribusi & Panduan Penggunaan**
1. **Fork repo ini** ke akun masing-masing (Perwakilan).
2. **Clone repo** untuk mengerjakan tugas secara lokal:
   ```bash
   git clone https://github.com/orgname/praktikum-bigdata-2025.git
   ```
3. **Upload hasil praktikum ke folder kelompok masing-masing**
4. **Buat Pull Request (PR)** untuk review sebelum file masuk ke repo utama.

## 📢 **Kontak & Bantuan**
📩 Untuk pertanyaan atau bantuan teknis, hubungi asisten praktikum atau buka **Issues** di repo ini.

---
🚀 **Selamat belajar dan eksplorasi dalam dunia Big Data!** 🚀

