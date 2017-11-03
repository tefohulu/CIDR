# TUCIL 1 - JARINGAN KOMPUTER
Hutama Tefotuho Hulu / 13515045

## Petunjuk Penggunaan

Jalankan cmd pada folder zip yang sudah diextract, kemudian gunakan command
```
make
```
untuk melakukan kompilasi program, dan command
```
make run
```
untuk menjalankan program

## Proses Pengerjaan

### Phase 1

* Kalkulator diminta untuk mencari sebuah subnet valid untuk host yang disediakan.
* Yang dilakukan program adalah dengan membuat subnet yang diturunkan dari host yang telah diberikan, dalam hal ini penulis menggunakan akhiran ``` XXX.XXX.XXX.0/24 ```. Misalnya IP addres yang diberikan adalah
``` 
53.71.139.80
```
Maka subnetnya adalah
```
53.71.139.0/24
```

### Phase 2

* Kalkulator diminta untuk menghitung jumlah host valid untuk sebuah subnet yang disediakan (termasuk broadcast dan gateway).

### Phase 3

* Kalkulator diminta untuk mengecek apakah suatu host berada pada subnet yang diberikan, dan akan memberikan T bila benar dan F bila salah.
