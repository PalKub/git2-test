# Start w domu
Najprostszy sposób aby zaczać pracować:
1. Instalujesz gita w swoim systemie operacyjnym
2. Konfigurujesz tak jak w trakcie [zajęć](https://github.com/infoshareacademy/jjdzw2-materialy/blob/master/slajdy/04_2019-01-12_GIT-I.pdf):
  ```
  git config --global user.name "Imię i nazwisko"
  git config --global user.email "adres@email.pl"
  git config --global color.status auto
  git config --global color.branch auto
  git config --global core.editor vim
  ```
3. Klonujesz swoje repozytorium (przycisk clone or download, kopiowanie linku do repozytorium):
  ```
  git clone https://github.com/{USERNAME}/{nazwa-repozytorium}
  ```
4. Otwierasz folder `{nazwa-repozytorium}` w IDE IntelliJ
5. Modyfikujesz pliki
6. Dodajesz pliki do rejestru, robisz commit i pushujesz np.:
  ```
  git add .
  git commit -m 'Treść co zostało zmienione/dodane w języku angielskim'
  git push origin {nazwa-brancha}
  ```
7. Git powinien zapytać się o username i hasło

# Przykład ( Dzięki Adrian za sugestię :) )
1. git clone https://github.com/infoshareacademy/jjdzw2-homeworks.git  // klonujemy repozytorium
2. git branch imie.nazwisko  // tworzymy branch
3. git checkout imie.nazwisko  // przełączamy się na utworzony branch
4. dokonujemy zmian w odpowiednim katalogu, np. w zadaniu 4 :)
5. git add .
6. git commit -m 'Treść co zostało zmienione/dodane w języku angielskim'
7. git push origin imie.nazwisko

Koniec

Jeżeli pojawi się nowe zadanie robicie git pull ale pamiętajcie, że wcześniej musicie mieć wszystko spushowane

Czytajcie komunikaty w konsoli! Powodzenia!