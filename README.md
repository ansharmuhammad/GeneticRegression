# Prediksi Nilai Tukar Mata Uang JPY -> USD (Algoritma Genetika dan Multiple Linear Regression)
## optimasi regresi dengan algoritma genetika untuk prediksi nilai tukar mata uang JPY -> USD.

## Data

data yang digunakan adalah data nilai tukar mata uang JPY->USD dari 2014 - 2016. Nilai yang dipakai adalah nilai Close

sample data: 

| Indeks | Tanggal    | Jam  | Open    | High    | Low     | Close   | Volume |
|--------|------------|------|---------|---------|---------|---------|--------|
| 0      | 2014.01.02 | 0:00 | 105.294 | 105.435 | 104.538 | 104.776 | 40216  |
| 1      | 2014.01.03 | 0:00 | 104.782 | 104.864 | 104.067 | 104.767 | 46159  |

## Metode yang Dipakai

### Multiple Linear Regression

Multiple Linear Regression digunakan untuk memprediksi nilai tukar mata uang. Nilai sliding window yang dipakai adalah 5.

<img src="https://image.slidesharecdn.com/8-1209490505240696-9/95/multiple-linear-regression-16-638.jpg?cb=1489720634" width="400" />
### Algoritma Genetika

Algoritma Genetika digunakan untuk mencari nilai koefisien MLR terbaik.
<img src="https://www.researchgate.net/profile/John_Geraghty2/publication/236179246/figure/fig1/AS:299498850013187@1448417498772/Genetic-algorithm-procedure-for-TSP.png" width="400" />

### Mean Squared Error

Mean Squared Error digunakan sebagai nilai Fitness individu.

<img src="https://i.imgur.com/vB3UAiH.jpg" width="400" />

## Hasil
berikut merupakan grafik nilai hasil prediksi dengan nilai sebenarnya :

![hasil](https://user-images.githubusercontent.com/39853838/54495803-e797b500-4919-11e9-9f56-2cd3ab253099.png)
