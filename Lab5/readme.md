## Laboratorium 5

# Podstawy Javascript

## Teoria

* [Wykład JS](https://users.pja.edu.pl/~ppisarski/prez/js/1.html)

## Zadania

W każdym zadaniu należy napisać w Javascript funkcję, której wynik będzie widoczny w konsoli przeglądarki.

### 1. Pitagoras
Napisz funkcję, sprawdzającą, czy dane trzy liczby tworzą
   „trójkę pitagorejską” (uwaga – liczby nie muszą być podane w
   kolejności rosnącej).

### 2. Pętla
Napisz funkcję wypisującą wszystkie liczby z przedziału a-b,
   podzielne przez c.

### 3. Tabliczka mnożenia
Napisz funkcję wypisującą w konsoli tabliczkę mnożenia o
   boku podanym jako parametr.
> tabliczka(3);
```
1 2 3
2 4 6
3 6 9
```
### 4. Ciąg Fibonacciego
Napisz funkcję wypisującą w konsoli ciąg Fibonacciego o
   długości podanej jako parametr.

### 5. Choinka
Napisz funkcję rysującą choinkę o podanej wysokości.

> choinka(4);
```
*
**
***
****
```

### 6. Choinka nocą
Napisz funkcję rysującą „choinkę nocą” o podanej wysokości
   (szerokość jest tu nieco większa niż wysokość).

> choinkaNoca(6);
```
*********
**** ****
***   ***
**     **
*       *
*********
```

### 7. Pola figur: switch
Napisz funkcję liczącą pole wybranej figury (prostokąt,
   trapez, równoległobok, trójkąt) z wykorzystaniem instrukcji
   switch. Każda figura powinna mieć osobną funkcję do liczenia
   pola.

### 8. Pola figur: callback
Napisz funkcję liczącą pole wybranej figury (prostokąt,
   trapez, równoległobok, trójkąt) bez użycia instrukcji
   warunkowej (bez if, switch, pętli). Wykorzystaj funkcje
   anonimowe i callback.

### 9. Pascal
Napisz funkcję wypisującą w konsoli trójkąt Pascala o
   wysokości podanej jako parametr.

### 10. Cenzura
Napisz funkcję cenzurującą zdanie. Funkcja ma otrzymać 2
    parametry: tablicę niedozwolonych słów oraz zdanie do
    ocenzurowania. Każde niedozwolone słowo ma zostać zastąpione
    znakiem *.

> cenzura([‘Ala’, ‘kot’], ‘Ala ma kota i psa’ );
```
* ma *a i psa
```
