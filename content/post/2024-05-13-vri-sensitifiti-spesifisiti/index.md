---
authors:
- admin
categories: ["Validitas dan Reliabilitas Instrument", "Kuliah", "Statistik", "R"]
date: "2024-05-13T00:00:00Z"
draft: false
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2024-05-13T00:00:00Z"
projects: []
subtitle: ""
summary: ""
slides: example
tags:
- Sensitivitas
- Spesifisitas
- Uji Statistik
- Diagnostik
title: Sensitivitas dan Spesifisitas
---

## Alat Skrining

Andaikan ditemukan sebuah penyakit baru yang sangat mematikan. Agar dapat mengurangi dampak dari penyakit tersebut, Pemerintah Negara X menggelontorkan anggaran untuk riset terhadap alat deteksi dini / *skrining* . Dari ratusan peneliti, terpilihlah 3 peneliti dengan inovasi Alat A, Alat B, dan Alat C, sebagai alat *skrining*. Setelah dilakukan percobaan, didapatkan data sebagai berikut:

```r

```

Menurut kalian, alat mana yang seharusnya dipilih oleh Pemerintah Negara X sebagai alat skrining penyakit baru tersebut? Berikan alasannya!

{{% callout note %}}
Instrumen deteksi dini memberikan hasil yang menunjukkan **_kemungkinan adanya paparan_**, karena umumnya membutuhkan pengujian lebih lanjut di laboratorium untuk mendapatkan hasil yang lebih akurat. Rentang waktu antara kemungkinan deteksi awal melalui skrining dan deteksi setelah munculnya gejala disebut _Detectable Pre-Clinical Phase_ atau DPCP. Jika suatu penyakit dapat teridentifikasi selama fase DPCP, maka pengobatan dapat dimulai lebih awal dan hasilnya dapat lebih positif.
{{% /callout %}}

## Pendahuluan

Dalam menentukan alat yang baik dalam melakukan sebuah pengukuran adalah dengan melihat tingkat akurasi alat tersebut. Pada *thermogun*, kebaikan dalam mengukur suhu tubuh adalah ketika ia mampu memberikan hasil yang cukup dekat *(akurat)* dengan hasil pengukuran standar. Pengukuran standar ini dinamakan dengan **Gold Standard**. Jika hasil pengukuran dari *thermogun* memiliki rata-rata selisih yang kecil (semisal 0.1$^\circ$C), maka dapat dikatakan bahwa *thermogun* memiliki hasil pengukuran yang akurat. **Namun bagaimana jika hasil pengukurannya memiliki deviasi standar yang tinggi?**

Namun tidak semua alat memiliki proses evaluasi alat seperti *thermogun*, sebagian alat hanya memberikan 2 hasil saja yaitu ya atau tidak; terpapar atau tidak; diabetes atau tidak; dsb. Pengujian pada alat-alat tersebut dapat dilakukan dengan menggunakan ukuran [Sensitivitas](#) dan [Spesifisitas](#).

## Sensitivitas dan Spesifisitas

[Sensitivitas](#) adalah nilai proporsi antara orang yang terdeteksi sakit ([**_true positives_**](#)) dibandingkan dengan seluruh orang yang benar-benar sakit ([**_true positives_** + **_false negatives_**](#)). Andaikan kita melakukan pengujian pada Alat A ke 10 orang yang sedang sakit. Jika ternyata hasil skrining menunjukkan bahwa 8 dari 10 orang terdeteksi sakit, maka sensitivitas Alat A adalah 8/10 atau 80%.

Sedangkan [Spesifisitas]($) adalah proporsi antara orang yang tidak terdeteksi sakit ([**_true negatives_**](#)) dibandingkan dengan seluruh orang yang benar-benar tidak sakit ([**_false positives_** + **_true negatives_**](#)). Andaikan kita melakukan skrining dengan Alat B kepada 10 orang yang tidak sakit. Jika hasil skrining menunjukkan bahwa terdapat 9 orang yang tidak sakit, maka hasil spesifisiti adalah 9/10 atau 90%.

<div class="figure">
<img src="https://thecompletemedic.com/images/core/research-diagnostic-table_original.png" />
<p class="caption" style="text-align: center"><span id="fig:tab-diagnstk"></span>Gambar 1: Tabel Diagnostik</p>
</div>

## Kegunaan dan Batasan

### Kegunaan

_Ability to **ruling out** a disease_<br />
Alat skrining dengan hasil sensitivitas yang tinggi menunjukkan bahwa alat skrining semakin baik kemampuannya untuk menyingkirkan kemungkinan penyakit pada individu yang sebenarnya sehat. Andaikan terdapat pasien yang terdeteksi tidak terpapar, maka nakes dapat langsung yakin bahwa pasien tersebut benar-benar tidak terpapar.

_Ability to **ruling in** a disease_<br />
Sedangkan alat skrining yang mendapatkan hasil spesifisitas tinggi menunjukkan bahwa alat skrining tersebut semakin baik kemampuannya untuk mengonfirmasi keberadaan penyakit pada individu yang sebenarnya menderita penyakit tersebut. Andaikan terdapat pasien yang terdeteksi terpapar, maka nakes dapat langsung yakin bahwa pasien tersebut benar-benar sedang terpapar.

### Batasan

Keterbatasan utama baik itu sensitivitas maupun sensitifitas adalah ketidakmampuannya dalam membantu nakes untuk mengukur besar peluang (probabilitas) bahwa pasien benar-benar terpapar jika hasil skrining menunjukkan bahwa pasien terdeteksi terpapar.

Ini karena sensitivitas dan spesifisitas ditentukan berdasarkan apakah seseorang memiliki penyakit atau tidak. Namun, saat Anda berinteraksi dengan pasien, mereka akan menunjukkan serangkaian gejala, bukan diagnosis, sehingga sulit untuk langsung mengetahui apakah mereka menderita penyakit atau tidak. Oleh karena itu, kita tidak bisa langsung menerapkan parameter ini pada pasien. 

{{% callout note %}}
Sensitivitas dan Spesifisitas merupakan salah satu uji validitas dalam kasus Uji Diagnostik. Kegunaannya dalam mengukur ketepatan alat ukur (atau alat skrinig) menunjukkan bahwa Sensitivitas dan Spesifisitas dapat menunjukkan tingkat keakuratan dalam pengukuran.
{{% /callout %}}

## License

Copyright 2023-present [Dimas BC Wicaksono](https://dwicaksono.netlify.app/).

Released under the [MIT](https://github.com/HugoBlox/hugo-blox-builder/blob/master/LICENSE.md) license.
