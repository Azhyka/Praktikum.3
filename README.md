# Praktikum3

## Latihan 1
# Penggunaan end

  Parameter akhir dalam fungsi cetak digunakan untuk menambahkan string apa pun. Di akhir output dari pernyataan print dengan python.
  Secara default, fungsi cetak diakhiri dengan baris baru.
  Melewati spasi putih ke parameter akhir (end=' ') menunjukkan bahwa karakter akhir harus diidentifikasi oleh spasi putih dan bukan baris baru.
```
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
```
![Gambar1](gambar/Latihan1.png)

# Penggunaan Seperator
```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
![Gambar1](gambar/Latihan1,1.png)

# String Format 
```
# string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```
![Gambar1](gambar/Latihan1,2.png)

# String Format 2
```
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(0, 10**1))
print('{0:>3} {1:>16}'.format(0, 10**2))
print('{0:>3} {1:>16}'.format(0, 10**3))
print('{0:>3} {1:>16}'.format(0, 10**4))
print('{0:>3} {1:>16}'.format(0, 10**5))
print('{0:>3} {1:>16}'.format(0, 10**6))
print('{0:>3} {1:>16}'.format(0, 10**7))
print('{0:>3} {1:>16}'.format(0, 10**8))
print('{0:>3} {1:>16}'.format(0, 10**9))
print('{0:>3} {1:>16}'.format(0, 10**10))
```
![Gambar1](gambar/Latihan1,3.png)
# Hasil Latihan 1
![Gambar1](gambar/Hasil1.png)
## Latihan 2

# Input Variable
```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
```
![Gambar2](gambar/Latihan2.png)

# Cetak Variable
```
print("variable a=",a)
print("variable b=",b)
```
![Gambar2](gambar/Latihan2,1.png)

# Penggabungan Variable
```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```
![Gambar2](gambar/Latihan2,2.png)

# Input Variable 2
```
a=int(a)
b=int(b)
```
![Gambar2](gambar/Latihan2,3.png)

# Konversi Nilai Variable
```
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
```
![Gambar2](gambar/Latihan2,4.png)

# Hasil Latihan 2
![Gambar2](gambar/Hasil2.png)

# Latihan 3 Luas Lingkaran
```
print('Menghitung luas lingakaran')
print('==============================')
r = int(input('masukan jari-jari lingkaran: '))
phi = 3.14
L = phi * (r * r)
print('Luas lingakaran dengan jari-jari {} adalah {}'.format(r, L))
```
![Gambar3](gambar/Latihan3.png)

# Hasil Latihan 3
![Gambar3](gambar/HasilLingkaran.png)
