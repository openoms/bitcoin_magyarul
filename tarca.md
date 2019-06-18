# Bitcoin tárca

\[[Bevezetés](./)\] - \[[Bitcoin tárca](tarca.md)\] - \[[Vásárlás](vasarlas.md)\] - \[[Privát kulcs kezelés](private_key_management.md)\] - \[[AntiFUD](antifud.md)\] - \[[Magyar Bitcoin projektek](magyarok.md)\] - \[[Bitcoin programozás](programozas.md)\]

## Légy a saját bankod (Be your own bank)

A bitcoin tárolása tárcákban \(wallet\) történik. A tárcák igazából egyetlen lényeges dolgot tárolnak: a privát kulcsot \(private key\), ami a coin elköltéséhez szükséges. Minden egyéb: a címek, a címeken ülő összegek mind kiolvashatóak a blockchainből.

A privát kulcs teljes hozzáférést ad a hozzá tartozó coinokhoz így különösen lényeges, hogy mennyire biztonságos a tárca-alkalmazás.

Internetes tárca használatát - legyen az bármelyik exchange vagy a blockchain.com - nem ajánlhatom, mert ezek esetében nincs a használó birtokában a privát kulcs így nem mondható, hogy az ott tárolt bitcoin az övé lenne. Kriptovaluták esetében egyelőre sehol sincs állami garancia arra, hogy hozzáférhessünk, ami számlánkon van így mindenkinek magának kell gondoskodnia a biztonságáról.

## A legmegbízhatóbb, jól ismert tárca alkalmazások

* [GreenAddress](https://greenaddress.it/en/) - Androidra vagy iOS-re.
[Leírás képekkel angolul](https://getbittr.com/blog/how-do-i-set-up-a-blockstream-green-wallet).

* [Electrum](https://electrum.org/#download) - minden népszerű rendszerre elérhető. A legnépszerűbb asztali tárca. Együttműködik a hardware walletekkel \(Trezor, Ledger, Coldcard, stb. \) és képes multi-signature címeket létrehozni. 

* [Samourai Wallet](https://play.google.com/store/apps/details?id=com.samourai.wallet) - bizalmas adatkezelésre optimalizált alkalmazás Androidra

* [Wasabi wallet](https://www.wasabiwallet.io/) - 
Nyílt forráskódú, bizalmas adatkezelésre optimalizált Bitcoin tárca Windowsra, Linuxra és Mac-re. Beépített Tor anonimitási hálózattal, érmetársítási és érme-irányítási funkciókkal. Magyarok által fejlesztve.


* Bitcoin Core \(Full node\) 
[https://bitcoincore.org/en/download/](https://bitcoincore.org/en/download/)

## Hardver tárca \(hardware wallet\)

Nagyobb öszegek privát kulcsainak tárolására alkalmas. A **Trezor One** a legrégebbi és legbeváltabb fajta: [https://trezor.io/](https://trezor.io/)

Bármelyiket választod a legfontosabb, hogy a privát kulcsok seedjét képező **12-24 szót írd le** a tárca első indulásakor, mert a hardver \(telefon, PC, Hardver tárca\) elvesztésekor csak a seeddel tudsz hozzáférni a coinjaidhoz. Lásd a [Privát kulcs kezelés](private_key_management.md) fejezetet.

