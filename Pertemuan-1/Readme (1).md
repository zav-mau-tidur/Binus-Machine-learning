# Laporan Analisis Data Iris - Zaviero Syauqi
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
  <br> Merupakan Data yang berisi panjang kelopak bunga Iris dan kategorisasinya

  | Jenis                   | Keterangan                                                                              |
  | ----------------------- | --------------------------------------------------------------------------------------- |
  | Sumber                  | Github |
  | Dataset Owner           | mwaskom |
  | Lisensi                 | MIT |
  | Kategori                | Numeric |
  | Usability               | 90% |
  | Jenis dan Ukuran Berkas | CSV (4 KB) |

  Setelah melakukan observasi pada dataset yang diunduh melalui _link_ Github, didapatkan informasi sebagai berikut :
  
  Detail penjelasan dari isi dataset

- **Jumlah Baris dan Kolom**
  <br> It has 150 rows and 5 columns

- **Fitur pada Data**
  <br> the dataset seems to consist of attributes of flowers

- **Bentuk Data**
  <br> it is shown that the numeric data has decimals therefore it is a float type data and the species category/attribute illustrates a object type data
- **Deskripsi Data**
  <br> data consist of 150 rows and 5 columns: four numerical features such ass (sepal_length/sepal_width/petal_length/petal_width)
  the feature mean describes the average out of 150 total data, the standard deviation shows how far apart/spreadout the data is(smallest value-highest)/the average distance, the minimum value shows the lowest value out of 150 total data meanwhile the maximum value shows the highest value out of 150 total data
  
  | Data               | sepal_length | sepal_width | petal_length | petal_width |
  |--------------------|--------------|-------------|--------------|-------------|
  | Total Data         | 150.000000   | 150.000000  | 150.000000   | 150.000000  |
  | Mean               | 5.843333     | 3.057333    | 3.758000     | 1.199333    |
  | Standard Deviation | 0.828066     | 0.435866    | 1.765298     | 0.762238    |
  | Minimum Value      | 4.300000     | 2.000000    | 1.000000     | 0.100000    |
  | Maximum Value      | 7.900000     | 4.400000    | 6.900000     | 2.500000    |

## Evaluation
This iris dataset describes data about the width and length of petals and sepals with the objective of flower classification based on those 4 attributes
