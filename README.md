# Odpalanie

```
docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/ jupyter/minimal-notebook
```

Następnie nalezy otworzyc link wypisany w terminalu:
```
http://127.0.0.1:8888/lab?token=7fc6e5f807c3badd17168ab05e8c6440b6333da8031a9cf9
```

# Kolejnosc modulow
Kazdy rozdzial posiada w nazwie numer - jest to "domyslna" kolejnosc, zgodnie z ktora przerabiamy material na szkoleniu.
Nie oznacza to jednak, ze to jedyna mozliwosc - w zaleznosci od oczekiwan grupy i postepow w trakcie szkoloenia kolejnosc moze zostac zmieniona.
Projekcik rozwijany w trakcie szkolenia jest podzielony na zadania, ktorym odpowiadaja tagi w repozytorium gitowym. W kazdym momencie istnieje
mozliwosc przelaczenia sie na dane zadanie, nawet jesli nie ukonczylo sie poprzedniego lub zmienilo sie kolejnosc.

1. Wprowadzenie
2. Moduly i biblioteki
3. Listy, slowniki, zbiory
4. Comprehensions
5. Pliki
6. Testy
7. Programowanie obiektowe
8. Wyjatki
9. Typy
10. Funkcje i zakresy
11. Dekoratory
12. Managery contextu
13. Generatory
14. Paczkowanie kodu
15. Aplikacje terminalowe
16. Debugowanie i profilowanie kodu
17. HTTP
