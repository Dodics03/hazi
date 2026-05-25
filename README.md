# Földrajzi Konzolos Kvízjáték

## Projekt leírása

Ez a program egy konzolos alapú földrajzi kvízjáték Python nyelven. A játék során a felhasználónak különböző városokról kell eldöntenie, hogy melyik országban találhatók.

Minden kérdéshez 4 válaszlehetőség tartozik, amelyek közül pontosan egy helyes.

A játék végén a program kiírja az elért pontszámot, valamint elmenti azt egy statisztikai fájlba.

---

## Funkciók

- 10 véletlenszerű kérdés minden játékban
- Kérdések külső fájlból ("kerdesek.txt") betöltve
- 4 válaszlehetőség minden kérdésnél
- Helyes/helytelen válasz visszajelzés, amennyiben helytelen, helyes válasz megadása
- Aktuális pontszám kijelzése minden kör után
- Korábbi pontszámok mentése ("statisztika.txt")
- Statisztikák megjelenítése a főmenüben
- Konzolos menürendszer

---

## Fájlszerkezet

projekt/
│── python_hazi.py
│── kerdesek.txt
│── statisztika.txt
│── README.md
│── specifikacio.pdf


### Fájlok szerepe

#### "python_hazi.py"
A játék teljes forráskódja.

#### "kerdesek.txt"
A kérdésbankot tartalmazza.

Formátum:

Város,Ország1,Ország2,Ország3,Ország4,Helyes_válasz_sorszáma

Példa:

Brno,Csehország,Lengyelország,Szlovákia,Ausztria,1
Lyon,Olaszország,Franciaország,Spanyolország,Belgium,2

#### "statisztika.txt"
A korábbi játékok pontszámait tárolja.

Példa:

pont:8
pont:5
pont:9

---

## A program működése

1. A program elindul és megjelenik a főmenü.
2. A játékos kiválasztja a **Játék indítása** opciót.
3. A program véletlenszerűen kiválaszt 10 kérdést.
4. A játékos válaszol a kérdésekre.
5. A rendszer minden válasz után visszajelzést ad:
   - helyes válasz
   - helytelen válasz
6. Megjelenik az aktuális pontszám.
7. A játék végén az eredmény mentésre kerül.
8. A statisztikák a főmenüből megtekinthetők.

---

## Használt technológiák

- Python 3
- "random" modul
- fájlkezelés ("open", "with")
- listák
- dictionary-k
- ciklusok
- függvények
- hibakezelés ("try-except")

---

## Program futtatása

1. Nyisd meg a projekt mappáját.
2. Ellenőrizd, hogy a következő fájlok jelen vannak:
   - "python_hazi.py"
   - "kerdesek.txt"

3. Futtasd a programot:

python_hazi.py

---

## Készítette

**Cserfai Dorottya**

Biomérnök hallgató – Python alapú földrajzi kvízjáték - Python programozás vegyészmérnököknek házifeladat.
