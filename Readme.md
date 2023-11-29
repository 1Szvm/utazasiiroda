# Verzió kezelés

## Helyi repo lézrehozása

 - inicializálás:
    > git init
 - felhasználó ellenőrzése:
    >git config user.name

    >git config user.email
 - fájlok ellenőrzés
    >git status
 - előkészítés commit-ra
    >git add .
 - feltőltés
    > git commit -m "msg"

## Összekapcsolás egy távoli repoval

 - helyi repo össze kapcsolása:
    >git remote add origin "https://token@github.com/1Szvm/"file".git"

 - eltárolása az új verziónak:

    >git push -u origin master