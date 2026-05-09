# Multi-Criteria-Decision-Support-System

Repository ini berisi kumpulan implementasi berbagai metode dalam **Sistem Pendukung Keputusan (SPK)** dan **Machine Learning dasar** yang digunakan untuk menyelesaikan permasalahan klasifikasi dan pengambilan keputusan berbasis data.
Setiap metode diimplementasikan menggunakan pendekatan sederhana (Excel / perhitungan manual) dengan tujuan utama untuk memahami konsep, alur, dan logika di balik masing-masing metode.

---

# Metode yang Digunakan

## 1. Simple Additive Weighting (SAW)
Metode **SAW** digunakan untuk menentukan alternatif terbaik melalui proses penjumlahan terbobot. Nilai setiap alternatif dinormalisasi terlebih dahulu agar berada pada skala yang sama, kemudian dikalikan dengan bobot kriteria dan dijumlahkan untuk menghasilkan skor akhir.
Cocok untuk: kasus dengan banyak alternatif dan kriteria sederhana

---

## 2. Weighted Product (WP)
Metode **WP** menggunakan pendekatan perkalian terbobot dalam mengevaluasi alternatif. Setiap nilai atribut dipangkatkan dengan bobotnya, kemudian dikalikan untuk menghasilkan nilai preferensi.
Cocok untuk: kasus yang sensitif terhadap perbedaan nilai antar alternatif

---

## 3. TOPSIS
Metode **TOPSIS** menentukan alternatif terbaik berdasarkan kedekatannya terhadap solusi ideal positif dan jaraknya dari solusi ideal negatif.
Cocok untuk: pengambilan keputusan berbasis jarak terhadap kondisi ideal

---

## 4. MOORA
Metode **MOORA** mengoptimalkan keputusan dengan membandingkan nilai kriteria benefit dan cost. Hasil akhir diperoleh dari selisih antara kedua komponen tersebut.
Cocok untuk: kasus optimasi multi-kriteria

---

## 5. Analytical Hierarchy Process (AHP)
Metode **AHP** digunakan untuk menentukan bobot kriteria melalui perbandingan berpasangan. Metode ini juga menyediakan uji konsistensi untuk memastikan penilaian yang logis.
Studi kasus: Pemilihan smartphone berdasarkan harga, performa, kamera, dan baterai

---

## 6. Profile Matching
Metode **Profile Matching** mengevaluasi tingkat kesesuaian antara profil kandidat dengan profil ideal melalui perhitungan selisih (gap).
Studi kasus:
* Penerimaan karyawan
* Pemilihan karyawan berdasarkan aspek akademik dan afektif

---

## 7. K-Nearest Neighbor (KNN)
Algoritma **KNN** mengklasifikasikan data berdasarkan kedekatannya dengan data latih menggunakan perhitungan jarak.
Studi kasus: klasifikasi biner (positif/negatif) berdasarkan dua atribut

---

## 8. Naive Bayes
Metode **Naive Bayes** merupakan algoritma klasifikasi berbasis probabilitas yang menggunakan Teorema Bayes.
Studi kasus:
* Prediksi bermain golf berdasarkan kondisi cuaca
* Diagnosis perbaikan laptop berdasarkan gejala

---

# Perbandingan Metode

Setiap metode memiliki karakteristik yang berbeda:

* **SAW** → sederhana dan mudah dipahami
* **WP** → lebih sensitif terhadap perbedaan nilai
* **TOPSIS** → mempertimbangkan solusi ideal
* **MOORA** → menyeimbangkan benefit dan cost
* **AHP** → kuat dalam penentuan bobot subjektif
* **Profile Matching** → fokus pada kesesuaian profil
* **KNN** → berbasis kedekatan data
* **Naive Bayes** → berbasis probabilitas

Pemilihan metode disesuaikan dengan karakteristik masalah yang dihadapi.

---

# Tools

* Microsoft Excel
* Perhitungan manual berbasis metode

---

# Tujuan Pengembangan

Proyek ini bertujuan untuk:
* Memahami berbagai metode SPK dan klasifikasi
* Membandingkan pendekatan yang berbeda dalam pengambilan keputusan
* Membangun dasar yang kuat sebelum implementasi ke bahasa pemrograman seperti Python

---

# 👤 Penutup

Portfolio ini menunjukkan eksplorasi berbagai pendekatan dalam pengolahan data dan pengambilan keputusan, mulai dari metode berbasis penjumlahan, perkalian, jarak, hingga probabilitas. Setiap metode dipelajari tidak hanya dari sisi implementasi, tetapi juga dari pemahaman konsep dan konteks penggunaannya.

---
