# P2_Probstat_C_5025201087

## Soal No 1  
### a) Standar Deviasi  
```r
> different <- c(100-78,95-75,70-67,90-77,90-70,90-72,90-78,90-74,100-77)
> sd(different)
[1] 6.264982
```    
  
### b) Uji p-value  
```r
> t.test(different)

        One Sample t-test

data:  different
t = 7.8213, df = 8, p-value = 5.136e-05
alternative hypothesis: true mean is not equal to 0
95 percent confidence interval:
 11.51764 21.14902
sample estimates:
mean of x 
 16.33333 
```  
  
### c) Menentukan uji tes terhadap pernyataan H0  
Berdasarkan output yang dihasilkan, diperoleh nilai t = 12.013, dengan derajat bebas 8 dan nilai p-value = 5.136e-05. Dari hasil tersebut peneliti dapat menolak hipotesis awal dan disimpulkan bahwa terdapat pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen, sebelum dan sesudah melakukan aktivitas A. Selain itu, dari output di atas, kita juga peroleh selang kepercayaan rata-rata dari sampel yang berkisar di antara 11.51764 sampai 21.14902  atau dapat dinyatakan bahwa dengan selang kepercayaan 95% kita yakin rata-rata selisih data sampel X dan Y akan berkisar antara 11.51764 sampai 21.14902. Rata-rata selisih data sampel X dan Y yang dihitung adalah 16.33333.  
  
  
## Soal No 2  
### a) Apakah setuju dengan klaim tersebut?  
Setuju (Jika di logika singkat, tanpa menjalankan analisa mendalam).  
  
### b) Jelaskan hasil dari output  
```r
> zsum.test(mean.x = 20000 , sigma.x = 3900 , n.x = 100 , mu = 23500 , conf.level = 0.95)

        One-sample z-Test

data:  Summarized x
z = -8.9744, p-value < 2.2e-16
alternative hypothesis: true mean is not equal to 23500
95 percent confidence interval:
 19235.61 20764.39
sample estimates:
mean of x 
    20000
```  
b+c) Berdasarkan output yang dihasilkan, diperoleh nilai z = 51.282 dengan nilai p-value < 2.2e-16. Dari hasil tersebut dapat disimpulkan bahwa hipotesis alternatif bernilai benar karena rerata yang didapatkan tidak sama dengan 23500 (confidence interval berada di kisaran 19235.62 sampai 20764.39).  
  
  
## Soal No 3  
### a) H0 dan H1  
H0 : Tidak ada perbedaan dalam kedua variabel  
H1 : Ada ketidaksamaan dalam kedua variabel yang dibandingkan  
  
### b) Hitung sampel statistik  
Melakukan Uji T Independen karena 2 populasi tidak saling berikatan/saling bebas.  
```r
> tsum.test(mean.x = 2.64 , s.x = 1.67 , n.x = 19 , mean.y = 2.79 , s.y = 1.32 , n.y = 27 , var.equal = TRUE, conf.level = 0.95)

        Standard Two-Sample t-Test

data:  Summarized x and y
t = -0.34001, df = 44, p-value = 0.7355
alternative hypothesis: true difference in means is not equal to 0
95 percent confidence interval:
 -1.0391105  0.7391105
sample estimates:
mean of x mean of y 
     2.64      2.79
```  
  
### c) Lakukan uji statistik (df = 2)  
### d) Nilai kritikal  
```r
# Left-tailed test
> qt(p=0.05 , df = 2 , lower.tail = TRUE)
[1] -2.919986

# Right-tailed test
> qt(p=0.05 , df = 2  ,lower.tail = FALSE)
[1] 2.919986

# Two-tailed test
> qt(p=0.05/2 , df = 2 , lower.tail = FALSE)
[1] 4.302653
```  
  
### e) Keputusan  
### f) Kesimpulan  
Membutuhkan waktu cukup lama dalam mencari referensi yang belum tersedia :")  
  
  
## Soal No 4  
### a) 


