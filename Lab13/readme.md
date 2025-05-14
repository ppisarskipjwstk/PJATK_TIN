## Laboratorium 13

# Node.js

## Teoria

* [Wykład Node](https://users.pja.edu.pl/~ppisarski/prez/new/TIN_Node.pdf)

## Zadania

### 1. Prosty serwer w node.js

Stwórz prosty serwer w node.js o funkcjonalnościach takich jak w zadaniu 2. Serwer będzie przyjmować requesty i wykonywać polecenia:
* GET: otwiera plik podany w parametrze i zwraca jego zawartość
* POST: otwiera plik podany w parametrze i dopisuje do niego zawartość, również podaną w parametrze
* DELETE: usuwa plik podany w parametrze

Przykład:

Konsola:
> node serwer.js
```
Serwer działa na porcie 3000
```

Przeglądarka:
> http://localhost:3000/plik.txt 
```
Zawartość pliku plik.txt: lorem ipsum dolor sit amet
```

Podpowiedzi:

* Przykładowy prosty serwer w node.js: https://www.tutorialsteacher.com/nodejs/create-nodejs-web-server
* Requesty można wywoływać poprzez przeglądarkę, konsolę (cURL), aplikację Postman lub własny kod JavaScript z AJAX.





