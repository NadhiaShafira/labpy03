# Praktikum 3 - perulangan

Nama : Nadhia Shafira

Kelas : TI.24.A.5

NIM : 312410498

Mata Kuliah : Bahas Pemograman

## alur kode latihan1

```python
from random import random
```
Kode ini mengimpor fungsi random() dari modul random, yang akan menghasilkan angka acak antara 0 dan 1.

```python
n = int(input("masukkan nilai N: "))
```
Kode ini meminta pengguna untuk memasukkan nilai `N`, yang akan menentukan jumlah data yang ingin dihasilkan yang memenuhi kriteria tertentu.

```python
count = 0
```
Variabel `count` diinisialisasi dengan nilai 0, yang akan digunakan untuk menghitung jumlah data acak yang sudah memenuhi kriteria.

```python
while count < n:
```
Kode ini membuat sebuah while loop yang akan terus berjalan selama nilai `c

```python
random_number = random()
```
Dalam setiap iterasi while loop, kode ini menghasilkan angka acak `random_number` antara 0 dan 1.

```python
if random_number < 0.05:
```
Setelah menghasilkan angka acak, kode memeriksa apakah angka tersebut kurang dari 0.05. Jika ya, maka angka tersebut dianggap memenuhi kriteria.

```python
print(f"data ke {count} = {random_number}")
count += 1
```
Jika angka acak memenuhi kriteria (`random_number < 0.05`), maka:

- Kode akan menampilkan angka acak tersebut dan indeksnya.
- Nilai count akan ditambah 1 untuk menunjukkan bahwa satu angka yang memenuhi kriteria telah ditemukan.

- ```python
print("SELESAI")
```
akan menampilkan `SELESAI!`
```
