# Uruchamianie 
Wykonaj plik sql w Microsoft SQL Managment Studio
Otwórz folder z projektem za pomocą PyCharm, a następnie uruchom plik Projekt1.py

# Obłsługa
Podaj nazwę swojego serwera sql(aby wybrać domyślny - `localhost` - naciśnij enter) wpisując jego nazwę w konsoli
Aby dodawać, usuwać, modyfikować lub wygenerować raport  wpisz `ADD`, `DELETE`, `MODIFY`, `RAPORT` kiedy na kolsoli widnieje zapytanie `Wpisz: Add, Delete, Modify,Show, Raport, Leave`. Wybierz dla krótej tabeli chcesz przeprowadzić wybraną operację wpisując jej nazwę w konsoli.
Dalej postępuj według wskazówek/zapytań w konsoli wpisując odpowiedznie wartości.
Aby zamknąć aplikację wpisz `LEAVE` kiedy pojawi się pytanie `Wpisz: Add, Delete, Modify,Show, Raport, Leave`

Przykładowa interakcja dodawania:


`Wpisz: Add, Delete, Modify, Raport, Leave`

add

`Dodaj do: Anime, Studio, Characters`

anime

`Podaj tytuł(użyj ''):`

'Nowe'

`Podaj gatuenk(użyj '')(możesz zostawić puste):`

'Romans'

`Podaj liczbę odcinków(możesz zostawić puste):`

13

`Podaj id studia(możesz zostawić puste):`
4



Przykładowa interakcja usuwania:

`Wpisz: Add, Delete, Modify, Raport, Leave`

delete

`Dodaj do: Anime, Studio, Characters`

studio

`Usuń rekord taki, że kolumna studio_name jest równa:`

'WIT STUDIO'


Przykładowa interakcja modyfikacji:

`Wpisz: Add, Delete, Modify, Raport, Leave`
modify

`Dodaj do: Anime, Studio, Characters`

characters


`Zmodyfikuj rekord taki, że kolumna [id, first_name, second_name, anime_id, title, genre, no_of_episodes]:`

second_name

`jest:(=,<,>,<=,>=):`

=

`podaj wartość(użyj '' jeżeli wartość jest tekstem):`
null

`Zmodyfikuj zmienną [ 'anime_id', 'first_name', 'second_name']: second_name
aby była równa(użyj '' jeżeli wartość jest tekstem):`

'asd'




