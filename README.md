# Praktikum3

# Program Python Menghitung Luas Dan Keliling Lingkaran

Untuk kesempatan hari ini saya akan menghitung Luas Dan Keliling Lingkaran
menggunakan python disertakan dengan Flowchart menghitung Luas Dan Keliling lingkaran.

Saat akan menghitung Luas Dan Keliling Lingkaran hal pertama yang harus kita ketahui adalah
rumus luas dan keliling dari lingkaran

**RUMUS LUAS DAN KELILING LINGKARAN** 

`Luas = pi*r*r`

`Keliling = 2*pi*r`

  - Nilai pi yang akan kita gunakan adalah 22/7 

  - r merupakan jari-jari lingkaran

**pi** merupakan nilai konstanta dimatematika dalam sebuah lingkaran

**jari-jari** merupakan jarak antara titik tengah/pusat dengan tipe lingkaran.

Sebenarnya ada rumus lain dalam menghitung keliling lingkaran dengan menggunakan diameter, tapi pada kasus ini saya akan menggunakan jari-jari saja

**FLOWCHART MENGHITUNG LUAS DAN KELILING LINGKARAN**

Berikut ini adalah contoh flowchart dari mulai hingga selesai

`Mulai > Masukan Jari-Jari > Hitung Luas & Keliling > Tampilkan Luas Dan Keliling Lingkaran > Selesai`

![Screenshot (64)](https://user-images.githubusercontent.com/115474950/198354139-24066221-99a3-4232-8242-e65142b903c8.png)

**PROGRAM PYTHON MENGHITUNG LUAS DAN KELILING LINGKARAN**

**Input**

`print("Program Python Menghitung Luas Dan Keliling Lingkaran")`

`print("---------------------------------------------------\n")`

`pi = 22/7`

`jari = float(input("Masukan Jari-Jarinya : "))`

`luas = pi*(jari*jari)`

`keliling = 2*pi*jari`

`print("\n--------------------Hasilnya-----------------------")`

`print ("Luas Lingkaran \t\t=",luas)`

`print ("Keliling Lingkaran\t=",Keliling)`

Berikut Hasilnya Seperti Gambar Berikut:

![Screenshot (59)](https://user-images.githubusercontent.com/115474950/198355564-1badbfe9-875a-4060-8a40-51c2a03e08c0.png)

**Output**

`Program Python Menghitung Luas Dan Keliling Lingkaran`

`------------------------------------------------------`

`Masukan Jari-Jarinya : 37`

`----------------------Hasilnya------------------------`

`Luas Lingkaran = 4302.571428571428`

`Keliling Lingkaran = 232.57142857142856`

Hasilnya seperti gambar berikut :

![Screenshot (61)](https://user-images.githubusercontent.com/115474950/198356980-f06b6dbc-b707-4e23-861c-86b15561ba5f.png)

Ketika kita sudah mendapatkan nilai **pi** dan **jari-jari** selanjutnya kita bisa menghitung Luas Dan Keliling dengan rumus masing-masing

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil dua pecahan saja di belakang koma(,) kita pakai fungsi **format** () seperti berikut

**Input**

`print("\n---------------------Hasilnya----------------------")`

`print("Luas Lingkaran =","{:.2f}".format(luas))`

`print("Keliling Lingkaran =","{.2f}".format(keliling))`

Hasilnya seperti gambar berikut ini :

![Screenshot (60)](https://user-images.githubusercontent.com/115474950/198358449-c1bb6fe1-3b8e-4a3a-b26b-de2c9a2eaf0a.png)

**Output**

`-------------------------Hasilnya------------------------`

`Luas Lingkaran = 4302.57`

`Keliling Lingkaran = 232.57`

Hasilnya seperti gambar berikut ini :

![Screenshot (62)](https://user-images.githubusercontent.com/115474950/198358922-bb64231c-8828-44f6-a01b-b408f32b219d.png)

Dengan menggunakan fungsi **format(luas;.2')** maka akan menghasilkan 2 angka pecahan saja di belakang koma.

Sekianlah pembahasan kali ini mengenai contoh program python untuk menghitung luas dan keliling lingkaran. Bila ada kekurangan mohon di maafkan.

**TerimaKasih**




