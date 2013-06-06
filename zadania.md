Komputerowe-wspomaganie-nauczania-przedmiotow-
==============================================
1
PSPI 2013 - Matlab/Mathematica – przykładowe zadania
zaliczeniowe
1. Opór zastepczy trzech oporników R1, R2 i R3, połaczonych równolegle,
wyraza sie wzorem
R =
1
1
R1
+ 1
R2
+ 1
R3
.
Utwórz trzy zmienne zawierajace wartosci tych oporów i oblicz opór
zastepczy. Napisz funkcje, która wykonuje te operacje.
(Matlab, Mathematica)
2. Utwórz zmienna ftemp, która bedzie przechowywała temperature w
skali Fahrenheita. Zamien te wartosc na stopnie Celsjusza, korzystajac
z relacji C = (F −32)5/9, i przypisz zmiennej ctemp. Napisz funkcje,
która wykonuje te operacje.
(Matlab, Mathematica)
3. Wektor na płaszczyznie moze byc reprezentowany przez współrzedne
kartezjanskie x i y lub przez współrzedne biegunowe r i . Zwiazek
miedzy nimi jest dany przez
x = r cos(),
y = r sin().
Przypisz wartosci współrzednym biegunowym r oraz  i oblicz odpowiednie
współrzedne kartezjanskie x i y. Napisz funkcje, która wykonuje
te operacje.
(Matlab, Mathematica)
4. Oblicz:
p
17, 31.3 i tg(). Sporzadz wykresy funkcji
p
x, 3x i tg(x) w
przedziale (-5,5).
(Matlab, Mathematica)
5. Wygeneruj liczby losowe:
(a) liczbe rzeczywista z przedziału (0,1);
(b) liczbe rzeczywista z przedziału (0,20);
(c) liczbe rzeczywista z przedziału (20,50);
(d) liczbe całkowita z przedziału (0,10);
(e) liczbe całkowita z przedziału (0,11);
(f) liczbe całkowita z przedziału (50,100).
2
(Matlab, Mathematica)
6. Uzywajac funkcji oraz operatorów Matlaba i programu Mathematica
utwórz nastepujace wektory;
(a) 3 4 5 6
(b) 1.0000 1.5000 2.0000 2.5000 3.0000
(c) 5 4 3 2
7. Znajdz elegancki sposób generacji macierzy
7 8 9 10
12 10 8 6
Potem napisz wyrazenia, które dadza
(a) element w pierwszym wierszu i trzeciej kolumnie;
(b) wszystkie elementy drugiego wiersza;
(c) pierwsze dwie kolumny.
(Matlab, Mathematica)
8. Utwórz macierz a (4×2), zawierajaca zera, i przypisz ja do zmiennej.
Potem zastap jej drugi wiersz przez 3 i 6.
(Matlab, Mathematica)
9. Utwórz wektor x, składajacy sie z 21 równoodległych punktów z zakresu
od − do . Oblicz wektor y „równy” x2 − 4x + 3. Sporzadz
odpowiedni wykres.
(Matlab, Mathematica)
10. Utwórz macierz (3×5) losowych liczb rzeczywistych. Usun jej trzeci
wiersz.
(Matlab, Mathematica)
11. Oblicz objetosc wyrazonej kuli według wzoru
v =
4
3
(r3
z − r3w
),
gdzie rz jest promieniem zewnetrznym, a rw promieniem wewnetrznym.
(Matlab, Mathematica)
12. Napisz skrypt, który przypisuje wartosci wspłórzednym x i y kilku
punktów i zaznacza te punkty na płaszczyznie xy niebieskimi plusami
(+).
(Matlab)
3
13. Utwórz wektor x o wartosciach od 0 do 100 z krokiem 5 i wektor
y, który zawiera wartosci exp(−x2), obliczone dla kazdego elementu
wektora x. Wykresl te punkty uzywajac funkcji plot i bar.
(Matlab)
14. Wykresl funkcje 2x − (2x − x2) dla x zakresu od 0 do  uzywajac:
(a) 10 punktów z zakresu;
(b) 100 punktów z zakresu.
(Matlab, Mathematica)
15. Napisz funkcje, obliczpoleprost, która oblicza pole prostokata dla podanych
długosci boków.
(Matlab, Mathematica)
16. Sinus hiperboliczny argumentu x jest zdefiniowany jako
sinh(x) =
ex − e−x
2
.
Napisz funkcje hipsin, która implementuje te definicje.
(Matlab, Mathematica)
17. Jezeli pewna suma pieniedzy P jest złozona na koncie bankowym o
oprocentowaniu r i rocznej kapitalizacji, to koncowa suma pieniedzy
po n latach jest dana przez
Tn = P(1 + r)n.
Napisz funkcje, która pobierajac argumenty P, r i n, oblicza koncowa
sume pieniedzy.
(Matlab, Mathematica)
18. Przyblizona wartosc funkcji silnia moze byc otrzymana za pomoca
formuły Stirlinga
n! 
p
2n

