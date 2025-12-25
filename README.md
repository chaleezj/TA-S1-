# Tugas Akhir S1 – Klasifikasi Bunga Anggrek Menggunakan CNN VGG-19

## Identitas

* **Nama**: Yudha Nugraha
* **Program Studi**: S1 Teknik Informatika
* **Universitas**: Universitas Dian Nuswantoro
* **Tahun Lulus**: 2025

---

## Judul Tugas Akhir

**Klasifikasi Citra Bunga Anggrek Menggunakan Convolutional Neural Network (CNN) dengan Arsitektur VGG-19**

---

## Deskripsi Singkat

Repository ini berisi implementasi dan dokumentasi **Tugas Akhir (Skripsi) jenjang S1** yang membahas tentang klasifikasi citra bunga anggrek menggunakan metode **Deep Learning**, khususnya **Convolutional Neural Network (CNN)** dengan arsitektur **VGG-19**.

Penelitian ini bertujuan untuk mengklasifikasikan bunga anggrek ke dalam beberapa genus berdasarkan citra digital, serta menganalisis pengaruh perbedaan sumber dataset terhadap performa model.

---

## Dataset

Dataset yang digunakan terdiri dari **tiga sumber utama**:

1. **Dataset Pribadi**

   * Diambil langsung oleh penulis menggunakan kamera pribadi
   * Fokus pada bagian **kelopak bunga anggrek**
   * Memiliki variasi pencahayaan dan sudut pengambilan gambar

2. **Dataset Kaggle**

   * Dataset publik dari Kaggle
   * Menampilkan bunga anggrek dengan **batang, daun, atau pot** yang masih terlihat

3. **Dataset Gabungan**

   * Kombinasi dataset pribadi dan dataset Kaggle

### Kelas / Genus Anggrek

Dataset mencakup **5 genus anggrek**, masing-masing ±250 citra:

* Cattleya
* Dendrobium
* Phalaenopsis
* Paphiopedilum
* Vanda

---

## Metode yang Digunakan

* **Model**: Convolutional Neural Network (CNN)
* **Arsitektur**: VGG-19 (Transfer Learning)
* **Framework**: TensorFlow & Keras
* **Preprocessing**:

  * Resize citra
  * Normalisasi
  * Data augmentation

---

## Lingkungan Pengembangan

* **Bahasa Pemrograman**: Python
* **Platform**: Google Colab
* **Perangkat**: Laptop ASUS Nitro 5
* **Library Utama**:

  * TensorFlow
  * Keras
  * NumPy
  * OpenCV
  * Matplotlib
  * Scikit-learn

---

## Evaluasi Model

Evaluasi performa model dilakukan menggunakan:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Hasil pengujian menunjukkan bahwa penggunaan **dataset gabungan** memberikan performa klasifikasi yang lebih stabil dibandingkan penggunaan satu sumber dataset saja.

---

## Struktur Folder (Contoh)

```
├── dataset/
│   ├── pribadi/
│   ├── kaggle/
│   └── gabungan/
├── preprocessing/
├── model/
├── training/
├── evaluation/
├── results/
└── README.md
```

---

## Tujuan Penelitian

* Mengimplementasikan CNN VGG-19 untuk klasifikasi bunga anggrek
* Menganalisis pengaruh perbedaan sumber dataset terhadap akurasi model
* Memberikan referensi penelitian di bidang **computer vision dan klasifikasi citra tanaman**

---
