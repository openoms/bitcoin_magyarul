###### [ **Bevezetés** ] -- [ [Bitcoin tárca](tarca.md) ] -- [ [Vásárlás](vasarlas.md) ] -- [ [Privát kulcs kezelés](private_key_management.md) ] -- [[ AntiFUD](antiFUD.md) ] -- [ [Magyar Bitcoin projektek](magyarok.md) ] -- [ [Bitcoin programozás](programozas.md) ]

*Ez a dokumentum kezdőknek való bevezetésre szolgál saját kutatás és tapasztalatok alapján. Folyamatos fejlesztés alatt. Javaslatokat és korrekciókat szívesen veszek.*

### Miért Bitcoin?

1. **Cenzúrázhatatlan**: senki sem tiltható el a használatától.
2. **Engedély-nélküli**: bárki részt vehet a hálózatban, az egyetlen feltétel, hogy kövesse a protokoll szabályait. Egy teljesen nyitott rendszer, nincs szükség API kulcsra vagy bármilyen engedélyre ahhoz, hogy bárki bitcoin címet generálhasson vagy tranzakciót küldhessen.
3. **Kötött mennyiségű**: a protokoll összesen 21 millió bitcoin létrehozását teszi lehetővé. Nincs olyan személy vagy hozzáférési szint, ami ezt a konszenzust megváltoztathatná.
4. **Lindy effektus**: minél tovább létezik annál nagyobb esélye van tovább fennmaradni. A Bitcoin blockchain 2009 január 3-án indult és azóta szakadatlanul termeli blokkjait.
5. **Páratlan biztonság**: jelenleg közel 40 Exahash/s számítási kapacitás biztosítja a hálózatot: <https://www.blockchain.com/charts/hash-rate?scale=1&timespan=all>\
Több mint 9 ezer publikusan elérhető számítógép (node) validálja és osztja a Bitcoin blockchaint és benne a tranzakciókat: <https://bitnodes.earn.com/>
6. **Oszthatóság**: A legkisebb egység 1 satoshi ami 0,00000001 bitcoin azaz 10 a -9-en BTC. 100millió satoshi = 1 bitcoin. Amikor 1 bitcoin 1 millió forintba kerül (kb. 3600 USD) 1 satoshi 1 fillért ér.
7. **Skálázhatóság és azonnali mikrotranzakciók**: A rohamosan növekvő Lightning Network hamarosan egy teljes fizetőrendszerré fejlődik. Lehetővé teszi pl. a  hirdetési bevételek mikro-tranzakciókkal való helyettesítését. A fizetési csatornákon történő tranzakciók nem kell, hogy a blockchainbe kerüljenek így azonnali megállapodást segítenek a felek között minimális díjért. Minden újabb csatorna növeli a küldhető összeg határát és az hálózat áteresztő-képességét. <https://1ml.com/statistics>

### Technikai összetevők

1. **Kriptográfia**: Nyílvános (public) és privát kulcs (private key) párokon alapul, amik lehetővé teszik a címek generálását és a tulajdonviszonyok bizonyítását. Lásd: PGP titkosítás:<https://hu.wikipedia.org/wiki/PGP>
2. **Peer-to-peer (p2p) hálózat**: a decentralizációt biztosítja. Nincs egy központi szerver ami a kéréseket kiszolgálja. A hálózatban résztvevő számítógépek az egymástól közvetlenül letöltött adatokból építkeznek. Nincs olyan pont, ami feltétlenül szükséges a hálózat működéséhez. Lásd: BitTorrent protokoll.
3. **Blockchain**: a blokkokat alkotó adatok oly módon fűződnek össze, hogy minden blokk tartalmazza az előző blokk hash-ét is így egymástól függetlenül nem változtathatóak, láncot alkotnak. A blockchain integritását a full node-ok ellenőrzik. Átlagosan 10 percenként adódnak a lánchoz 1-2 MB méretű blokkok. A Bitcoin blockchain 2018 végén 193 GB-ot foglal.
4. **Proof-of-Work (PoW)**: a blockchain bányászattal történő biztositása. Jelentős energiabefektetés nélkül lehetetlen a blockchainbe írni. A hálózat biztonságának a mutatója a hashrate, a bányászatot végző számítógépek összes számítási kapacitása. A bányászat nehézségét a protokoll 2016 blokkonként (kb. két hetente) újraértékeli és átlag 10 perces blokkidőt céloz meg.

---

### Továbbiak magyarul

A Bitcoin WhitePaper fordítása:  
<https://www.bitcoinbazis.hu/utmutato/szatosi-feher-konyv/>

Andreas M. Antonopoulos - 
Mastering Bitcoin Open Edition magyar fordítása:  
<https://bitcoinbook.info/wp-content/translations/hu/book.pdf>

Nem hivatalos oldal:  
<https://bitcoin.org/hu/> (vigyázz a bitcoin<i></i>.com csalás)

---

### Angolul

Cypherpunk Manifesto (1993 március 9.):  
<https://nakamotoinstitute.org/cypherpunk-manifesto/>

A Bitcoin WhitePaper (2008 október 31.):  
<https://nakamotoinstitute.org/bitcoin/>

Elmélet a befektetés és használat mikéntjéről:  
<https://github.com/PierreRochard/bitcoin-investment-theses>

Egy mindent átfogó gyűjtemény:  
<https://lopp.net/bitcoin.html>

Történeti esszé zenével:  
<https://medium.com/@danhedl/planting-bitcoin-56bd1459cb23>

Nick Szabo blogja:  
https://unenumerated.blogspot.com/

The Princeton Bitcoin kurzus és könyv:  
<http://bitcoinbook.cs.princeton.edu/>
<https://d28rh4a8wq0iu5.cloudfront.net/bitcointech/readings/princeton_bitcoin_book.pdf>

Kövesd az élő beszélgetést a (Crypto)Twitteren:  
<https://twitter.com/openoms>

---

### Az Osztrák gazdasági iskola alapjai

Könyvajánlat:

Murray N. Rothbard - Gazdasági Válságok: Okaik és gyógymódjuk  
<https://libertarianizmus.hu/rothbard-valsagok/>

Saifedean Ammous -
The Bitcoin Standard: The Decentralized Alternative to Central Banking  
<https://www.amazon.co.uk/Bitcoin-Standard-Decentralized-Alternative-Central/dp/1119473861/>  
Kalózverziók ebben a feedben:  
<https://twitter.com/saifedean/status/1067030051596718081>

Ingyenesen elérhető könyv a központi bankok működéséről:
Murray N. Rothbard - The Mystery of Banking  
<https://mises.org/library/mystery-banking>