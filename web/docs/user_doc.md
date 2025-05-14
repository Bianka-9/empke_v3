# Felhasználói dokumentáció

## Telepítés

Lépések:

* Letöltés
* Függőségek telepítése
* Backend indítása
* Frontend indítása

### Letöltés

Töltsük le a következő helyről: 

* https://github.com/suli2024/in_empke2

Például:

```bash
git clone https://github.com/suli2024/in_empke2
```


### Függőségek telepítése és indítás

Backend:

```bash
cd api
npm install
npm start
```

Frontend:

```bash
cd web
npm install
npm start
```

## Dolgozók kezelése

A főoldalon a dolgozók listáját láthatjuk.

![Főoldal](img/home.png)
![Főoldal](img/home_with_arrow.png)

Új dolgozó felvétele a táblázat felett a "Hozzáadás" gombra kattintva lehetséges.

A **dolgozók az azonosítójukat automatikusan** kapják, ezt _nem lehet megadni vagy szerkeszteni_.

![Dolgozó hozzáadása](img/add.png)

A törlés a "Törlés" feliratú gombra kattintva kivitelezhető.

![Dolgozó törlése](img/delete.png)

Egy dolgozó szerkesztése a "Szerkeszt" gombra kattintva kezdeményezhető, az adott sorban.

![Dolgozó szerkesztése](img/modify.png)

Szerkesztés után meg kell nyomni a "Mentés" gombot, hogy eltárolja az adatbázis az új adatokat.

![Mentés](img/arrow_to_save.png)

