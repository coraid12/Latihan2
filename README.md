# Operator Aritmatika
Opeartor aritmatika termasuk dalam operator yang paling sering digunakan dalam pemrograman.

Opeartor aritmatika terdiri dari:

Operator	Simbol
Penjumlahan	+
Pengurangan	-
Perkalian	*
Pembagian	/
Sisa Bagi	%
Pemangkatan

Mari kita coba dalam program:

# Langkah-Langkah

#Ambil input untuk mengisi nilai
a = input("Inputkan nilai a: ")
b = input("Inputkan nilai b: ")

#Menggunakan operator penjumlahan
c = a + b
print "Hasil %d + %d = %d" % (a,b,c)

#Operator Pengurangan
c = a - b
print "Hasil %d - %d = %d" % (a,b,c)

#Operator Perkalian
c = a * b
print "Hasil %d * %d = %d" % (a,b,c)

#Operator Pembagian
c = a / b
print "Hasil %d / %d = %d" % (a,b,c)

#Operator Sisa Bagi
c = a % b
print "Hasil %d %% %d = %d" % (a,b,c)

#Operator Pangkat
c = a ** b
print "Hasil %d ** %d = %d" % (a,b,c)

Hasilnya:

![hasil-program-operator-aritmatika](https://user-images.githubusercontent.com/56239989/67143772-089dfb00-f299-11e9-8bd7-3f6707cbfc81.png)

Pada kode program di atas, kita menggunakan string formatting untuk mencetak hasil dari masing-masing opearasi.

Operator % selain digunakan untuk string formatting, operator ini juga digunakan untuk menghitung operasi sisa bagi.

Misal: 5 % 2, maka hasilnya 1. Karena sisa dari hasil bagi antara 5 dengan 2 adalah 1.
