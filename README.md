# Analisis dan Prediksi Kualitas Udara Menggunakan Data Polusi di Amerika Serikat Berbasis AI

## Latar Belakang

Kualitas udara merupakan salah satu indikator penting dalam kesehatan lingkungan dan masyarakat. Paparan jangka panjang terhadap polutan seperti PM2.5, PM10, CO, NO2, dan O3 telah terbukti meningkatkan risiko penyakit pernapasan dan jantung. Dalam proyek ini, kami menganalisis data polusi udara dari berbagai kota di Amerika Serikat dengan tujuan menggali wawasan penting dan membangun model prediktif berbasis machine learning.

Proyek ini juga memanfaatkan AI (IBM Granite Model) untuk menghasilkan insight otomatis dari hasil analisis, sebagai bukti penerapan kecerdasan buatan dalam sains data lingkungan.

---

## Tujuan Proyek

- Menganalisis tren dan konsentrasi berbagai polutan di kota-kota besar di AS.
- Mengidentifikasi faktor utama penyebab kualitas udara buruk.
- Memprediksi kualitas udara (baik/buruk) berdasarkan level polusi menggunakan model machine learning.
- Menggunakan AI untuk menyarikan insight dari hasil analisis secara otomatis.

---

## Dataset

- **Judul:** US Pollution Data (2000–2016)
- **Sumber:** [Kaggle – US Pollution](https://www.kaggle.com/datasets/sogun3/uspollution)
- **Fitur utama:** PM2.5, PM10, SO2, NO2, CO, O3, Kota, Negara bagian, Tanggal
- **Target prediksi:** Kualitas udara (`Baik` atau `Buruk`, berdasarkan threshold PM2.5)

---

## Insight & Temuan

- Polutan **PM2.5** adalah faktor dominan dalam klasifikasi kualitas udara buruk.
- **Los Angeles** dan **Houston** memiliki konsentrasi PM2.5 tertinggi, diduga akibat aktivitas industri dan transportasi padat.
- **Musim panas** menunjukkan tren peningkatan polusi terutama O3, sehingga intervensi pada bulan Juli–Agustus sangat disarankan.
- Model **Random Forest** mampu mengklasifikasikan kualitas udara dengan akurasi sekitar **85%**, menjadikannya kandidat kuat untuk sistem peringatan dini.
- Korelasi kuat ditemukan antara **PM10 dan NO2**, terutama di wilayah urban padat.

---

## AI Support (Granite Model)

- **IBM Granite Model** digunakan untuk menghasilkan insight ringkasan dari analisis secara otomatis melalui prompt LLM.
- Model ini membantu meringkas hasil analisis statistik dan memformulasikan rekomendasi kebijakan lingkungan secara efisien.

---

##  Tools yang Digunakan

- **Google Colab** – untuk eksplorasi data, visualisasi, dan training model
- **Python** – library: `pandas`, `seaborn`, `matplotlib`, `sklearn`, `numpy`
- **IBM Granite / Watsonx** – untuk AI-powered insight summarization

---

## Rekomendasi

1. Fokus penanganan polusi udara di kota industri dengan konsentrasi PM2.5 tinggi.
2. Lakukan intervensi berbasis waktu pada musim panas untuk menekan lonjakan O3.
3. Integrasikan model prediksi kualitas udara dalam dashboard monitoring lingkungan pemerintah.

---

## 📬 Kontak

Capstone Project oleh:  
Nama: Muhammad Fiqih Mu'azaidin  
Email: muazaidinmfiqih@gmail.com
Universitas: Universitas Negeri Surabaya  
Tahun: 2025

