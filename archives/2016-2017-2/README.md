# **ELTE - JavaScript Technologiak**

## Idopont es helyszin
* **Idopont:** Kedd, 16:00 - 17:45
* **Helyszin:** Eszaki tomb, 2.63 - as terem, PC-8

## Ismerteto
* A targy elsodleges celja, hogy egy attekintest nyujtson a jelenlegi, modern webes technologiakrol,
legyen szo akar az aktualis JavaScript nyelvi elemekrol, a nyelvre epulo keretrendszerekrol es projekt eszkozokrol,
akar az aktualis webes API - krol es szabvanyokrol vagy a JavaScript nyelv szerver oldalon torteno felhasznalasarol
* A targy masodlagos celja, hogy az adott temakoroket ugy targyaljuk meg, hogy kozben figyelembe veszunk szoftverfejlesztesi
modszertanokat, elveket es technikakat, ugyelve ezzel a kodminosegre, az alkalmazasok architekturajanak megfelelo kialakitasara,
programozasi paradigmak tudatos felhasznalasara es minden olyan tenyezore, amit egy alkalmazas fejlesztese soran erdemes
figyelembe venni _(Megjegyzes: Egyetlen targyba keptelenseg belezsufolni mindent es azt megfeleloen atadni,
ennek a targynak sem ez a celja, de emlites szintjen mindenkeppen meg kell jelenniuk azoknak az ismereteknek, amelyek nelkul
egy szoftver helyes megvalositasa nem kivitelezheto. Pl. nem beszelhetunk ugy egy JavaScript keretrendszerrol,
hogy ne emlitenenk mondjuk a jelenleg is nepszeru komponens - alapu architekturat)_

