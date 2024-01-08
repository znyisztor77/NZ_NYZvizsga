# NZ_NYZviszga
Német Zoltán Nyisztor Zoltán Vizsgaremek dokumentáció 

 

Az általunk készített alkalmazás egy lézer vágó cég raktár kezelését végzi, amelyben a raktárban tárolt alapanyagokat(különböző anyag típusok) és a megrendeléseket nyilván tartását végzi.
Az alkalmazásban nyomon követhető, hogy egy anyagot jelen esetbe egy lemez táblát a melyik dolgozó használta fel és melyik megrendeléshez. 
Az alkalmazás webes felhasználó felületű, amely a  Django Framework segítségével van megoldva. 
A webes felület tartalmaz egy qr kódot amely segítségével telefonon is kezelhető a felület. 

Django framework: https://www.djangoproject.com/ 

A Django Framework kezeli az Mysql adatbázist és segítségével van megjelenítve a webes kezelő felület. 
A adatbázist a XAMPP laklamazás kezeli.

XAMPP mysql webserver: https://www.apachefriends.org/hu/index.html

A felhasználói felület és az adtbázis közötti kapcsolatot a XAMPP alkalmazás biztosítja a Django Framework-ön keresztül. 

A webes kezelő felület html, css fájlokból tevődik össze. Az sql adatbázis kapcsolatot pedig a django framework biztosítja. 



---
A betöltő oldal egy bejelentkező (login)form.
Szükséges megadni a nevet és jelszőt.
A főoldal aszerint töltődik be, hogy ki fogja használni az alkalmazást.
1. admin
2. raktáros
3. operator(lézervágó)

Adim:
Teljes hozzáférés a raktárkezeléshez és adatbázis módosításáshoz.
- új dolgozó felvétele
- régi dolgozó törlése
- új anyagok rögzítése
- adatbázis karbantartása
  
Raktáros:
- anyag kiadása
- anyag bevétele
- hiány esetén megrendelés rögzítése

Operator:
- új munka rögzítése
- a munkához szükséges anyag kiválasztása
- befejezett munka rögzítése(szükség esetén munkalap nyomtatása)

Munkalap tartalma:
- a munka sorszáma
- felhasznált alap anyag
- munka kezdete
- munka vége
- dolgozó neve
- munka megnevezése ha van

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Fdhj0E8Fwr5VxQ5VDCPejjW%2FInventory-Management-system-(Community)%3Ftype%3Ddesign%26node-id%3D0%253A1%26mode%3Ddesign%26t%3Dpe2mPrLWeKtfYyed-1" allowfullscreen></iframe>


