# Tugaslabspy04and05pert9
**NAMA     	: VERONIKA DESNA ERNAYANTI FAU** <br>
**NIM       : 312010333** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Bahasa Pemrograman** <br>
# Praktikum 4
## Latihan 4
<img width="347" alt="latihan 04" src="https://user-images.githubusercontent.com/73053784/100190597-308e7200-2f21-11eb-8737-845dfb0c67b6.png">

### Syntax
berikut merupakan syntax untuk menampilkan program diatas

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
Dibawah ini merupakan hasil output dari syntax diatas
![1](https://user-images.githubusercontent.com/73016496/100323437-56d31100-2ff8-11eb-9b61-5f84f1d8daba.png)

## ANALISIS
 Penjelasan singkat fungsi source code kurang lebih seperti yang sudah dijelaskan di comment yang tertera pada Syntax
 

## Tugas Praktikum 4
![Screenshot (40)](https://user-images.githubusercontent.com/73010098/100231831-2046b900-2f5a-11eb-8cc4-2d6e0b8e2670.png)

### Syntax
berikut merupakan syntax untuk menampilkan program diatas
#author Veronika fau - 312010333

print(90*"=")
print("MASUKAN DATA SISWA")
print(90*"=")

dataNilai = []
while True :
    nama = input("Nama        : ")
    nim = input("NIM         : ")
    nTugas = int(input("Nilai Tugas : "))
    nUts = int(input("Nilai UTS   : "))
    nUas = int(input("Nilai UAS   : "))
    nAkhir = float(nTugas)*30/100+(nUts)*35/100+(nUas)*35/100
    dataNilai.append ([nama, nim, nTugas, nUts, nUas, nAkhir])
    add = input("TAMBAH DATA (ya/tidak)?")

    if add.lower() == "tidak":
        break


#directory data siswa
print(90*"=")
print("| {0:^2} | {1:^18} | {2:^10} | {3:^10} | {4:^10} | {5:^10} | {6:^7} |".format("NO", "NAMA", "NIM", "NILAI TUGAS", "NILAI UTS", "NILAI UAS", "NILAI AKHIR"))
print(90*"=")
no = 0
for x in dataNilai:
    no+=1
    print("| {0:>2} | {1:<18} | {2:>10} | {3:>11} | {4:>10} | {5:>10} | {6:>11.2f} |"\
        .format (no,x[0][:18],x[1][:10],x[2],x[3],x[4],x[5]))
print(90*"=")

## OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas
![2](https://user-images.githubusercontent.com/73016496/100332703-4a54b580-3004-11eb-897f-aef6873744db.png)


## ANALISIS
• Proses input data terjadi pada syntax dibawah ini :
![3](https://user-images.githubusercontent.com/73016496/100334127-f4810d00-3005-11eb-9854-f24363c6be0f.png)
• Pada statement dataNilai=[] berfungsi untuk menyimpan/merangkap data yang akan diinputkan oleh user
• Pada statement while True : berfungsi untuk melakukan proses looping/perulangan.
• Pada statement nAkhir = float(nTugas)*30/100+(nUts)*35/100+(nUas)*35/100 diambil dari ketentuan soal untuk proses perhitungan nilai akhir.
• Pada statement dataNilai.append ([nama, nim, nTugas, nUts, nUas, nAkhir]) berfungsi menambah element list.
• Pada statement







