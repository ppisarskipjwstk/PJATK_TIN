## Laboratorium 11

# AJAX

## Teoria

* [Wykład AJAX](https://users.pja.edu.pl/~ppisarski/prez/ajax/1.html)

## Zadania

### 1. Prosta strona www z wykorzystaniem AJAX

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






