# Tugaslabspy04and05pert9
**NAMA     	: VERONIKA DESNA ERNAYANTI FAU** <br>
**NIM       : 312010333** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Bahasa Pemrograman** <br>
# Praktikum 4
## Latihan 4
<img width="347" alt="latihan 04" src="https://user-images.githubusercontent.com/73053784/100190597-308e7200-2f21-11eb-8737-845dfb0c67b6.png">

## Syntax
#veronikadesnafau

print(80*"=")

angka = [5, 10, 15, 20, 25]

#print semua elemen
print("Tampilkan semua elemen : ", angka)

#print elemen 3
print("Tampilkan elemen 3 : ", angka[2])

#print elemen 2 sampai elemen 4
print("Tampilkan elemen 2 sampai elemen 4 : ", angka [1:4])

#print elemen terakhir/elemen ke 5
print("Tampilkam elemen terakhir : ", angka[4])

#ubah elemen ke 4 dengan nilai lain
angka[3] = 17
print("ubah elemen ke 4 : ", angka)

#ubah elemen ke 4 sampai terakhir
angka[3:5] = [30, 35]
print("ubah elemen ke 4 sampai elemen terakhir : ", angka)

print(80*"=")

#buat 2 variabel list
listA = [2, 4, 6, 8, 10]
listB = [3, 5, 7, 9, 11]

#Tampilkan semua list
print("list A : ", listA)
print("list B : ", listB)

#ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
listB.extend(listA[0:2])
print("ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B) : ", listB)

#tambah list B dengan nilai string
listB.append("veronika")
print("tambah list B dengan nilai string : ", listB)

#tambah list B dengan 3 nilai
listB.extend([15, 17, 19])
print("tambah list B dengan 3 nilai : ", listB)

#gabungkan list B dengan list A
listC = listA + listB
print("gabungan list A dan list B : ", listC)

print(80*"=")

## OUTPUT
