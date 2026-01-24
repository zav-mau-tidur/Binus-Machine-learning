# Laporan Analisis Data Iris - Azhar Rizki Zulma
## Domain Proyek

Melakukan analisis sederhana pada data Iris untuk mengetahui terkait data yang digunakan sebelum melakukan keseluruhan metode machine learning.

### Latar Belakang
  
Sebagai permulaan sebagai seorang machine learning engineer maka kita perlu mengetahui data yang kita gunakan dengan melakukan analisis data sebelum melakukan pembuatan proyek Machine Learning.

## Business Understanding

Analisis sederhana yang dilakukan untuk memahami data yang digunakan, seperti berapa total jumlah baris dan kolomnya, ada fitur apa saja dalam data tersebut, dan apa yang bisa diprediksi dari data tersebut.

### Problem Statements

Bagaimana Cara melakukan Analisis Data Sederhana pada Data Iris.

### Goals

Tujuan dari proyek ini adalah mengetahui tentang data yang digunakan, terdapat fitur-fitur apa saja pada data tersebut dan bisa digunakan untuk melakukan apa data Iris tersebut.

### Solution statements

Dengan memanfaatkan library pandas untuk mengelola data, maka kita dapat melakukan banyak hal dengan library pandas tersebut seperti mengetahui fitur apa saja pada data Iris tersebut, berapa total data yang ada dan lain sebagainya.
    
## Data Understanding
- **Informasi Dataset**
  <br> Merupakan Data yang berisi panjang kelopak bunga Iris dadn kategorisasinya

  | Jenis                   | Keterangan                                                                              |
  | ----------------------- | --------------------------------------------------------------------------------------- |
  | Sumber                  | Github |
  | Dataset Owner           | mwaskom |
  | Lisensi                 | MIT |
  | Kategori                | Numerik |
  | Usability               | 90% |
  | Jenis dan Ukuran Berkas | CSV (4 KB) |

  Setelah melakukan observasi pada dataset yang diunduh melalui _link_ Github, didapatkan informasi sebagai berikut :
  
  Detail penjelasan dari isi dataset

- **Jumlah Baris dan Kolom**
  <br> Jumlah Baris dan Kolom yang didapatkan adalah 150 Baris dengan 5 Kolom

- **Fitur pada Data**
  <br> Terdapat fitur pada data yang dapat digunakan sebagai kategorisasi spesies bunga iris yaitu pada kolom species.

- **Bentuk Data**
  <br> Data bertipe numerik dengan tipe data float, sedangkan pada kolom species memiliki tipe data object

- **Deskripsi Data**
  <br> Hasil dari deskripsi data, data memiliki rerata nilai sepal_length 5.843333, sepal_width 3.057333, petal_length 3.758000, dan petal_width 1.199333, dengan nilai tertingginya adalah 7.900000 dan terendahnya adalah 0.100000 dari keseluruhan data. Berikut adalah tabel detailnya.
  
  | Data               | sepal_length | sepal_width | petal_length | petal_width |
  |--------------------|--------------|-------------|--------------|-------------|
  | Total Data         | 150.000000   | 150.000000  | 150.000000   | 150.000000  |
  | Mean               | 5.843333     | 3.057333    | 3.758000     | 1.199333    |
  | Standard Deviation | 0.828066     | 0.435866    | 1.765298     | 0.762238    |
  | Minimum Value      | 4.300000     | 2.000000    | 1.000000     | 0.100000    |
  | Maximum Value      | 7.900000     | 4.400000    | 6.900000     | 2.500000    |

## Evaluation

Dari hasil analisis sederhana yang dilakukan bahwa data iris merupakan data panjang kelopak bunga dengan memiliki fitur untuk mengkategorisasikan spesie berdasarkan panjang kelopak bunga Iris. Dari data tersebut kita dapat melakukan berbagai hal seperti melakukan prediksi jenis spesies bunga iris berdasarkan panjang kelopak yang diinputkan atau melakukan analisis lebih lanjut untuk memahami lebih mendetail tentang bunga iris berdasarkan panjang kelopaknya.
