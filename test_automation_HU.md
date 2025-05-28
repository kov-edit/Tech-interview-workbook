# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
Célja: 
- A munkatermékek és kód hibamegelőzés céljából történő kiértékelése
- Meghatározott követelmények teljesülésének igazolása
- Ellenőrzi, hogy a teszt tárgya tényleg beépült e és megfelel e az elvárásoknak
- Hibák megtalálása, kockázat szintjének csökkentése
- Minőségi szint biztosra meghatározása
- Működésének ellenőrzése
Nem célja:
- Garantálni a hibamentességet
- Mindent végigvizsgálni

#### ✅ Mik a tesztelési alapelvek?
- A hibák jelenlétét mutatja, nem a hiányukat - nem garantálja a hibamentességet
- Nem lehet kimerítő teszt - mindent letesztelni néhány eset kivételével nem lehet
- Korai teszt: idő és pénz spórolás
- Hibafürtök megtalálása
- Nem csak egyfajta tesztelési technikát kell használni
- Függ a tesztelés a körülményektől
- A hibamentesség téveszme

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Komponenstesztelés, külön-külön teszteli a komponenseket, hogy megfigyelje a működést, hibákat találjon, csökkentse a kockázatot
A fejlesztő, főként nekik van hozzáférésük a kódhoz

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
- Egységtesztelés - Egy komponens hogyan működik, legkisebb egység
- Integrációs tesztelés - Az egységek, komponensek közötti működést vizsgálja
- Rendszertesztelés - Teljes folyamatot teszteli
- Rendszer integrációs tesztelés - Külső szolgáltató is ellenőrzi
- Elfogadási tesztelés - Felhasználókat vagy megbízót bevonva tesztelik, hogy neki(k) megfelel e

#### ✅ Mi a különbség a verifikáció és a validáció között?
Verifikáció - A termék megfelel e a tervezési specifikációknak és követelményeknek
Validáció - A termék megfelel e a felhasználói igényeknek és elvárásoknak

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
- Funkcionális - Teljesség, helyesség, megfelelősség a követelmények specifikációjának
- Nemfunkcionális - Megbízhatóság, teljesítmény-hatékonyság, biztonság, kompatibilitás, használhatóság, a rendszer viselkedését nézi
- Fehérdoboz tesztelés - A kód belső szerkezetét, munkafolyamatát, adatfolyamot vizsgál
- Változásokhoz kapcsolódó teszt  
    - Ellenőrző teszt - Hibajavítás után az új szoftver verziót is teszteljük
    - Regressziós teszt - Megnézi, hogy egy kód nem befolyásol e véletelenül egy másik egységet

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
- Fehér doboz - A tesztelő a kódot és az adatáramlást látja, az alapján végez teszteket
- Szürke doboz - A tesztelő részleges információval rendelkezik a belső működésről, és az alkalmazást kívülről és belülről is teszteli
- Fekete doboz - A tesztelő nem ismeri a belső működést, a bemeneteket és kimeneteket vizsgálja

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
- Felhasználói elfogadási teszt - A megbízó, végfelhasználó teszteli a programot, és ha minden részletnek megfelel, elfogadja
- Rendszerteszt - A fejlesztők tesztelik a programot, hogy a nekik megadott szempontoknak megfeleljen amit írta

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
- Regressziós teszt - Megnézi, hogy egy kód nem befolyásol e véletelenül egy másik egységet
- Füsttesztelés - A rendszer megfeleljen az alapvető funkcionalitási és stabilitási követelményeknek, fontos korai lépés
- Újratesztelés - Ha a hiba ki lett javítva, megnézik újra, hogy így már működik e

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
- Statikus tesztelés - Munkatermék manuális vizsgálata, kód vagy más egység eszközvezérelt vizsgálata, fontos része a biztonsági tesztelésnek = a hibákat közvetlenül találja meg, kevesebb erőfeszítés mellett; felhasználható a munkatermékek konzisztenciájának és belső minőségének javítására
- Dinamikus - A kód futtatása, futtatással tesztelés = hibák okozta meghibásodásokat azonosítjuk a szoftver futtatása során; a kívülről látható viselkedésekre fókuszál

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
- V-modell - Integrálja a tesztfolyamatot, támogatja a korai tesztelést
- Vízesés modell - A tesztelés csak akkor kezdődőhet el, ha miinden fejlesztési tevékenység befejeződött, az egyes tesztszintekhez kapcsolódó tesztek végrehajtása egymás után történik
- Agile - Több részletben teszteli a rendszert, mivel a szoftver fokozatosan bővül, és a rendszer és több részletben van tervezve


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">

## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
- Ha új a hiba akkor feljegyzem, felmérem a súlyosságát, és utána feltérképezem a lehetséges megoldásokat
- Ha már ismert hiba akkor a lehetséges megoldásokból másik módszert próbálok meg
- Mindkét esetben írnék hibajelentést

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
- Bemutatja a tesztevékenységek állapotát és előrehaladását a teszttervhez képest
- Megmutatják a haladást gátló tényezőket
- A jelentés tartalmazza a következő időszakra tervezett teszteléseket = a fejlesztők is tudnak ezzel tervezni
- Ismerteti a tesztobjektum minőségét, fel tudja mérni a minőségbeli változásokat
- Könnyebben kiszűrhetők a gyakori teszteléssel az eltérések a tervtől
- Felmérhetik a fejlesztők a fennmaradó kockázatokat = később kevesebb hiba lesz

