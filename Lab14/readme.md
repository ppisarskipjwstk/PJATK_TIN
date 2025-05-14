## Laboratorium 14

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

