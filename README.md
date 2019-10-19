Latihan2

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

# file: operator_aritmatika.py

# Ambil input untuk mengisi nilai
a = input("Inputkan nilai a: ")
b = input("Inputkan nilai b: ")

# Menggunakan operator penjumlahan
c = a + b
print "Hasil %d + %d = %d" % (a,b,c)

# Operator Pengurangan
c = a - b
print "Hasil %d - %d = %d" % (a,b,c)

# Operator Perkalian
c = a * b
print "Hasil %d * %d = %d" % (a,b,c)

# Operator Pembagian
c = a / b
print "Hasil %d / %d = %d" % (a,b,c)

# Operator Sisa Bagi
c = a % b
print "Hasil %d %% %d = %d" % (a,b,c)

# Operator Pangkat
c = a ** b
print "Hasil %d ** %d = %d" % (a,b,c)

Hasilnya:
