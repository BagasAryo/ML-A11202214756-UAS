# Klasifikasi Gambar MRI Tumor Otak

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

Proyek ini menggunakan Convolutional Neural Network (CNN) yang dikerjakan di google colab untuk mengklasifikasikan gambar MRI tumor otak menjadi dua kategori: Tumor dan No Tumor. Model ini dilatih dengan dataset gambar MRI tumor otak dan dapat digunakan untuk memprediksi jenis tumor pada gambar baru.

## Persyaratan

- Akun Google Colab
- GDrive
- Dataset Gambar MRI Tumor Otak

### Persiapan Dataset

- Download dataset yang ada pada kaggle - https://www.kaggle.com/code/pkdarabi/brain-tumor-detection-by-cnn-pytorch/input?select=Brain+Tumor+Data+Set
- Extract zip file yang sudah didownload ke folder mana saja, misalnya "Dataset tumor". Didalam folder Dataset tumor, terdapat 2 folder, brain tumor dan healthy.
- Buat folder baru dengan nama "Dataset_Brain_Tumor"
- Buat 2 folder lagi di dalam folder Dataset_Brain_Tumor untuk nanti di upload ke GDrive, folder Tumor untuk brain tumor dan folder Non_Tumor untuk healthy
- Pada masing-masing folder brain tumor dan healthy yang ada didalam folder dataset tumor otak, urutkan berdasarkan type dan copy sebanyak masing-masing 200 gambar ber-ekstensi jpg ke folder baru.

### Persiapan Google Drive
- Klik tombol Baru di sebelah kiri atas
- Klik tombol upload folder, upload folder bernama Dataset_Brain_Tumor

### Mengaktifkan Google Colaboratory (kalau sudah aktif, bisa di skip langkah ini)
- Klik tombol Baru di sebelah kiri atas
- Klik Lainnya
- Klik Hubungkan aplikasi lainnya
- Ketik Colaboratory pada pencarian
- Klik Colaboratory
- Klik Install

Buka google collab
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
Dan selamat mengerjakan
