![gambar 1](screenshot/scr1.gif) <p>
Program ini adalah program untuk Menghitung dan Menampilkan data nilai Mahasiswa dengan menggunakan LIST dan Module Texttable pada PYTHON 3.6 di OS Windows Program Menghitung, menampilkan Data Mahasiswa penjelasan tentang program untuk menghitung dan menampilkan data mahasiswa dan nilai yg di dapat, dengan perhitungan nilai (tugas : 30%, uts : 35%, uas: 35%).
                                Entry input pada program ini adalah
Input NAMA<p>
Input NIM<p>
Input NILAI TUGAS<p>
Input Nilai UAS<p>
Input Nilai AKHIR<P>


## hasil outputnya berupa tabel menggunakan module 
```javascript
texttable
```
### disini saya menggunakan Python 3.6 di OS Windows. di OS Windows Kita Harus Mendownload dan Instal Texttable dan PIP (Package) silakan download libarary [di sini ](https://pypi.python.org/pypi/texttable/0.8.4) .

### setelah di install library nya kita langsung bisa menggunakan perintah from texttable import texttable fungsinya yaitu untuk memanggil module texttable dengan menggunakan texttable kita bisa membuat output tabel yang rapi sesuai dengan yang kita input. 
### disini saya juga menggunakan fungsi list untuk program input pada koding ini, yaitu menggunakan Python ListMethods : Append () menambahkan item dari belakang . 
### selain itu saya menggunakan perintah while untuk mengulang pertanyaan yang akan diinput 

```javascript
while(jawab == "y"):
nama.append(input("Masukan Nama :"))
nim.append(input("Masukan Nim :"))
nilai_tugas.append(input("Nilai Tugas :"))
nilai_uts.append(input("Nilai UTS :"))
```

### maka outputnya akan ada pertanyaan tambah data jika jawab "y" maka pertanyaan akan terulang kembali dan diiput kembali seperti sebelumnya, jika menjawab "t" maka perintah selesai dan keluar output hasil inputan. dengan cara itu kita bisa menginput lebih dari 1 inputan atau sesuai yg kita inginkan.
```javascript
nilai_uas.append(input("Nilai UAS :"))
jawab = input("Tambah data (y/t)?")
```
## perintah 
```javascript
for i in range(no) : 
```
## digunakan untuk melakukan perulangan atau iterasi sampai batas atau range yang telah ditentukan.
```javascript
table.add_rows([['No','Nama','NIM','TUGAS','UTS','UAS','AKHIR'],[i+1, nama[i],nim[i],nilai_tugas[i],nilai_uts[i],nilai_uas[i],akhir]])
print (table.draw()) .
```
### 'table.add_row' untuk menambahkan baris pada tabel. untuk menampilkan karakter bisa ditambahkan tanda (' ') dan untuk menampilkan hasil dari input tidak menggunakan tanda petik. dan untuk perhitungan nilai akhir menggunakan operator aritmatika perkalian dan penjumlahan.

### untuk hasil output nya 
  No  | Nama           | NIM         | Nilai Tugas   | Nilai UTS     | Nilai UAS    | Nilai Akhir |
  ----| -------------- | ----------- |---------------|---------------|--------------|-------------|
  1   | REFI DAUS          | 31171769    | 90            | 90            | 100          |  93.500     |
  2   | SAHRUL         | 1171798     | 90            | 80            | 90           |  86.500     |