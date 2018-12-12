# Privát kulcs kezelés

\[[Bevezetés](README.md)\] - \[[Bitcoin tárca](tarca.md)\] - \[[Vásárlás](vasarlas.md)\] - \[[Privát kulcs kezelés](private_key_management.md)\] - \[[AntiFUD](antifud.md)\] - \[[Magyar Bitcoin projektek](magyarok.md)\] - \[[Bitcoin programozás](programozas.md)\]

## ["Ha birtoklod a privát kulcsot akkor az a te bitcoinod, ha nem birtoklod, nem a te bitcoinod." \(Andreas Antonopoulos videó\)](https://www.youtube.com/watch?v=vt-zXEsJ61U)

Telefon, számítógép vagy hardver tárca elvesztése esetén az egyetlen esély bitcoinunk elérésére, ha a tárca generálásakor leírt seedből visszaállítjuk privát kulcsokat. Ez a seed a megjegyzés illetve tárolás egyszerűsítése végett 12-24 angol szóból áll amelyek közel random módon kerülnek kiválasztásra ebből a listából: [https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt) A szavakat az első négy karakter meghatározza, akár ennyit is elég leírni.

Ezt seedet lehetőleg ne elektronikusan tároljuk. Kis érték esetén egy papírlapon leírva biztonságos helyen tárolandó. A környezeti hatások \(elázás, tűz, stb.\) mellett attól is meg kell óvnunk, hogy mások a tudtunk nélkül hozzáférjenek. **Bárki, aki tudja ezt a seedet hozzáférhet a rajta tárolt bitcoinhoz.**

Papírlap helyett használhatunk fémlapot, amibe beleütve, vagy gravírozva a szavakat sokkal ellenállóbb lesz a környezeti hatásoknak. Egy borítékban leragasztva, esetleg számozott, hologramos biztonsági matricával védve elrejthetjük a kíváncsi szemek elől.

A 24 szót 2/3 - 2/3 - 2/3 arányban elosztva feloszthatjuk 3 papír- vagy fémlap között az ábrán látható módon:  
![](https://user-images.githubusercontent.com/32912678/42778987-f2c65fee-890c-11e8-82f6-3aeab7304f14.png)  
Így egy lap nem elegendő a tárca visszállításához, de bármelyik kettőből menni fog. A lapokat a fentebb leírt módon lezárt borítékban tároljuk 3 biztonságos, földrajzilag is elkülönülő helyen.

Időnként érdemes meggyőződni a borítékok érintetlenségéről, mert a seed 2/3-ának birtokában elvileg már lehetséges a maradék 1 harmad próbálgatással való megtalálása. Ehhez persze egy nagyteljesítményű számítógép \(pl. egy GPU rig\) és jelentős szaktudás szükséges. Ennek esélyét és az így tárolt maximális összeget mindenkinek magának kell fontolóra vennie. A módszer leírása angolul: [https://github.com/JWWeatherman/how\_to\_store\_bitcoin](https://github.com/JWWeatherman/how_to_store_bitcoin)

Nagyobb érték tárolására kifejlesztett maximálisan paranoid módszer angolul:  
[https://glacierprotocol.org/](https://glacierprotocol.org/)

Privát kulcsok tárolásának biztosítására szakosodott cég:  
[https://keys.casa/](https://keys.casa/)

