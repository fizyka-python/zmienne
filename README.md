# Zmienne

## Zamiana sąsiadów

Nazwa pliku:  `zamiania.py`

Proszę napisać program, który wczytuje z klawiatury dane oddzielone spacjami. Następnie ma on wydrukować te dane, ale parami
zamienione miejscami (`dane[0]` zamienione z `dane[1]`, `dane[2]` zamienione z `dane[3]` itd.). Jeżeli ilość danych jest
nieparzysta, ostatni element powinien pozostać na swoim miejscu.

Przykład:

    Podaj dane: 1 2 3 4 5 6 7 8 9  
    2 1 4 3 6 5 8 7 9

## Usuń co trzeci

Nazwa pliku:  `usun3.py`

Proszę napisać program, który wczyta co tekst z klawiatury, a następnie usunie z niego co trzeci znak (zaczynając od trzeciego).
Pozostałe znaki wydrukuje na ekranie.

Przykład:

    Podaj tekst: Ala ma kota.  
    Al m kta

## Najczęstsza litera

Nazwa pliku:  `najczestsza.py`

Proszę napisać program, który wczyta linijkę tekstu, a następnie wypisze najczęstszą literę w nim występującą. Program powinien
ignorować wielkość liter, a najczęstsza litera powinna być wydrukowana jako wielka. Jeżeli najczęstsza litera występuje
kilkukrotnie, wystarczy wypisać dowolną z nich. (dla chętnych — w takim wypadku w kolejnych liniach wypisać wszystkie litery,
o których można powiedzieć, że są najczęstsze)

Przykład:

    Podaj tekst: W Szczebrzeszynie chrząszcz brzmi w trzcinie  
    Z

W wersji zaawansowanej:

    Podaj tekst: Abba  
    A  
    B

Wskazówka: proponuję stworzyć słownik, przyporządkowujący danej literze ilość jej wystąpień. Ilość wystąpień danej litery można
poznać za pomocą metody `count` dla łańcucha tekstowego (proszę samodzielnie wyszukać jej dokumentację).