#### ✅ Mit tartalmaz egy hibajelentés?
- A hiba azonosítója
- A hiba címe és rövid összefoglalója
- A bejelentés dátuma, a tesztelő neve aki megtalálta
- A tesztelt elem és a környezet azonosítója
- A fejlesztési ciklus fázisa ahol a hibát találták
- Hiba reprodukálását és megoldását lehetővé tevő leírás, beleértve a naplófájlokat, az adatbázismentéseket, képernyőképeket vagy felvételeket
- Elvárt és tényleges eredmények
- Hiba súlyossága
- Következtetések, ajánlások és jóváhagyások
- Hivatkozások, beleértve a problémát feltáró tesztesetet is

#### ✅ Hogyan rangsorolnál egy hibát?
- Kritikus
- Magas
- Közepes
- Alacsony

## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
- Automatomatizálni:
    - Sok esetet megvizsgáló teszt, például karakterlimitek tesztelése, bejelentkező adatok elfogadására irányuló tesztelés
    - Minden amihez az oldal többszöri lefrissítése és az adatok újboli beírása kell
- Nem automatizálni:
    - Egy-egy teszteset esetén, ahol csak kattintgatni kell az oldalon, esetleg csak egy-két fajta adatkombinációt kell kipróbálni
    - Olyan esetben, ahol nem várt hibákat keresünk, és valószínű, hogy eddig ismeretlen hibákba ütközünk

#### ✅ Írj le egy jó automatizált tesztet!
- Kis komponensekre van osztva a teszt
- A jelentésben megjelenik a tesztelő neve, a teszt hossza, eredménye, a környezet és az egyéb releváns adatok
- Gyorsan kapunk eredményt = csökken a teszteléssel töltött idő
- Könynen ismételhető

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
- A Selenium webalkalmazások automatikus tesztelésére szolgáló keretrendszer. Ez széles körben használható eszköz és az egyik legismertebb nyílt forrású teszteszköz
- A Selenium IDE egy Firefox add-on amely a böngésző interakciók egyszerű felvételére és lejátszására képes - beépített fejlesztői környezet, melynek jelentése, hogy az applikáció segít neked szoftvereket fejleszteni a segédprogramokon keresztül
- A WebDriver helyileg vezérli a böngészőt, ahogyan azt egy felhasználó tenné, akár helyben, akár egy távoli gépen a Selenium szerver használatával

#### ✅ Hogyan lehet azonosítani a webes elemeket?
- Id, class vagy a tag neve alapján (pl. p, div, stb.)

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
- Seleniumban a wait paranccsal kényszeresen várakoztatni tudjuk
- Ha várunk egy elemre akkor lehetséges hogy a tesztesetünkben van a probléma, például roszsul adtuk meg a helyét, vagy nem létezik az elem azon az oldalon ahol mi gondoltuk hogy lesz
- Lehet hogy egy előző elem befolyására nem tudjuk elérni az elemet
- Néhány esetben egy másik, akár számunkra nem látható elem is blokkolhatja az elemünket (pl a cookie settings, felugró hirlevél, stb.)

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
- A POM arra fókuszál ahogy a UI elemekkel interaktálsz, milyen a felépítés
- A keyword driven pedig a magasabb szintű tesztekkel foglalkozik, nem annyira része a design tesztelése

#### ✅ Mi a különbség a TDD és BDD között?
- TDD - automatizált teszteket ír a fejlesztő mielőtt megírja a kódot = segít a kód jobbá tételében, gyorsabban jönnek ki a hibák
- BDD - a rendszer viselkedése befolyásolja a fejlesztői változásokat, először felmérik a fejlesztők, hogy mit is szeretnének csinálni

#### ✅ Mi az API tesztelés és miért hasznos?
- Az API az alkalmazásprogramozási interfész rövidítése, és olyan definíciók, protokollok és szabályok összessége, amelyeket a fejlesztők az alkalmazásszoftverek készítésekor és a már meglévő rendszerekbe és platformokba történő integrálásakor használnak
- Egy API használatakor a magas szintű konzisztencia az egyik legfontosabb szempont. Ez kiszámíthatóvá teszi a fejlesztési folyamatot, és azt jelenti, hogy a felhasználók továbbra is integrálhatják szoftverüket a meglévő programokkal anélkül, hogy változtatniuk kellene a folyamataikon. Ennek a minőségi szintnek a megtalálása API-tesztelési folyamatot jelent
- Kisebb változtatásokat végezhet a kódbázisban, és korán meghatározhatja az API korlátait, a kézi tesztelés pedig nagyobb rugalmasságot tesz lehetővé, mivel sok apró módosítást végezhet
- Az ad hoc tesztelést a legjobb kézzel végezni, mivel egy-egy felmerülő kisebb probléma nem biztos, hogy megéri egy hosszú és bonyolult automatizált rendszeren keresztülmenni

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
- Adatvezérelt tesztelés egy szoftvertesztelési módszer, amelyben a tesztadatokat táblázat vagy táblázat formájában tárolják. Az adatvezérelt tesztelés lehetővé teszi a tesztelők számára, hogy egyetlen tesztszkriptet vigyenek be, amely képes tesztelni egy tábla összes tesztadatát, és a tesztkimenetet ugyanabban a táblában várja
- A tesztelők gyakran több adatkészlettel rendelkeznek egyetlen teszthez, és az egyes adatkészletekhez egyedi tesztek létrehozása időigényes lehet. Az adatvezérelt tesztelés segít az adatok elkülönítésében a tesztszkriptektől, és ugyanazok a tesztszkriptek futtathatók a bemeneti tesztadatok különböző kombinációihoz, és a teszteredmények hatékonyan generálhatók

#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?

#### ✅ Mik a mobil tesztautomatizálás kihívásai?

## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?
#### ✅ Írj le egy Continuous Delivery folyamatot!
#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
#### ✅ Mi a Docker és miért hasznos?