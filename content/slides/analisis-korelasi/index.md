---
authors: ["Dimas BC Wicaksono"]
categories: ["Statistik"]
date: "2024-05-18T00:00:00Z"
slides:
  highlight_style: dracula
  theme: black
format:
  revealjs:
    incremental: true 
summary: Analisis Korelasi
tags: []
title: Analisis Korelasi
---

# Analisis Korelasi {#ankor}

[Dasar Biostatistika](#ankor) | [Dimas BC Wicaksono](#ankor)

---

## Konsep Korelasi {#konskor}

- [Analisis Korelasi](#konskor), metode statistika inferensial untuk mendapatkan derajat hubungan linier antar variabel (*bivariable*).
- [Koefisien Korelasi](#konskor), adalah ukuran derajat hubungan antar variabel.
- [Arah Hubungan](#konskor), arah hubungan pada koefisien korelasi adalah positif (+) dan negatif (-)

---

## Sifat Koefisien Korelasi {#sifat}

- Nilai koefisien korelasi berkisar antara -1 dan 1
- Nilai koefisien korelasi positif (+) menunjukkan [hubungan yang searah](#sifat). Artinya, apabila nilai variabel bebas meningkat, maka nilai variabel terikat juga ikut meningkat (begitu pula sebaliknya).
- Nilai koefisien korelasi negatif (-) menunjukkan [hubungan yang berlawanan arah](#sifat). Artinya, apabila nilai variabel bebas meningkat, maka nilai variabel terikat akan menurun (begitu pula sebaliknya).


---

<img src="https://www.questionpro.com/blog/wp-content/uploads/2020/04/Pearson-correlation-coefficient-1.jpg" alt="Image from Questionpro.com"/>
<figcaption>Gambar 1. Arah korelasi (Image from Questionpro.com)</figcaption>


---

## Analisis Korelasi dan Kausalitas

- Dalam KBBI menunjukkan bahwa kata "korelasi" artinya kejadian sebab akibat (kausalitas).
- Meski demikian, analisis korelasi dalam statistik tidak menunjukkan hal yang sama.
- Analisis Korelasi hanya menggambarkan keeratan hubungan seperti yang telah dijelaskan [sebelumnya](#konskor)


---

## Jenis Analisis Korelasi {#jenis}

- [Korelasi Pearson Product Moment](#jenis), untuk data yang berskala interval dan rasio.
- [Korelasi Rank Spearman](#jenis), untuk data yang berskala ordinal.
- [Korelasi Koefisien Kontigensi](#jenis), untuk data yang berskala nominal.

---

## Hipotesis Uji Korelasi {$hipotesis}

- Hipotesis:
  - `\(H_0:\)` Tidak ada korelasi antara variabel X dan Y
  - `\(H_1:\)` Terdapat korelasi antara variabel X dan Y
- Tingkat signifikansi -> 0.05 ($\alpha = 0.05$)


---

Apabila hasil uji menunjukkan nilai [_p-value_ yang kurang dari `\(\alpha\)` ($p-value \le \alpha$)](#hipotesis), keputusan pengujian adalah tolak `\(H_0\)`. Artinya terdapat korelasi antara kedua variabel.


---

## Kriteria Koefisien Korelasi {#kriteria}

- Selain hasil uji hipotesis, uji korelasi juga memberikan hasil besar koefisien korelasi.
- Kriteria korelasi dapat diklasifikasikan berdasarkan besar koefisien korelasinya:
  - 0.00 - 0.29, derajat hubungan sangat lemah
  - 0.30 - 0.49, derajat hubungan lemah
  - 0.50 - 0.69, derajat hubungan cukup kuat
  - 0.70 - 0.79, derajat hubungan kuat
  - 0.80 - 1, derajat hubungan sagat kuat
  

--- 

## Uji Korelasi dengan SPSS {#spss}

[Data Latihan](https://docs.google.com/spreadsheets/d/1cQFIUc7nAqli9rPRkHjHNGL6mXhTLwj1rl_vSH2uunE/edit?usp=sharing)


---

# Questions?


---

# Terima Kasih
