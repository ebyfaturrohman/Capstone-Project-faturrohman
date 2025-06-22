
# Capstone Project — Cerdas Menyaring Suara Pelanggan

## 🧠 Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan dan meringkas komentar pelanggan e-commerce berbahasa Indonesia secara otomatis menggunakan teknologi Large Language Model (LLM). Dengan pendekatan ini, pemilik usaha atau tim Customer Service dapat memahami suara pelanggan secara efisien dan mengambil tindakan berdasarkan insight yang dihasilkan.

## 🎯 Tujuan
- Mengelompokkan komentar pelanggan menjadi kategori **pujian**, **keluhan**, dan **netral**
- Menghasilkan **ringkasan otomatis** dari kumpulan komentar
- Menyediakan **insight nyata** dan **rekomendasi actionable**
- Menerapkan AI (Granite-style) untuk tugas klasifikasi dan summarization

## 🗂️ Dataset
- Sumber: [Kaggle - E-Commerce Sampled Reviews in Bahasa Indonesia](https://www.kaggle.com/datasets/satyaahb/e-commerce-sampled-reviews-in-bahasa-indonesia)
- File: `Shopee_Sampled_Reviews.csv`
- Kolom digunakan: `content`, `score`

## ⚙️ Tools & Teknologi
- Platform Analisis: Google Colab
- Bahasa Pemrograman: Python
- Library:
  - `pandas`, `matplotlib`, `seaborn`
  - `transformers` (HuggingFace)
- Model AI:
  - `mT5` Multilingual Summarizer
  - `xlm-roberta` for zero-shot classification (simulasi IBM Granite)

## 🧪 Proses Analisis
1. Load dataset
2. Preprocessing teks komentar
3. Label otomatis berdasarkan `score`
4. Klasifikasi komentar dengan LLM zero-shot
5. Summarization per kategori
6. Visualisasi distribusi komentar
7. Insight dan rekomendasi

## 📊 Insight Utama
- Keluhan terbanyak: kemasan rusak & pengiriman lambat
- Pujian terbanyak: harga terjangkau & pelayanan cepat
- Komentar netral menyimpan banyak saran konstruktif

## 🧩 AI Support
- Klasifikasi: Zero-shot dengan `xlm-roberta`
- Summarization: `mT5 multilingual`
- Bahasa Indonesia, tanpa training tambahan

## ✅ Hasil Utama
- Komentar berhasil dikelompokkan otomatis
- Rangkuman representatif
- Insight mendalam dari ribuan komentar

## 📁 Struktur File
├── Capstone_Presentasi_Faturrohman.pptx
├── Shopee_Sampled_Reviews.csv
├── Capstone_Faturrohman.ipynb
└── README.md

## 🙏 Terima Kasih
Proyek ini dibuat dalam program **Data Classification and Summarization using IBM Granite** — Hactiv8 & IBM.
—

Faturrohman