n
e
n
.
Napisz funkcje implementujaca te formułe
(Matlab, Mathematica)
19. Jezeli znane sa długosci dwóch boków trójkata i kat miedzy nimi, to
mozna obliczyc długosc trzeciego boku uzywajac formuły
a2 = b2 + c2 − 2bc cos .
Napisz funkcje obliczajaca trzeci bok w takiej sytuacji.
(Matlab, Mathematica)
4
20. Napisz funkcje wektormn, tworzaca wektor liczb całkowitych od m
do n niezaleznie od tego, który z tych parametrów jest wiekszy. Jezeli
m = n, to wektor bedzie miał jeden element.
(Matlab, Mathematica)
21. Napisz skrypt, który generuje losowo liczbe całkowita i drukuje czy ta
liczba jest przysta, czy nieparzysta.
(Matlab)
22. Napisz funkcje sumkrok2, która oblicza sume liczb od 1 do n z krokiem
2, gdzie n jest argumentem funkcji.
(Matlab, Mathematica)
23. Napisz funkcje geomsum, która pobiera wartosci r oraz n i oblicza
sume szeregu geometrycznego
1 + r + r2 + r3 + r4 + . . . + rn.
(Matlab, Mathematica)
24. Napisz funkcje, która pobiera macierz i oblicza srednia jej wszystkich
elementów.
(Matlab, Mathematica)
25. Zbuduj wektor, zawierajacy piec liczb losowych z zakresu od -10 do
10. Wykonaj na nim nastepujace operacje:
(a) odejmij 3 od kazdego elementu;
(b) oblicz ile elementów jest dodatnich;
(c) oblicz moduł kazdego elementu;
(d) znajdz element maksymalny.
(Matlab, Mathematica)
26. Wygeneruj losowo liczbe całkowita n, zbuduj wektor liczb całkowitych
od 1 do n z krokiem 2., podnies kazdy element tego wektora do
kwadratu i wykresl te kwadraty.
(Matlab, Mathematica)
27. Zbuduj wektor x, zawierajacy liczby całkowite od 1 do 10, i wektor
y równy x. Narysuj te linie prosta. Dodaj szum do danych budujac
wektor y2, przechowujacy wartosci y ± 0.25. Narysuj prosta i te „zaszumione”
punkty.
(Matlab, Mathematica)
5
28. Rozwiaz układ równan
4x1 − x2 + 3x4 = 10
−2x1 + 3x2 + x3 − 5x4 = −3
x1 + x2 − x3 + 2x3 = 2
3x1 + 2x2 − 4x3 = 4
(Matlab, Mathematica)
29. Znajdz pierwiastki równania f(x) = 0 dla nastepujacej funkcji
f(x) = 3x2 − 2x − 5.
Zbuduj wktory x i y i narysuj te funkcje w zakresie od -3 do 3.
(Matlab, Mathematica)
30. Oblicz wartosc wielomianu
3x3 + 4x2 + 2x2
dla x=6 i x=8.
(Matlab, Mathematica)
31. Zbuduj wektor x, zawierajacy liczby całkowite od 1 do 20, i wektor y,
zawierajacy liczby losowe z zakresu -2 do 2. Dopasuj linie prosta do
tych danych. Narysuj dane i te linie na jednym wykresie.
(Matlab)
32. Zbuduj wektory, zawierajace wspórzedne czterech punktów na płaszczyznie.
Dopasuj do nich funkcje liniowa i kwadratowa. Narysuj te
funkcje i punkty na wykresie
(Matlab)
33. Uzyj funkcji quad do przyblizenia powierzchni pod krzywa 4x2 + 3 w
przedziale (-1,3).
(Matlab)
34. Zaproponowano nastepujaca formułe opisujaca ewolucje populacji USA
P(t) =
19727300
1 + e−0.03134(t−1913.25) ,
gdzie t jest data podana w latach. Oblicz i wykresl te populacje miedzy
rokim 1790 a 2000 co 10 lat.
(Matlab, Mathematica)
35. Usun najwiekszy element z wektora x= [1 2 5 0 5].
(Matlab, Mathematica)
