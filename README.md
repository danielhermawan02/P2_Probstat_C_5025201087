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
