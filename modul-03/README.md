# Modul [03] - [Trigonometri]

**Nama:** [Eva Anggraeni Lubis]  
**NIM:** [1306625039]  
**Kelas:** [Fisika C]

---

## 1. Problem Statement
> Membuat program yang dapat menghitung nilai sinus dan cosinus dari suatu besar sudut dalam derajat menggunakan pendekatan deret McLaurin

## 2. Mathematical Equation
> x = \theta \times \frac{\pi}{180}
> \sin(x) = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots
> \cos(x) = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots
> ER_{sin} = \left| \frac{AV_{sin} - TV_{sin}}{TV_{sin}} \right| \times 100\%
> ER_{cos} = \left| \frac{AV_{cos} - TV_{cos}}{TV_{cos}} \right| \times 100\%

## 3. Algorithm
> 1. Print "PROGRAM SINUS-COSINUS"
2. Print "Nama : Eva Anggraeni Lubis"
3. Print "NIM : 1306625039"
4. Print "Kelas : Fisika C"
5. Input "Besar sudut (derajat)"
6. Hitung radian = sudut × π / 180
7. Hitung TV_sinus = sin(radian)
8. Hitung TV_cosinus = cos(radian)
9. Print "True value sin"
10. Print "True value cos"
11. Print tabel "Jumlah Suku | AV sinus | ER sinus | AV cosinus | ER cos"
12. suku = 1
13. Selama ER_sinus ≥ 5% atau ER_cosinus ≥ 5%
   13.1 Hitung AV_sinus menggunakan fungsi sinus
   13.2 Hitung AV_cosinus menggunakan fungsi cosinus
   13.3 Hitung ER_sinus
   13.4 Hitung ER_cosinus
   13.5 Print suku, AV_sinus, ER_sinus, AV_cosinus, ER_cosinus
   13.6 suku = suku + 1
   13.7 Kembali ke langkah 13
14. Input "Mau menghitung lagi (y/t)"
15. Jika input "y"
   15.1 Kembali ke langkah 5
16. Jika input "t"
   16.1 Print "Program selesai"
17. Selesai
