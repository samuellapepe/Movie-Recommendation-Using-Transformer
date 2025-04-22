# 🎬 **Movie Recommendation Using Transformer**

Sistem rekomendasi film berbasis model Transformer yang dilatih menggnuakan dataset MovieLens 1M. Proyek ini merupakan bagian dari tugas kelompok pada mata kuliah *Deep Learning*.

## 📁 **Dataset**
Dataset yang digunakan adalah data set MovieLens 1M, berisi informasi pengguna, film, dan rating. Dataset dapat diunduh [disini.](https://drive.google.com/file/d/1h6uydOD4ce0vrIKqTEYlLeb2ofp3BkoM/view?usp=sharing)

## ⚙️ **Fitur Proyek**
* Preprocessing data pengguna dan film
* Transformasi data menjadi format sekuensial untuk model Transformer
* Model rekomendasi berbasis arsitektur Transformer dari PyTorch
* Pelatihan model dan evaluasi kinerja

## 🧠 **Arsitektur Model**
Menggunakan TransformerEncoder dari PyTorch untuk mempelajari urutan film yang ditonton oleh pengguna dan memberikan rekomendasi film berikutnya.

Komponen penting:
* Embedding layer untuk ID film
* Positional encoding
* Transformer encoder layer
* Fully connected output layer

## 🛠️ **Dependencies**
Berikut library utama yang digunakan:
* torch
* torchtext
* pandas
* numpy

## 🏁 **Cara Menjalankan**
1. Clone repo ini:
<pre> git clone https://github.com/username/movie-recommender-transformer.git 
  cd movie-recommender-transformer </pre>
2. Jalankan notebook:
* Buka Movie Recommendation Using Transformer.ipynb
* Jalankan semua sel secara berurutan

👨‍👩‍👧‍👦 Anggota Kelompok
* Samuella Dyas Bejanakasih Pepe - 6162001056
* Nurul Mutiara Fadzriani Hazsanah - 6162001108
* Nicolas Dennis - 6162001126
