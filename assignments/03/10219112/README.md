# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10298345'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219112'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```
Dengan keluaran

![gambar 1](https://github.com/HanzHamzahK/fi3201-01-2021-2/blob/main/assignments/03/10219112/images/3xrctga2r.png)

Error terjadi karena variabel 'char' belum didefinisikan sehingga penambahan variabel 'char' kepada variabel 's' menghasilkan error

Kode dites pada OneCompiler [3xrctga2r](https://onecompiler.com/python/3xrctga2r)

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219112'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char1
  print(n, ':', s, sep='')
```
Dengan keluaran

![gambar 2](https://github.com/HanzHamzahK/fi3201-01-2021-2/blob/main/assignments/03/10219112/images/3xrctk2dd.png)

Kode dites pada OneCompiler [3xrctk2dd](https://onecompiler.com/python/3xrctk2dd)

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219112'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char2
  print(n, ':', s, sep='')
```
Dengan keluaran

![gambar 3](https://github.com/HanzHamzahK/fi3201-01-2021-2/blob/main/assignments/03/10219112/images/3xrctkv86.png)

Kode dites pada OneCompiler [3xrctkv86](https://onecompiler.com/python/3xrctkv86)

## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ Mengubah angka NIM menjadi daftar yang menampilkan banyaknya persegi dengan jumlah sesuai dengan nilai digit pada NIM
