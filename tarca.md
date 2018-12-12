# Bitcoin tárca

\[[Bevezetés](README.md)\] - \[[Bitcoin tárca](tarca.md)\] - \[[Vásárlás](vasarlas.md)\] - \[[Privát kulcs kezelés](private_key_management.md)\] - \[[AntiFUD](antifud.md)\] - \[[Magyar Bitcoin projektek](magyarok.md)\] - \[[Bitcoin programozás](programozas.md)\]

## Be your own bank - Légy a saját bankod

A bitcoin tárolása tárcákban \(wallet\) történik. A tárcák igazából egyetlen lényeges dolgot tárolnak: a privát kulcsot \(private key\), ami a coin elköltéséhez szükséges. Minden egyéb: a címek, a címeken ülő összegek mind kiolvashatóak a blockchainből.

A privát kulcs teljes hozzáférést ad a hozzá tartozó coinokhoz így különösen lényeges, hogy mennyire biztonságos a tárca-alkalmazás.

Internetes tárca használatát - legyen az bármelyik exchange vagy a blockchain.com - nem ajánlhatom, mert ezek esetében nincs a használó birtokában a privát kulcs így nem mondható, hogy az ott tárolt bitcoin az övé lenne. Kriptovaluták esetében egyelőre sehol sincs állami garancia arra, hogy hozzáférhessünk, ami számlánkon van így mindenkinek magának kell gondoskodnia a biztonságáról.

A legmegbízhatóbb általam jól ismert tárcák:

## Android

**Samourai Wallet**: [https://play.google.com/store/apps/details?id=com.samourai.wallet](https://play.google.com/store/apps/details?id=com.samourai.wallet)

## iOS

**Green Address**: [https://itunes.apple.com/app/id1206035886](https://itunes.apple.com/app/id1206035886)

## Desktop \(Linux/Mac/Windows\):

**Electrum**:  
A legnépszerűbb asztali tárca. Együttműködik a hardware walletekkel \(Trezor, Ledger, Coldcard\) és képes multi-signature címeket létrehozni. [https://electrum.org/\#download](https://electrum.org/#download)

**Bitcoin Core \(Full node\)**:  
[https://bitcoincore.org/en/download/](https://bitcoincore.org/en/download/)

**Wasabi wallet**:  
magyarok által fejlesztett, beépített CoinJoin-nal, ami a coinok történetét maszkolja el a blockchainen : [https://www.wasabiwallet.io/](https://www.wasabiwallet.io/)

## Hardver tárca \(hardware wallet\):

Nagyobb öszegek privát kulcsainak tárolására alkalmas.  A **Trezor One** a legrégebbi és legbeváltabb fajta: [https://trezor.io/](https://trezor.io/)

Bármelyiket választod a legfontosabb, hogy a privát kulcsok seedjét képező **12-24 szót írd le** a tárca első indulásakor, mert a hardver \(telefon, PC, Hardver tárca\) elvesztésekor csak a seeddel tudsz hozzáférni a coinjaidhoz. Lásd a [Privát kulcs kezelés](private_key_management.md) fejezetet.

