Program sederhana untuk menentukan bilangan terbesar
Coding
- print ('=====================================')
- print ('PROGRAM MENENTUKAN BILANGAN TERBESAR')
- print ('=====================================')
- print ('')
- print ('Masukkan 3 Bilangan yang diinginkan!')
a=int(input('Bilangan 1 = '))
b=int(input('Bilangan 2 = '))
c=int(input('Bilangan 3 = '))
if a>b and a>c:
- print('')
- print('=====================================')
- print (a, 'Adalah Bilangan terbesar')
elif b>a and b>c:
- print('')
- print('=====================================')
- print (b, 'Adalah Bilangan terbesar')
else:
- print('')
- print('=====================================')
- print(c, 'Adalah Bilangan terbesar')
- print ('=====================================')
Penjelasan
Pertama kita harus menginput bilangan pertama sampai bilangan ketiga. Codingnya :
a=int(input(‘Bilangan 1 = ‘))
b=int(input(‘Bilangan 2 = ‘))
c=int(input(‘Bilangan 3 = ‘))
Selanjutnya kita menggunakan logika if dan Logika AND. Codingnya :
if a>b and a>c:
- print (a, ‘Adalah Bilangan terbesar’)
elif b>a and b>c:
- print (b, ‘Adalah Bilangan terbesar’)
else:
- print (c, ‘Adalah Bilangan terbesar’)
Penjelasannya : Jika a lebih dari b dan a lebih dari c, maka output bilangan a, kalau bilangan a bukan bilangan terbesar maka lanjut ke bilangan b, jika b lebih dari a dan b lebih dari c maka bilangan b Adalah Bilangan terbesar, kalau a dan b bukan bilangan terbesar maka bilangan c Adalah bilangan yang terbesar.
Output
=====================================
PROGRAM MENENTUKAN BILANGAN TERBESAR
=====================================
Masukkan 3 Bilangan yang diinginkan!
Bilangan 1 = 10
Bilangan 2 = 30
Bilangan 3 = 20
=====================================
30 Adalah Bilangan terbesar
=====================================
Process finished with exit code 0
