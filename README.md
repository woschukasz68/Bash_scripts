# Bash_scripts

Skrypt user_dodaj 

Ma co najmniej trzy parametry.
Skrypt powinien dodać użytkowników w ilości opowiadającej nazwom podanym na liście
parametrów skryptu.
Podczas oddawania użytkownika należy stworzyć lub nie katalog domowy
(decyzja ma być podjęta na podstawie podanego parametru skryptu domT/ domN).
Ponadto należy ustawić domyślną powłokę w której będzie logował się nowo
utworzony użytkownik, przy czym określenie powłoki określone zostanie poprzez
podanie obowiązkowego parametru skryptu ( np. bash, sh, zsh).
Skrypt powinien tworzyć plik_logów, który będzie zawierał listing nowo dodanych
użytkowników wraz z datą ich dodania.
Kolejność parametrów: rodzaj powłoki, katalog domowy, nazwy użytkowników

Skrypt polacz_pliki  

ma co najmniej 2 parametry.
Nazwy plików tekstowych: pliki, plik1, .. , plikn .
Pliki podane jako parametr muszą istnieć i nie być puste. Program ma
zapisać połączenie wszystkich plików do pliku pliki
Należy sprawdzać czy:
- przekazano co najmniej 2 parametry,
- pliki istnieją, są niepuste i są plikami zwykłymi oraz czy mamy do nich prawo odczytu,
- czy mamy prawo zapisu do pliku

Skrypt info_zasoby

Ma co najmniej jeden ,a maksymalnie trzy parametry.
Podane parametry skryptu określają rodzaj szukanych plików ( f-plik zwykły, d-katalog,
l-dowiązanie symboliczne).
Po uruchomieniu podaje liczbę plików znajdujących się w bieżącej kartotece w
następującej formie:
Plików zwykłych: 7
Katalogów: 3
Dowiązań symbolicznych:0
oraz
Plików: +++++++
Katalogów:+++
Dowiązań symbolicznych:
Należy sprawdzić czy:
- Został podany co najmniej jeden argument wywołania skryptu i nie podano więcej
niż trzech argumentów
- podane argumenty odpowiadają odpowiednim literom alfabetu (f,d,l).
Jeżeli któryś literał nie został podany, to nie należy wyświetlać tekstu opisowego (
tj. gdybyśmy nie podali „f” to w wyniku nie powinien znaleźć się komunikat
„Plików zwykłych: ”

Skrypt prawa_dostepu

ma co najmniej 2 parametry i maksymalnie 4.
Zadaniem skryptu będzie nadawanie praw dostępu wszystkim plikom
znajdującym się w danym katalogu. Jako parametr skryptu należy podać: w postaci
numerycznej prawa dostępu (np. 731) oraz określić rodzaj zasobów według parametrów
skryptu określających rodzaj szukanych plików (gdzie: f-plik zwykły, d-katalog, ldowiązanie symboliczne).
Do testów proszę używać zasobów umieszczonych we własnym katalogu domowym!
Należy sprawdzić czy,
- są podane co najmniej dwa i nie więcej niż cztery argumenty wywołania skryptu,
- pierwszy argument jest zapisany w formacie trzech znaków,
- kolejne argumenty skryptu odpowiadają odpowiednim literom alfabetu (f,d,l).
