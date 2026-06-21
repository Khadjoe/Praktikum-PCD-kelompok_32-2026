# Praktikum-PCD-kelompok_32-2026
## Nama Anggota
###  nama anggota : INDIRA RAMADHANI SABRINA 
###  nama anggota  : MIKA KHAIRAN DJUBIKIT
###  nama anggota : FIDO PRIASA SETYONO PUTRA

# Project Overview
Project ini merupakan implementasi Pengolahan Citra Digital (PCD) untuk melakukan klasifikasi varietas beras berdasarkan dataset gambar. Datasetnya: 

- daun sehat
- daun black rot

Tujuan utama: 
menemukan metode klasifikasi yang paling akurat untuk menegenali penyakit daun anggur dari citra, dengan cara membandingkan 3 algoritma (KNN, SVM, Random Forest) yang sama-sama menggunakan fitur tekstur GLCM dari daun yang sudah di-preprocessing sebelumnya.

Model klasifikasi pada project:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

---

# Kombinasi Preprocessing

| Percobaan | Tahapan Preprocessing |
|-----------|----------------------|
| Percobaan 1 | gray → median filter → ekualisasi |
| Percobaan 2 | gray → median filter → ekualisasi → sobel → roberts |
| Percobaan 3 | gray → median filter → ekualisasi → sobel → roberts → threshold → masking |

---
