# Labpy03

# Latihan 1 (Program menampilkan n bilangan acak lebih < 0.5)

	~Alur Agoritmanya :
	-import random memanggil file random
	-n = int(input("Masukan nilai N : ")) input variabel n, tipe data integer
	-for i in range(n) : looping for, dengan jumlah perulangan sebanyak n
	-a=random.uniform(0.0,0.5) variabel a berisikan random angka dari 0.0 sampai 0.5
	-print ("data ke : ", i, "=> ", a) print data ke : i = index looping a = angka random sesuai syarat nomer 4
	-print("Selesai") print Selesai di luar looping
	-Tampilkan hasil kelayar

~Berikut kode lengkapnya :

	print('|PROGRAM MENAMPILKAN N BILANGAN ACAK LEBIH < 0.5|')

	import random

	n = int(input("Masukan nilai N : "))
	for i in range(n) :
	    a=random.uniform(0.0,0.5)
	    print ("Data ke : ", i, "=> ", a)
    
	print("Selesai")
	
~Berikut Flowchartnya

![img](https://github.com/zahira12/Labpy03/blob/master/Flowchart1.png)

~Berikut Hasil Screenshootnya

![img](https://github.com/zahira12/Labpy03/blob/master/HasilLatihan1.png)

# Latihan 2 (Program menampilkan bilangan terbesar)

	~Alur Algoritmanya :
	-a=1 //variable a diisi 1, agar bisa masuk ke syarat while max=0 //variable max diisi 0
	-while a!=0 : looping while dengan syarat a bukan 0
	-if x > max : max = a proses if untuk mencari nilai terbesar
	-a = int(input("Masukan bilangan : ")) input nilai a dengan tipe data integer
	-if a == 0 : break jika inputan a diisi angka 0 maka break alias berhenti looping
	-print("Bilangan terbesar adalah : ",max) print nilai terbesar, variabel max

~Berikut kode lengkapnya:

	print ('|PROGRAM MENAMPILKAN BILANGAN TERBESAR|')
	print ('')

	a=1
	max=0
	while a!=0:
	    if a>max:
	        max=a
	    a=int(input('Masukkan bilangan :'))	
	    if a==0:
	         break
        
	print ('Nilai terbesarya adalah :',max)

~Berikut Flowchatnya:

![img](https://github.com/zahira12/Labpy03/blob/master/Flowchart2.png)

~Berikut Hasil Screenshootnya

![img](https://github.com/zahira12/Labpy03/blob/master/HasilLatihan2.png)

# Program 1 (Program menghitung laba pengusaha)

	~Alur Agoritmanya :
	-x=100000000 modal 100,000,000, variable x
	-sum=0 variable untuk menjumlah total laba
	-y=0 variable untuk masa bulan
	-lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 
	*variable untuk jumlah laba perbulan, 
	 dipisahkan dengan koma, tipe data integer
	-for i in lb : looping for indexs i, dengan mengambil data dari lb
	-sum=sum+i rumus untuk menghitung total laba perbulan
	-y+=1 masa bulan, tiap looping menambah 1
	-print("laba bulan ke-", y ,"sebesar :", i ) print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb
	-print("Total laba adalah :", sum) print total laba
	-Tampilkan hasil kelayar 

~Berikut kode lengkapnya :

	x=100000000
	sum=0
	y=0
	lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
	print('Modal awal seorang pengusaha        :',x)
	for i in lb :
	    sum=sum+i
	    y+=1
	    print('Laba bulan ke-', y ,'sebesar            :', i)

	print('Total laba yang didapat adalah      :', sum)

~Berikut Flowchatnya:

![img](https://github.com/zahira12/Labpy03/blob/master/Flowchart3.png)

~Berikut Hasil Screenshootnya

![img](https://github.com/zahira12/Labpy03/blob/master/HasilProgram1.png)
