# **ELTE - JavaScript Technologiak**

## Ismerteto

A targy celja, hogy megismerkedjunk a JavaScript nyelvvel es az eppen aktualis modern, kore epulo technologiakkal, keretrendszerekkel.
Illetve, hogy nemi betekintest nyerjunk a web platformra valo alkalmazasfejlesztesre.

## Tematika

1. Bevezetes a *JavaScript* es a *Webt* vilagaba
2. Amit az *ECMAScript 7* szabvanyrol tudni erdemes
3. Aszinkron *JavaScript* fejlodese
4. **Node.js** es a szerver oldali *JavaScript*
5. *Web Components* technologiak
6. *Single-page application* **React.js** - ben
8. *Container* es *presentational* komponensek **React.js** - ben
7. **React.js** alkalmazas allapotkezelese **Redux** - al
8. *JavaScript* projekt eszkozkeszlet
9. Komponensek az **Angular.js** - ben
10. **Angular.js** alkalmazas allapotkezelese **Rx.js** - el *(opcionalis)*
11. Kitekintes a *TypeScript* / **Angular2** - re *(opcionalis)*

## Szamonkeres

A targy sikeres teljesitesehez a felev soran (legkesobb a vizsgaidoszak veget megelozo ket hetig) 2 beadando feladat megoldasanak leadasa szukseges.
A 2 beadando megoldasara egyetlen kriterium vonatkozik, kulonbozo kliens oldali keretrendszer / konyvtar segitsegevel kell elkeszulniuk.
Ezek lehetnek az oran bemutatott (Angular, React) keretrendszerek valamelyike, vagy egyenileg valasztottak.
A megoldasok ertekeleset az oran elhangzott ismeretek alkalmazasa hatarozza meg, illetve a kod minosege (skalazhatosag, karbantarthatosag, esetleg jol tesztelhetoseg) befolyasolhatja.

Az oldalon szereplo minta feladatok kozul (egy konnyebb es egy nehezebb) is lehet valasztani, akar a ket alkalmazas keszulhet
ugyanahoz a beadando feladathoz is. Termeszetesen sajat feladat megoldasat is be lehet adni, viszont ezeknek a komplexitasa legalabb
meg kell, hogy kozelitsek a minta beadando feladatok kozul a konnyebbiket.
Amennyiben ennek megallapitasa nem egyertelmu elozetesen tudunk egyeztetni a feladatokrol.

A megoldasokat email formajaban lehet majd bekuldeni (akar a teljes projektet vagy a remote repository linkjet).
A megoldasokrol pedig egy erdemjegy es egy szoveges ertekeles fog szuletni.

## Minta beadando feladatok

### #1 Linkek nyomon kovetese

A feladat egy olyan alkalmazas megvalositasa, amivel egy tetszoleges HTML forrasban tudunk linkeket beallitani nyomon kovetes celjabol.
* *(Nyomon kovetes alatt a linkek sajat magunkhoz valo atiranyitasat ertjuk, amin keresztul nyomon tudjuk kovetni, hogy a linkre kattintottak)*
* *(Egy link alatt a HTML ```<a>``` elemet ertunk)*

Az alkalmazas alljon ket kulon panelbol. Az egyik panel legyen egy szoveseges mezo (akar szerkeszto). A masik panel pedig jelenitse meg a szovegben talalhato
linkeket egy listaban, es tegye lehetove azok nyomon kovetesenek beallitasat.

A jobb oldali panel lehet egy sima szoveges mezo, ahova barmit be tudunk irni (textarea) vagy valami *okosabb* szerkeszto (CodeMirror, TinyMCE).

A bal oldali panel tartalmazzon egy listat, ahol egy lista elem a kovetkezo:

Nyomon kovetes | URL |
:--------------:|:---:|
[X] | http://www.google.com
[_] | http://www.twitter.com

Tovabba legyen egy kereso mezo, ami mindig a linkek URL - jeben keres es neveben keres. Egy linket akkor tekintunk ervenyesnek
ha a href attributumaban ervenyes URL cim talalhato.
Ha a szoveges mezo tartalma valtozik (esetleg link torlodik, adodik hozza), akkor a linkek listaja is azonnal frissuljon.
Az alkalmazas ujratoltese utan a linkek allapota ne vesszen el, mas bongeszobol valo megnyitas utan sem.
Az alkalmazas egy felhasznalo kiszolgalasara legyen kepes.

*(A legkonnyebben ugy tudjuk tarolni egy linken, hogy nyomon van kovetve, ha egy seged attributumot teszunk ra, pl.: tracked="true")*

## Feladatok

## Hivatkozasok
