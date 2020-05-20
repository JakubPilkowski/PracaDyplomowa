PracaDyplomowa SportNewsManager
======
Aplikacja służąca do nadzorowania newsów piłkarskich
------

### Repozytoria (Na tę chwile są one prywatne(do omówienia z promotorem))
 __Aplikacja na androida__ (https://gitlab.com/Pilkowski/SportsNewsManager)
 
 __Backend__ (https://gitlab.com/Pilkowski/sportsnewsmanagerbackend) - Możliwa zmiana linku - wątpliwe, że będe robił w Django
 
 __Aplikacja webowa__ () - Nie wiem czy wymagana, narazie brak linku
 
### Tematyka pracy
Aplikacja ma za zadanie na podstawie kryteriów użytkownika wyświetlać newsy oraz dodatkowe treści (np wyniki meczów, transfery) z ulubionych lig bądź konkretnych zespołów. Aplikacja składa się z trzech głównych ekranów: `Newsy`, `Ulubione` oraz `Popularne`.
Główny ekran (Newsy) aplikacji będzie się zawierał wszystkie wybrane przez użytkownika newsy z przed kilku dni (najprawdopodobniej do 2). Każdy news składa się z:
* Logo strony internetowej z której pochodzi
* Nazwę strony internetowej
* Date dodania
* Głównego zdjęcia
* Tytułu newsa

Oprócz tego ekran `Newsy` będzie wyświetlał polecane newsy, które mogą się akurat spodobać użytkownikowi. 

Druga zakładka (Ulubione) będzie zbiorem ulubionych drużyn/lig jakie użytkownik wybrał. Z poziomu tego ekranu użytkownik
może usuwać wybrane drużyny/ligi.

Ostatnia zakładka (Popularne) będzie pokazywała strony internetowe, które są ostatnio popularne. Aplikacja będzie liczyła ilość kliknięć na daną stronę piłkarską i na jej podstawie będzie sortowała strony wyświetlające się. 

Każda z zakładek ma prawym dolnym rogu przycisk, która nawiguje do ekranu dodania drużyny. Użytkownik będzie mógł na podstawie podanych danych wybrać swoje ulubione ligi/drużyny.

Oprócz tego aplikacja będzie zawierała system logowania za pomocą facebooka, googla oraz ekran ustawienia, z poziomu którego będzie można np zmienić motywy aplikacji, zarządzać wyświetlaną zawartością (np wyświetlanie samych transferów lub samych wyników meczy),
wybrać domyślną zakładkę, zmienić język aplikacji itp, włączać/wyłączać powiadomienia.


### Diagramy przypadków użycia

DPU główny:
![DPU](/Diagramy/DPU.png)
PU dodaj drużynę jest odzielnie, ponieważ dodanie drużyny rozpoczyna się w każdej podstawowej zakładce (Newsy, Ulubione, Popularne)

PU zaloguj:
![PU Zaloguj](/Diagramy/PU_Zaloguj.png)

PU zarządzaj wiadomościami:
![PU Zarzadzaj wiadomosciami](/Diagramy/PU_Zarzadzaj_wiadomościami.png)

PU zarządzaj ulubionymi:

![DPU](/Diagramy/PU_Zarzadzaj_ulubionymi.png)

PU zarządzaj popularnymi stronami:
![DPU](/Diagramy/PU_Zarzadzaj_popularnymi_stronami.png)

PU zarządzaj ustawieniami:

![DPU](/Diagramy/PU_Zarzadzaj_ustawieniami.png)

### Struktura bazy danych


![DPU](/Baza_danych/BazaDanych.png)


### Scenariusze




### Mockupy



### Instalacja Aplikacji
