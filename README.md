# Projekt Telepítési Útmutató

Üdvözlünk a projektben! Az alábbiakban részletes útmutatót talál a fejlesztői környezet beállításához és az alkalmazás elindításához.

## Használt nyelvek és package-ek
- Frontend: Angular, TypeScript
- Backend: Node.js, Express
- Adatbázis és Backend közötti kapcsolat: Sequelize
- Adatbázis: MySQL

## Telepítés

Győződjön meg róla, hogy a következők telepítve vannak a gépén:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [Angular CLI](https://angular.dev/installation)

A telepítést követően ellenőrizheti, hogy a Node.js és npm megfelelően telepítve van, a következő parancsokkal:

```bash
node -v
npm -v
ng --version
```


## Klónozza le a repot
```bash
git clone https://github.com/tarrgabor/Moment.git
```
## Telepítse a függőségeket és indítsa el a szervereket
A klónozás után nyissa meg a projektet és nyisson meg 2 terminált.

Az 1. terminálba írja:
```bash
cd Backend
npm i
```
Várja meg amíg települnek a package-ek, majd írja be a következőt:
```bash
npm run dev
```
A 2. terminálba írja:
```bash
cd Frontend
npm i
```
Várja meg amíg települnek a package-ek, majd írja be a következőt:
```bash
ng serve
```
Miután elindította a frontend-et, ezen a linken érheti el: http://localhost:4200/
