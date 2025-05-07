## Laboratorium 13

# Websocket

## Teoria

* [Wykład Websocket](https://users.pja.edu.pl/~ppisarski/prez/new/TIN_Websocket.pdf)

## Zadania

### 1. Czat na Websocket - serwer.

* Stwórz projekt node.js. Załóż folder, w nim nowy plik server.js, a także package.json do skonfigurowania projektu.
* Użyj `npm install` by zainstalować projekt.
* Zainstaluj bibliotekę `ws` by używać jej w swoim projekcie, może być też `socket.io`, `Websocket` lub inna.
* Przy pomocy zainstalowanej biblioteki, zbuduj serwer socketowy.
* Serwer powinien nasłuchiwać na wiadomości i rozsyłać je wszystkim połączonym klientom

### 2. Czat na Websocket - klient.

* Stwórz dokument html, a w nim input na wpisanie wiadomości, przycisk do wysyłania oraz div, w którym pokażą się wiadomości otrzymane z serwera
* Stwórz kod Javascript, korzystający z obiektu WebSocket, który wyśle wpisaną wiadomość na serwer (a serwer roześle ją do wszystkich).
* Skrypt niech obsłuży event przyjścia nowej wiadomości z serwera, wyświetlając ją w wyznaczonym divie (jako append, by zachować wcześniejsze wiadomości)

### 3. Czat - rozbudowa

* Dodaj możliwość podania nicku na czacie - osobny input i przycisk "połącz".
* Dodaj wyświetlenie listy połączonych klientów na serwerze jako console.log
* Dodaj możliwość rozłączenia czatu od strony klienta.

### 4. Czat - prywatne wiadomości

* W momencie połączenia do czatu, serwer niech odeśle klientowi listę połączonych użytkowników.
* Dodaj po stronie klienta możliwość wysyłania prywatnej wiadomości (wybór adresata np. z listy rozwijanej).
