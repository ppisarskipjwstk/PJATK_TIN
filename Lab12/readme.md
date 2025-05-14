## Laboratorium 12

# Node.js

## Teoria

* [Wykład Node](https://users.pja.edu.pl/~ppisarski/prez/new/TIN_Node.pdf)

## Zadania

### 1. Hello World w node.js

Stwórz skrypt, który - wywołany z parametrem przez node.js, wyświetli wiadomość powitalną, zawierającą słowo z parametru.

Przykład:
> node skrypt.js Jan
```
hello, Jan!
```

Podpowiedzi:
* Dokumentacja i instalacja node.js: https://nodejs.org/en (na komputerach uczelnianych jest zainstalowane)
* Aby uruchomić skrypt w node.js, w konsoli systemowej wchodzimy do folderu ze skryptem, a następnie uruchamiamy polecenie  node nazwa_pliku.js
* Aby uruchomić skrypt z parametrami, polecenie będzie wyglądało następująco: 
* node skrypt.js parametr1 parametr2 parametr3
* Dostęp do konsolowych parametrów w skrypcie JS mamy z poziomu tablicy process.argv

### 2. Prosty skrypt do obsługi plików

Stwórz skrypt z wykorzystaniem biblioteki fs (Filesystem). Skrypt powinien wykonywać proste operacje na plikach tekstowych. Oprócz właściwego pliku ze skryptem js, utwórz folder (np: “files”), a w nim kilka plików tekstowych z przykładowymi tekstami. Program ma umożliwiać:
* otwieranie pliku podanego jako parametr i wyświetlanie jego zawartości,
* dopisanie tekstu podanego jako parametr do zawartości pliku,
* kasowanie pliku podanego jako parametr.

Przykład:

> node skrypt.js open file.txt
```
Zawartość pliku file.txt: lorem ipsum dolor sit amet
```

> node skrypt.js append file.txt nowa_treść
```
Zapisałem do pliku file.txt: nowa_treść
```

> node skrypt.js delete file.txt
```
Usunąłem plik file.txt
```

> node skrypt.js open nie_istniejący_plik
```
Plik nie_istniejący_plik nie istnieje!
```

Podpowiedzi:
* Dokumentacja modułu fs: https://nodejs.org/api/fs.html 
* W katalogu z plikiem zadania utwórz plik package.json, a w nim wpisz: `{“type”: “module”}`  (pozwoli to na korzystanie z modułów w Twoim skrypcie)
* Następnie w konsoli, w tym samym katalogu uruchom polecenie npm install




