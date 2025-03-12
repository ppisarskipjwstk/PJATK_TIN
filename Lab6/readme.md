## Laboratorium 6

# JavaScript - Programowanie Funkcyjne

## Teoria

* [Wykład Programowanie Funkcyjne](https://users.pja.edu.pl/~ppisarski/prez/new/TIN_JS_Programowanie_Funkcyjne.pdf)

## Zadania

### 1. Pola figur - Callback

Zadanie liczące pola figur (zajęcia 5, numer 7) przekształć by działało z wykorzystaniem Callback.

* Każda funkcja licząca pole (prostokąt, trapez, równoległobok, trójkąt), powinna być zapisana do zmiennej.
* Główny program powinien działać bez użycia instrukcji warunkowej (bez if, switch, pętli).
* Do głównego programu, funkcja licząca pole powinna być przekazana jako parametr

> pole(trojkat, 5, 6); //gdzie trojkat to funkcja zwracająca pole trójkąta
```
15
```

### 2. Cenzura

Napisz funkcję cenzurującą zdanie. 

* Funkcja ma otrzymać 2 parametry: zdanie do cenzurowania i niedozwolone słowo.
* Niedozwlone słowo ma zostać zastąpione znakiem `*`.

> cenzura("Ala ma kota i psa", "kot");
```
Ala ma *a i psa
```


### 3. Cenzura masowa

* Przerób swoją funkcję cenzurującą zdanie, by działała jako parametr funkcji `array.map()`.
* Efektem działania powinno być ocenzurowanie całej tablicy słów

> let tablica = ['kotlet', 'kotka', 'koty', 'pies'];
> let wynik = tablica.map(cenzura, {slowo: 'kot'});

```
['*let', '*ka', '*y', 'pies'] //wynik
``` 
