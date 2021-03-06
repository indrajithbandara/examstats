# Statistici examene bacalaureat și admitere la hackathonul [Date Deschise](datedeschise.ro)

Vrem să indexăm datele de pe http://admitere.edu.ro/ și http://bacalaureat.edu.ro/ și să facem statistici pe ele.

Hackers:

- @andreibordeianu
- @dranov
- @palcu

Împărțim proiectul în:

1. Achiziții de date - Python scrapper & parser
2. Frontend - Din SQLite, cu Flask, aruncăm datele în D3.js

## Install

```
pip install -r requirements.txt
```

## Milestone 1

- indexăm un județ mare și Bucureștiul
- precalculăm statistici
- stocăm datele în SQLite
- frontendul în Flask
- charts în [D3.js](http://d3js.org/)

Ce statistici afișăm prima dată:

- bar chart cu mediile la materii
- scăderi/creșteri de medii între generații
- uman vs real
- informații despre licee

    - evoluția studenților de la anumite licee - au intrat cu media X1 sau locul Y1, au ieșit cu media X2 și locul Y2
    - clase defalcate

## Milestone 2

- front page cu o hartă cu toate județele
- statistici în mare despre bacalaureat și admitere din 2013 - 2009
- hartă cu toate județele

## Milestone 3

- indexăm toți anii

## Milestone 4

- corelări cu date de la facultăți
- fete vs băieți (putem să folosim faptul că majoritatea numelor de fete se termină in "a")

## Milestone 5

- antrenăm rețele neuronale pe date să putem „ghici” notele pe care le poate lua un elev
