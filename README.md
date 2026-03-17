# fortran
vezbe fakultet informatika 
beleske dana 17.03.2026 vezbe broj jedan
READ - naredba za ucitavanje podataka
read (*,*) a
      | |
      v v
  unos sa tastature; unos neformatiran
WRITE - naredba za ispis podataka
WRITE(*,*) c
      | |
      v v
ispis na ekranu;ispis neformatiran
WIRTE(*,*) 'Vrednost za c je',c
uvek na pocetku Prvi_prog

program lelouch_vi_brittania
write(*,*) 'unesi vrednost za a i b'
read(*,*) a,b
c=a+b
write(*,*) 'vrednost za c je',c
end program
read(*,*) -> read *,
write(*,*) -> print *,
-----------------
read(*,5) n
5 format ( I4 )
-----------------
In I4 _ _ _ _ ( 1 2 3 4 ) ( _ 1 2 3 )
Fkd k - Ukupan broj mesta ostavljen d - broj decimalnih mesta
F6.3 _ _ . _ _ _ 1 2 . 3 4 5 - 1 . 2 3 4
Ek.d e=1.602 * 10^-19 C 
1.602 E-19
-----------------
F9.3
-----------------
write (*,15) n
15 format(' ', I4)
-----------------
program shinji
write(*,*) 'Unesi vrednost za a i b po format I4,F6.3'
read(*,5) n,b
5 format(I4,2x,F6.3)
c=n+b
write(*,15) c
write(*,*) c
15 format(' ','Vrednost za c je',F10.3)
end program
