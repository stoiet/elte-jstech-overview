# **Jegyzet**

### **Modulok**

A JavaScript nyelv hosszu ideig nem rendelkezett szabvanyba foglalt, sajat modul rendszerrel. A fejlesztok igy kenytelenek voltak sajat maguk megoldast talalni pl. a globalis nevter szennyezesenek problemajara, ujrafelhasznalhato es egysegbe zarhato es konnyebben karbantarthato kodok irasara.

Nehany megoldas konvenciova notte ki magat es sokaig "szabvanykent" tekintettek ra a fejlesztok, de termeszetesen az igazi megoldast az EcmaScript2015-os szabvanyban bevezetett modul rendszer jelentette. A webes vilag egyik meghatarozo tenyezoje a visszafele kompatibilitas, igy a korabbi szabvanyokra forditott JavaScript kodokban meg mindig fellelhetoek a korabbi mintak.

Meghatarozo modul konvenciok:
* CommonJS - szinkron betoltodesre alkalmazott modul "szabvany", NodeJS eseten meg mindig a default modul rendszer
* AMD - aszinkron betoltodesre alkalmazott modul "szabvany", sokaig a bongeszoben futo kodot RequireJS segitsegevel bontottak modulokra es toltottek be
* UMD - mind szinkron es aszinkron betoltodesre, bongeszos es NodeJS alatti futtatasra alkalmas modul szabvany, JavaScript package-ek eseten fontos volt mind ket esetet tamogatni

A jelenlegi EcmaScript2017-es (egeszen EcmaScript2015 ota) szabvanyban definialt modulok eseten egy fajlt a nyelv egy modulnak tekint, ami egy vagy akar tobb fuggvenyt, objecktumot, osztalyt, stb. szolgalhat ki.

```javascript
// classes.js
export class ClassA {}
export class ClassB {}
```
```javascript
// index.js
import { ClassA, ClassB } from './classes';
```

A szabvany tamogatja a tovabb "exportalas" lehetoseget is, amire akkor lehet szuksegunk, ha tobb definiciot akarunk egy kozos fajlon keresztul elerhetove tenni, pl.:
```javascript
// other.js
export * from './classes';
```

Erdekesseg, hogy sok nyelvben ugynevezett "namespace"-eket alkalmaznak a nevutkozes elkerulesere. JavaScript eseten erre nincs szukseg, ugyanis az adott definicio "behasznalasa" helyen lehetosegunk van atnevezesre, pl.:
```javascript
// other.js
import { ClassA as A } from './classes';
```

Tovabbi anyagok:
* [JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)
* [Writing Modular JavaScript](https://addyosmani.com/writing-modular-js/)
* [Szabvany](https://www.ecma-international.org/ecma-262/8.0/#sec-modules)
