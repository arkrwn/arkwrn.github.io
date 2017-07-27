---
layout: post
title:  "Pyhton - Konversi Tipe Data"
image: ''
date:   2017-07-26 00:05:30
tags:
- Python
description: ''
categories:
- Learn Python
---

Setelah mengenal beberapa tipe data dasar di Python, kini saatnya Kalian menguasai konversi tipe di Python.
Suatu tipe data dapat dikonversi lagi ke tipe data lain dengan menggunakan beberapa function berikut:

<!--more-->

-    chr(), mengubah angka ke karakter
-    unichr(), mengubah angka ke karakter unicode
-    str(), mengubah angka ke string
-    complex(), mengubah angka ke bilangan kompleks
-    float(), mengubah angka ke bilangan koma
-    hex(), mengubah angka ke bentuk heksadesimal
-    oct(), mengubah angka ke bentuk octal
-    int(), mengubah tipe data lain ke angka

Sekarang mari kalian coba mengubah angka ke beberapa tipe data lain.

```
angka = 12345
var1 = str(angka)
var2 = float(angka)
var3 = complex(angka)
var4 = hex(angka)
var5 = oct(angka)

print(var1)
print(var2)
print(var3)
print(var4)
print(var5)
```

# Praktek -- (Online Editor)[https://repl.it/JluY/2]

    + Silahkan jalankan kode di atas dan lihat apa hasilnya
    + Silahkan ubah isi variabel angka dengan angka lain yang kalian suka
