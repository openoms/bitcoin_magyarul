###### [ **Bevezetés** ] -- [ [Bitcoin tárca](tarca.md) ] -- [ [Vásárlás](vasarlas.md) ] -- [[AntiFUD](antiFUD.md) ]

*Ez a dokumentum kezdőknek  való bevezetésre szolgál saját kutatás és tapasztalatok alapján. Folyamatos fejlesztés alatt. Javaslatokat és korrekciókat szívesen veszek.*

### Miért Bitcoin?

1. **Cenzúrázhatatlan**: senki sem tiltható el a használatától.
2. **Engedély-nélküli**: bárki részt vehet a hálózatban, az egyetlen feltétel, hogy kövesse a protokoll szabályait.
3. **Kötött mennyiségű**: a protokoll összesen 21 millió bitcoin létrehozását teszi lehetővé. Nincs senkinek a hatalmában ezt megváltoztatni.
4. **Lindy effektus**: minél tovább létezik annál nagyobb esélye van tovább fennmaradni. A Bitcoin blockchain 2009 január 3-án indult és azóta szakadatlanul termeli blokkjait.
5. **Páratlan biztonság**: jelenleg közel 40 Exahash/s számítási kapacitás biztosítja a hálózatot: <https://www.blockchain.com/charts/hash-rate?scale=1&timespan=all>\
Több mint 9 ezer publikusan elérhető node validálja és osztja a Bitcoin blockchaint és benne a tranzakciókat: <https://bitnodes.earn.com/>
6. **Skálázhatóság**: A rohamosan növekvő Lightning Network hamarosan egy teljes azonnali fizetőrendszerré fejlődik. Lehetővé teszi pl. a  hirdetési bevételek mikro-tranzakciókkal való helyettesítését. A Bitcoin Blockchainre épülő Lightning Network új fejezet a Bitcoin rendszerében, itt is meg fog érni egy külön lapot a részletes magyarázata. <https://1ml.com/statistics>

### Technikai összetevők

1. **Kriptográfia**: Nyílvános (public) és privát kulcs (private key) párokon alapul, amik lehetővé teszik a címek generálását és a tulajdonviszonyok bizonyítását. Lásd: PGP titkosítás:<https://hu.wikipedia.org/wiki/PGP>
2. **Peer-to-peer (p2p) hálózat**: a decentralizációt biztosítja. Nincs egy központi szerver ami a kéréseket kiszolgálja. A hálózatban résztvevő számítógépek az egymástól közvetlenül letöltött adatokból építkeznek. Nincs olyan pont, ami feltétlenül szükséges a hálózat működéséhez. Lásd: BitTorrent protokoll.
3. **Blockchain**: a blokkokat alkotó adatok oly módon fűződnek össze, hogy minden blokk tartalmazza az előző blokk hash-ét is így egymástól függetlenül nem változtathatóak, láncot alkotnak. A blockchain integritását a full node-ok ellenőrzik. Átlagosan 10 percenként adódnak a lánchoz 1-2 MB méretű blokkok. A Bitcoin blockchain 2018 végén 193 GB-ot foglal.
4. **Proof-of-Work (PoW)**: a blockchain bányászattal történő biztositása. Jelentős energiabefektetés nélkül lehetetlen a blockchainbe írni. A hálózat biztonságának a mutatója a hashrate, a bányászatot végző számítógépek összes számítási kapacitása. A bányászat nehézségét a protokoll 2016 blokkonként (kb. két hetente) újraértékeli és átlag 10 perces blokkidőt céloz meg.

---

### Továbbiak magyarul

A Bitcoin WhitePaper fordítása: <https://www.bitcoinbazis.hu/utmutato/szatosi-feher-konyv/>

Nem hivatalos oldal: \
<https://bitcoin.org/hu/> (vigyázz a bitcoin. com csalás)

---

### Angolul

Cypherpunk Manifesto (1993 március 9.):
<https://nakamotoinstitute.org/cypherpunk-manifesto/>

A Bitcoin WhitePaper (2008 október 31.):
<https://nakamotoinstitute.org/bitcoin/>

Elmélet a befektetés és használat mikéntjéről:
<https://github.com/PierreRochard/bitcoin-investment-theses>

Egy mindent átfogó gyűjtemény: <https://lopp.net/bitcoin.html>

Történeti esszé zenével:
<https://medium.com/@danhedl/planting-bitcoin-56bd1459cb23>

Kövesd az élő beszélgetést a (Crypto)Twitteren: <https://twitter.com/openoms>

---

### Az Osztrák gazdasági iskola alapjai

Könyvajánlat:

Murray N. Rothbard - Gazdasági Válságok: Okaik és gyógymódjuk
<https://libertarianizmus.hu/rothbard-valsagok/>

Saifedean Ammous -
The Bitcoin Standard: The Decentralized Alternative to Central Banking Hardcover
<https://www.amazon.co.uk/Bitcoin-Standard-Decentralized-Alternative-Central/dp/1119473861/>