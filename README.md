![gambar 1](screenshot/scr1.gif) <p>
### Program ini adalah program untuk Menghitung dan Menampilkan data nilai Mahasiswa dengan menggunakan LIST  penjelasan tentang program untuk menghitung dan menampilkan data mahasiswa dan nilai yg di dapat, dengan perhitungan nilai (tugas : 30%, uts : 35%, uas: 35%). 


## Entry Input Pada Program Ini Adalah : 
<ul>
   <li>Input <b>NAMA</b> </li>
   <li>Input <b>NIM</b></li>
   <li>Input <b>NILAI TUGAS</b></li>
   <li>Input <b>Nilai Uas</b></li>
   <li>Input <b>Nilai Akhir</b></li>
</ul>
<hr/>





### disini saya juga menggunakan fungsi list untuk program input pada koding ini, yaitu menggunakan Visual Studi : Append () menambahkan item dari belakang . 
### selain itu saya menggunakan perintah while untuk mengulang pertanyaan yang akan diinput 

```javascript
data=[]
while(True):
    nim=input("masukan NIM: ")
    Nama=input("masukaan Nama: ")
    Tugas=input("masukan nilai Tugas: ")
    uts=input("masukan nilai UTS: ")
    uas=input("masukaan nilai UAS: ")
```

### Maka outputnya akan ada pertanyaan tambah data jika jawab "y" maka pertanyaan akan terulang kembali dan diiput kembali seperti sebelumnya, jika menjawab "t" maka perintah selesai dan keluar output hasil inputan. dengan cara itu kita bisa menginput lebih dari 1 inputan atau sesuai yg kita inginkan.
```javascript
Akhir=(int(Tugas)* .30) + (int(uts)* .35) + (int(uas)* .35)
    data.append([nim, Nama, Tugas, uts, uas, Akhir])
    ulangi=input("Tambah data (y/t)?")
```
## PERINTAH 
```javascript
if ulangi .lower()== 't' :
        break
```
## Digunakan untuk melakukan perulangan atau iterasi sampai batas atau range yang telah ditentukan.
```javascript
table.add_rows([['No','Nama','NIM','TUGAS','UTS','UAS','AKHIR'],[i+1, nama[i],nim[i],nilai_tugas[i],nilai_uts[i],nilai_uas[i],akhir]])
print (table.draw()) .
```
### Untuk menambahkan baris pada tabel. untuk menampilkan karakter bisa ditambahkan tanda (' ') dan untuk menampilkan hasil dari input tidak menggunakan tanda petik. dan untuk perhitungan nilai akhir menggunakan operator aritmatika perkalian dan penjumlahan.

### Untuk hasil output nya :
  No  | Nama           | NIM         | Nilai Tugas   | Nilai UTS     | Nilai UAS    | Nilai Akhir |
  ----| -------------- | ----------- |---------------|---------------|--------------|-------------|
  1   | REFI DAUS          | 31171769    | 90            | 90            | 100          |  93.500     |
  2   | SAHRUL         | 1171798     | 90            | 80            | 90           |  86.500     |

HASIL INPUT :
![gambar 2](screenshot/scr2.png) <p>
HASIL OUTPUT :
![gambar 3](screenshot/scr3.png) <p>