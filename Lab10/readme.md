## Laboratorium 10

# AJAX

## Teoria

* [Wykład AJAX](https://users.pja.edu.pl/~ppisarski/prez/ajax/1.html)

## Zadania

### 1. Notowania giełdowe

Pod adresem:

http://szuflandia.pjwstk.edu.pl/~ppisarski/zad8/dane.php

... dostępne są dane (generowane losowo kursy akcji oraz newsy giełdowe, zwracane w formie JSON).

Należy stworzyć prostą aplikację kliencką, która co jakiś czas samodzielnie
połączy się asynchronicznie z powyższym adresem i wyświetli dane w DOM, na przykład w formie tabelki.

1. Aplikacja (HTML, CSS, JS) z miejscem na wyświetlenie danych.
2. Połączenie (jQuery.ajax / XHR / Fetch itp.) między aplikacją a serwerem (np. co 5 sekund) i zmiana wyświetlanych danych.
3. Przy każdej cenie akcji należy wyświetlić również informację, czy cena zmieniła się względem poprzedniego notowania (wzrosła / spadła / nie zmieniła się; można to pokazać np. w formie strzałek lub koloru czcionki)
4. Zapamiętywanie 3 ostatnich newsów i wyświetlanie ich w formie rotatora.
5. Estetyczny styl CSS z responsywnością.





