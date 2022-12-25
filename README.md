# Praktikum-12
## String
```
Nama  : Hasbi Assidiki
NIM   : 312210448
Kelas : TI.22.A.4
```
# Code dan Penjelasan Program
* Latihan 1 
``` python
txt = 'Hello World'
print(f"Teks = {txt}")
# Menghitung jumlah karakter
print("Jumlah Karakter = ",len(txt))
# Mengambil karakter terakhir
a = txt[-1]
print('Karakter Terakhir = ',a)
# Mengambil karakter ke-2 sampai ke-4
b = txt[2:5]
print(f"Karakter ke-2 sampai ke-4 = {b}")
# Hilangkan spasi pada text 
c = txt.replace(" ","")
print("Spasi di hilangkan = ",c)
# Ubah teks menjadi huruf besar
d = txt.upper()
print(f"Teks menjadi huruf besar = {d}")
# Ubah teks menjadi huruf kecil
e = txt.lower()
print(f"Teks menjadi huruf kecil = {e}")
# Ganti karakter H dengan karakter J
f = txt.replace("H","J")
print(f"Menganti karakter H dengan J = {f}")
```
* Latihan 2 
``` python
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah {0} tahun'
print(txt.format(umur))
```
## Output Program
* Latihan 1     

![Screenshot (103)](https://user-images.githubusercontent.com/115614317/209470636-f8896dcb-47ec-4d54-ab88-099bcbc1a34f.png)  

* Latihan 2     

![Screenshot (104)](https://user-images.githubusercontent.com/115614317/209470640-cb9d5c34-5797-4b5b-83a6-1023196b50ef.png)  
