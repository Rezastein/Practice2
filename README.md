# **Program untuk menghitung luas dan keliling lingkaran**

[![instagram](https://img.shields.io/badge/Nama-Maulana%20Reza-blue.svg)](https://www.instagram.com/rezastein_) [![instagram](https://img.shields.io/badge/Nim-312110510-blue.svg)](https://www.instagram.com/rezastein_) [![instagram](https://img.shields.io/badge/Kelas-TI.21.C5-blue.svg)](https://www.instagram.com/rezastein_)

### **MY SOSIAL MEDIA :**

[![instagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/30px-Instagram_logo_2016.svg.png)](https://www.instagram.com/rezastein_) <br> [![facebook](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/F_icon.svg/30px-F_icon.svg.png)](https://www.facebook.com/rezastein.rezastein) <br> [![twiter](https://upload.wikimedia.org/wikipedia/de/thumb/9/9f/Twitter_bird_logo_2012.svg/30px-Twitter_bird_logo_2012.svg.png)](https://twitter.com/rezastein_) <br> [![whatapp](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/30px-WhatsApp.svg.png)](https://wa.me/qr/UK5NMG54XWHJC1)

## **Lab 1**
- **END**

```sh
print('A', end='')
```
**END** adalah karakter yang dicetak di akhir baris. Defaultnya adalah tanda newline (baris baru).

jadi penggunaan **END** menandakan penggunaan untuk newline/barisbaru

- **sparator**
```sh
print(w, x, y, z, sep=',')
```

**SEP** adalah pemisah(separator) yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.

- **formating string**

**formating string** adalah fitur Python yang paling keren adalah format string operator %. Operator ini unik untuk string dan membuat paket memiliki fungsi dari keluarga printf C () C. 
berikut adalah contoh sederhananya : 
```sh
print('{0:>3} {1:>16}'.format(0, 10**0))
```
**SCREENSHOT OUTPUT PROGRAM**
![.](ss/1.png)

## **Lab 2**
## input
- variable
```sh
a = 
b =
```
- input pada variable 
```sh
a = input("masukan nilai a: "))
b = input("masukan nilai b: "))
```
- type data pada input
<br> Type data **string/text** adalah **str**
<br> Type data **integer/angka** adalah **int**
```sh
a = int(input("masukan nilai a: "))
b = int(input("masukan nilai b: "))
```
## output
- Arithmetic Operators
<br/>
variable **a**+**b** 
```sh
print("hasil pergabungan {1}&{0}=%d".format(a,b) %(a+b))
```
##  **konversi bilangan variable**
## input
- input pada variable ber type data
```sh
a=int(a)
b=int(b)
```

## output
- Arithmetic Operators
<br>
variable **a**+**b** 
<br>
variable **a**/**b** 
```sh
print("hasil perjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
### **FLOWCART**
![.](ss/3.png)
### **SCREENSHOT PROGRAM**
![.](ss/2.png)

## **Program menghitung luas keliling lingkaran**

### Rumus Luas & Keliling Lingkaran
```sh
Luas     = π × r²
Keliling = 2 x π × r
```
- Nilai Phi yang akan digunakan adalah 3.14
- r merupakan jari-jari lingkaran

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.

```sh
phi = 3.14
r = float(input("Masukkan panjang jari-jari lingkaran: "))

luas = phi*(r*r)
keliling = 2*phi*r

print("Luas lingkaran adalah : "+ str(luas))
print("Keliling lingkaran adalah : "+ str(keliling))
```
**Float** adalah tipe data yang menampung bilang desimal/pecahan.

## **FLOWCART**
![.](ss/4.png)
## **SCREENSHOT PROGRAM**
![.](ss/5.png)
