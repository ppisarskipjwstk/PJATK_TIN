## Laboratorium 8

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

### 2. Prosta strona www z wykorzystaniem AJAX

Pod adresem:

https://jsonplaceholder.typicode.com

... dostępne jest testowe API zwracające dane - przykładowe posty, obrazy, komentarze. Jest tam też dokumentacja, jak go użyć.

Strona ma prezentować galerie zdjęć pobrane z API. 
Można używać JQuery oraz biblioteki do powiększenia zdjęć.

1. Widok strony głównej (lista albumów). Dane pobrane z adresu: https://jsonplaceholder.typicode.com/albums
2. Po kliknięciu na wybrany album pojawia się opis albumu oraz miniaturki zdjęć z wybranej galerii (wszystko ma się dziać bez przeładowywania strony lub przechodzenia na inną stronę). Dane pobieramy z adresu: https://jsonplaceholder.typicode.com/photos?albumId=xxx
3. Po kliknięciu w zdjęcie powinno się ono powiększyć (lightbox).
4. Formularz wysyłający dane (mockup zapisu nowego zdjęcia do danego albumu). Wysyłamy dane na adres: https://jsonplaceholder.typicode.com/photos (metoda POST, pola zgodne z obiektem photos, bez id)
5. Responsywność strony z wykorzystaniem media queries.





