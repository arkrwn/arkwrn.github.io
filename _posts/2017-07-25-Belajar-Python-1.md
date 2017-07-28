---
layout: post
title:  "Python - Tipe Data"
image: ''
date:   2017-07-25 00:05:30
tags:
- Python
description: ''
categories:
- Learn Python
comments: true
---

Untuk belajar Python, hal pertama yang harus kita ketahui adalah tipe data (*Data Type*)
untuk itu mari kita mulai mengenali tipe data yang terdapat dalam bahasa pemrograman Python
Python memiliki beberapa tipe data built-in atau bawaan yang cukup lengkap dan tidak sulit untuk digunakan.

Beberapa tipe data yang wajib kalian ketahui di Python3 antara lain:

- int, tipe data yang dapat kalian isi dengan bilangan bulat
- float, tipe data yang dapat kalian isi dengan bilangan koma
- string, tipe data yang dapat kalian isi dengan sebuah karakter atau kalimat
- complex, tipe data yang dapat kalian isi dengan bilangan kompleks
- long, tipe data yang dapat kalian isi dengan bilangan yang sangat besar. Bisa lebih dari 1 milyar
- boolean, tipe data yang dapat kalian isi untuk mendukung operasi bool. Nilanya hanya True dan False
- list, tipe data mirip array yang bisa kalian isi dengan tipe data apapun dan dapat diubah
- tuple, tipe data mirip list tapi tidak dapat diubah
- dictionary, tipe data key-value yang sangat berguna bila ingin membuat tipe data yang cukup terstruktur

perhatikan kode berikut :

```
angka1 = 10
angka2 = 3.14
angka3 = 10+5j
karakter = 'A'
kalimat = "Lorem ipsum sit dolor amet"
is_admin = True
is_member = False
daftar_angka = [1, 2, 3]
daftar_huruf = ('a', 'b', 'c')
data_orang = {'name':'michael', 'country':'Indonesia', 'phone':'7501234'}

print (angka1)
print (type(angka1))

print (angka2)
print (type(angka2))

print (angka3)
print (type(angka3))

print (kalimat)
print (type(kalimat))
```

pada kode diatas kita menggunakan fungsi print() untuk menampilkan output,
sementara fungsi type() kita gunakan untuk mengetahui tipe data dari variabel yang ingin kita ketahui tipe datanya

## Praktek -- ([Online Editor](https://repl.it/JluY/3))
  - Silahkan jalankan kode di atas dan lihat apa hasilnya
  - Silahkan buat variabel lain yang kalian ingin coba dengan tipe data yang ada pada kode di sebelah kanan. Dan lihat hasilnya.
