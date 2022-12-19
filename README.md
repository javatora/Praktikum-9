# Praktikum-9
### Nama    : Zainul Mutaqin
### NIM     : 312210153
### Kelas   : TI.22.B1

## Contoh dan Penjelasan Modul Praktikum 13

1. Berikut adalah fungsi yang mengubah suhu derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang di dapat, fungsi tersebut ditebus jika melihat suhu negatif.

<img width="505" alt="Screen Shot 2022-12-18 at 23 04 48" src="https://user-images.githubusercontent.com/115475424/208307972-a849ec43-6f2e-4f46-8fdd-2694b65151c1.png">

## Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError  artinya terjadi error pada pertanyaan assert.

2. Contoh ini membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.

![image](https://user-images.githubusercontent.com/115475424/208335971-19c0797a-0d79-4e71-994f-e1766f010622.png)

> Hasilnya :

Written content in the file successfully

### Hasilnya seperti ini karen aelse akan dijadikan ketika try adalah True

3. COntoh ini mencoba membuka file dimana anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian

![image](https://user-images.githubusercontent.com/115475424/208336132-141394ad-9fc2-4790-b07e-54753c3704f9.png)


## Mengapa hasilnya error ?
### r adalah read -  Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulsi maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.


4. Contoh ke empat

![image](https://user-images.githubusercontent.com/115475424/208336348-30d0f1e8-a089-456a-862c-3c2774f035e1.png)

### Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.


5. Contoh single exception

![image](https://user-images.githubusercontent.com/115475424/208336474-ef9ce7d1-71bc-4e1c-ac71-9556af5ee478.png)

> Hasilnya :

The argument does not contain numbers 
invalid literal for int() with base 10: 'xyz'

### Ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument: agar tidak error. Jika dijalankan akan mumncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.


6. Contoh dan penjelasan

![image](https://user-images.githubusercontent.com/115475424/208336730-af1904bc-e1ff-4397-b16a-d9aa577bdd74.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level", level ganti tanda koma dengan tanda plus. Cetak def dengan angka lebih besar dari 1.

