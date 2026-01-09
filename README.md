# Forest

Ez a projekt egy Three.js alapú 3D jelenetet jelenít meg Vite fejlesztői környezetben.

## Követelmények

- Node.js (ajánlott: 18+)
- npm

Ellenőrzés:
```bash
node -v
npm -v

## Telepítés

Függőségek telepítése:

npm install --save three
npm install --save-dev vite

A fejlesztői szerver indítása:

npx vite

## Fő elemek

- A színtér alapja – talaj ✅
- Legalább egy komplex objektum előállítása. Lehet stilizált, Three.js geometriákból összerakva, vagy Blenderben modellezve. ✅
- Legalább 3 különböző további alak/tárgy. (Fa, szikla, bokor) ✅
- Legyen megvilágítás, árnyékolás, animáció, interakció, szöveges információ. ✅

## Minimálisan szükséges, statikus geometriai modellek (2+2 pont)

Beépített Three.js geometriák használata (2 pont) ✅

- Legalább egy komplex objektum, valamint további legalább 3 kiegészítő. **(Komplex objektum: _szarvas_)** ✅
- A komplex objektum legalább 5 elemből álljon. ✅

Blender geometriai modellezés (2 pont). ✅

- A fenti geometriák közül legalább 1 legyen Blender-ben lemodellezett. **(Blender: _fa_)** ✅
- A beépített Blender hálók legyenek jól látható módon tovább szerkesztve! ✅
- Külön szöveges fájlban adjon rövid leírást a felszínhálók elkészítésének fontosabb lépéseiről! Miből indult ki, milyen szerkesztések történtek, stb. ✅

### Pontok: 4/4

## Mozgás és animáció (3 pont)

- Legalább 2 animált tereptárgy (vagy fény). ✅
- Legalább 1 db animáció, amely billentyűk vagy egér segítségével mozgatható. ✅
- Legalább 1 db animáció, amely időzítő segítségével önállóan változik/mozog. ✅

### Pontok: 3/3

## Interakció (2 pont)

- A színteret körbe lehessen forgatni egérrel és/vagy a kurzormozgató billentyűk segítségével. ✅
- A megvilágítás interaktív beállításával nappal és éjszaka választható legyen. ✅
- Az ablak bal felső sarkában jelenjen meg a programot készítő hallgató neve, NEPTUN azonosítója, valamint a szakja és az aktuális tanév megnevezése vászonra vetített szöveg segítségével. ✅
- Az ablak jobb felső sarkában jelenjen meg a használható billentyűk felsorolása a funkciók megadásával együtt. ✅
- A szöveges információkat ki/be lehessen kapcsolni az „I” (mint Információ) billentyűvel. ✅

### Pontok: 2/2

## Megvilágítás + árnyékolás (2 pont)

- Globális ambiens megvilágítás. ✅ 
- Legalább 2 db be-kikapcsolható pontfény vagy reflektorfény (pl. lámpa, reflektor, nap, hold, …). ✅
- Megvilágításra alkalmas anyag objektum használata (például Lambert vagy Phong). ✅
- Árnyékolás megfelelő használata. ✅
- Nappal és éjszaka váltás lehetősége. (Az árnyékolás megfelelő megvalósításának bemutatására.) ✅

### Pontok: 2/2

## Textúrázás (1 pont)

- Legalább 2 db objektum egymástól független, értelmes textúrázása (épület, jármű, égitest, szereplők, stb.). ✅

### Pontok: 1/1

## Alap pontszám: 12/12

## Plusz pontok (maximum 4 pont)

- Blender textúrázás 1 pont. ✅
- Fejlettebb textúrázás (bump, environment, normal, stb.) 1-1 pont, maximum 2 pont.

### Pontok: 4/2

## Összesített pontszám: 16/14