A targynak nincs elofeltete, viszont a [Webfejlesztes 2](http://webprogramozas.inf.elte.hu/webfejl2.php) targy sikeres
elvegzese erosen ajanlott meg a JavaScript technologiak targy felvetele elott. Az ott elhangzott ismeretek nagyban
megkonnyithetik az ezen a targy soran elhangzottak megerteset es a targy sikeres teljesiteset.

A kurzuson nem vezetunk katalogust, viszont az orara valo bejaras erosen ajanlott, mivel a targy elvegzese az eddigi
tapasztalatok alapjan nem szokott sikerulni azoknak, akik a felev soran akar csak nehany alkalommal is hianyoznak.

## Tematika
* **1. - Bevezeto a JavaScript nyelvrol**
  * Diak: [link](http://slides.com/robertberetka/jstech-17)
  * Feladatok: [link](https://github.com/stoiet/elte-jstech-exercises/tree/master/lession01)
* **2. - Modularizalt es objektum-orientalt JavaScript #1**
  * Diak: [link](http://slides.com/robertberetka/jstech-17-19#/)
  * Feladatok: [link](https://github.com/stoiet/elte-jstech-exercises/tree/master/lesson02)
* **3. - Modularizalt es objektum-orientalt JavaScript #2**
  * Diak: [link](http://slides.com/robertberetka/jstech-17-19-20#/)
  * Feladatok: [link](https://github.com/stoiet/elte-jstech-exercises/tree/master/lesson03)
* **4. - Asszinkronitas kezelese JavaScriptben**
  * Diak: [link](http://slides.com/robertberetka/jstech-17-19-20-21#/)
  * Feladatok: [link](https://github.com/stoiet/elte-jstech-exercises/tree/master/lesson05)
* **5. - Ismerkedes a komponens-alapu architekturaval (ReactJS) #1**
  * Diak: -
  * Feladatok: -
* **6. - Ismerkedes a komponens-alapu architekturaval (ReactJS) #2**
  * Diak: -
  * Feladatok: -
* **7. - ReactJS alkalmazas allapotkezelese Redux-al**
  * Diak: -
  * Feladatok: -

## Szamonkeres

### Szamonkeres modja
A targyat egy beadando feladat (SPA alkalmazas) megoldasanak leadasaval lehet sikeresen teljesiteni.
A beadando feladat megoldasanak leadasa az egyetlen feltetele a targy sikeres teljesitesenek,
viszont az erdemjegy a kovetkezo szempontok alapjan all elo:
* a kod mennyire felel meg az oran targyalt konvencioknak (kodszervezes, clean code, best practises)
* komponens-alapu architektura kliens oldalon (smart/dumb komponensek, single-responsibility principle)
* az alkalmazas kodja az aktualis JavaScript szabvany (ES2017) es modern nyelvi *"feature"*-ok felhasznalasaval keszult
* az alkalmazas az oran targyalt eszkozok es keretrendszerek felhasznalasaval keszult

A bekuldott megoldasokrol egy ertekeles fog szuletni, amit az az alapjan megajanlott jeggyel egyutt fogok visszakuldeni.
Egy megoldas tobbszor is beadhato es finomithato - egeszen a leadasi hataridoig - a visszajelzesek alapjan, igy akar
jobb erdemjegyet is lehet szerezni. Konzultaciot csak abban az esetben tartok, hogyha arra van tenyleges igeny es ezt
jeleztetek is idoben.

Ha az alkalmazast nem sikerult teljesen befejezni a kiszabott hataridore (nehany funkcionalitas hianyzik),
akkor is javaslom az elkuldeset, mivel ha az elkeszult kod minosege tukrozi az igyekezetet es az oran targyaltak
elsajatitasat, akkor a targy elerte a celjat es ennek fejeben akar a targy teljesitese is sikeres lehet.

Arra felhivnam mindenki figyelmet, hogy a nagyon silany minosegu, osszecsapott megoldasok eseten - amelyeken latszik, hogy
se megfelelo mennyisegu idot nem szantak ra, se az oran elhangzottak nem lettek figyelembe veve - fenntartom a jogot arra,
hogy elegtelen megajanlott jegyet adjak ra, annak ellenere, hogy lett bekuldve *"valamilyen"* megoldas.

### Szamonkeres hatarideje
A beadando feladatot legkesobb junius 20 - ig lehet bekuldeni az alabbi email cimre: **to.stoiet@gmail.com**
A beadando feladatot vagy a teljes forraskod vagy remote repository link (Github/BitBucket) elkuldesevel
lehet leadni.

### Beadando feladat
**Keretrendszerek / eszkozok:**
* Kliens oldalon: ReactJS vagy AngularJS 1
* Szerver oldalon: NodeJS, KoaJS, MongoDB
* Csomagkezelo: NPM vagy Yarn
* Projekt eszkozok: Webpack es Babel

**Feladat:** Persona Preview

Kepzeljunk el egy olyan alkalmazast, amivel olyan HTML oldalakat lehet epiteni, amelyeket tudunk szemelyre szabni.
Az alkalmazasban fel tudunk venni *"persona"*-kat, akiknek meg tudunk adni egyedi adatokat, ezen kivul meg tudunk adni
egy olyan HTML template-t, amelyet egy adott *"persona"*-ra legeneralva megkapjuk azt az oldalt, amit az adott szemelynek
mutatnak a megfelelo adatai alapjan.

**Pelda:**
* Van N darab *"persona"*-nank, akikhez tartozik egy email mezo, benne a sajat email cimeikkel. Illetve van egy HTML template-unk,
ami az egyszeruseg kedveert nezzen ki igy: ```<b>Email: </b><span>{{ persona.email }}</span>```
Ha kivalasztunk egy *"persona"*-t - akinek az email cime mondjuk: persona@personamail.com - akkor az igy kapott generalt HTML
a kovetkezo lesz: ```<b>Email: </b><span>persona@personamail.com</span>```

**Elfogadasi feltetelek:**
* Lehessen megadni *"persona"*-kat, akik a kovetkezo mezokkel rendelkeznek: first_name, last_name, email, gender
* Mar felvett *"persona"*-k adatait lehessen utolag modositani
* Lehessen megadni egy tetszoleges HTML template - t
* Lehessen a generalt HTML eredmenyet egy kulon elonezetben (preview) megtekinteni *"persona"*-kent

## Feladatok
* [Orai feladatgyujtemeny](https://github.com/stoiet/elte-jstech-exercises)

## Ajanlott
* [Olvasnivalo](https://github.com/stoiet/elte-jstech-overview/blob/master/README.md)
* [Videok](https://github.com/stoiet/elte-jstech-overview/blob/master/VIDEOS.md)
