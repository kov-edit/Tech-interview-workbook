# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
Célja: 
    A munkatermékek és kód hibamegelőzés céljából történő kiértékelése
    Meghatározott követelmények teljesülésének igazolása
    Ellenőrzi, hogy a teszt tárgya tényleg beépült e és megfelel e az elvárásoknak
    Hibák megtalálása, kockázat szintjének csökkentése
    Minőségi szint biztosra meghatározása
    Működésének ellenőrzése
Nem célja:
    Garantálni a hibamentességet
    Mindent végigvizsgálni

#### ✅ Mik a tesztelési alapelvek?
A hibák jelenlétét mutatja, nem a hiányukat - nem garantálja a hibamentességet
Nem lehet kimerítő teszt - mindent letesztelni néhány eset kivételével nem lehet
Korai teszt: idő és pénz spórolás
Hibafürtök megtalálása
Nem csak egyfajta tesztelési technikát kell használni
Függ a tesztelés a körülményektől
A hibamentesség téveszme

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Komponenstesztelés, külön-külön teszteli a komponenseket, hogy megfigyelje a működést, hibákat találjon, csökkentse a kockázatot
A fejlesztő, főként nekik van hozzáférésük a kódhoz

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
Egységtesztelés - Egy komponens hogyan működik, legkisebb egység
Integrációs tesztelés - Az egységek, komponensek közötti működést vizsgálja
Rendszertesztelés - Teljes folyamatot teszteli
Rendszer integrációs tesztelés - Külső szolgáltató is ellenőrzi
Elfogadási tesztelés - Felhasználókat vagy megbízót bevonva tesztelik, hogy neki(k) megfelel e

#### ✅ Mi a különbség a verifikáció és a validáció között?
Verifikáció - A termék megfelel e a tervezési specifikációknak és követelményeknek
Validáció - A termék megfelel e a felhasználói igényeknek és elvárásoknak

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
Funkcionális - Teljesség, helyesség, megfelelősség a követelmények specifikációjának
Nemfunkcionális - Megbízhatóság, teljesítmény-hatékonyság, biztonság, kompatibilitás, használhatóság, a rendszer viselkedését nézi
Fehérdoboz tesztelés - A kód belső szerkezetét, munkafolyamatát, adatfolyamot vizsgál
Változásokhoz kapcsolódó teszt - 
    Ellenőrző teszt - Hibajavítás után az új szoftver verziót is teszteljük
    Regressziós teszt - Megnézi, hogy egy kód nem befolyásol e véletelenül egy másik egységet

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
Fehér doboz - A tesztelő a kódot és az adatáramlást látja, az alapján végez teszteket
Szürke doboz - A tesztelő részleges információval rendelkezik a belső működésről, és az alkalmazást kívülről és belülről is teszteli
Fekete doboz - A tesztelő nem ismeri a belső működést, a bemeneteket és kimeneteket vizsgálja

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
Felhasználói elfogadási teszt - A megbízó, végfelhasználó teszteli a programot, és ha minden részletnek megfelel, elfogadja
Rendszerteszt - A fejlesztők tesztelik a programot, hogy a nekik megadott szempontoknak megfeleljen amit írta

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
Regressziós teszt - Megnézi, hogy egy kód nem befolyásol e véletelenül egy másik egységet
Füsttesztelés - A rendszer megfeleljen az alapvető funkcionalitási és stabilitási követelményeknek, fontos korai lépés
Újratesztelés - Ha a hiba ki lett javítva, megnézik újra, hogy így már működik e

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
Statikus tesztelés - Munkatermék manuális vizsgálata, kód vagy más egység eszközvezérelt vizsgálata, fontos része a biztonsági tesztelésnek = a hibákat közvetlenül találja meg, kevesebb erőfeszítés mellett; felhasználható a munkatermékek konzisztenciájának és belső minőségének javítására
Dinamikus - A kód futtatása, futtatással tesztelés = hibák okozta meghibásodásokat azonosítjuk a szoftver futtatása során; a kívülről látható viselkedésekre fókuszál

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
V-modell - Integrálja a tesztfolyamatot, támogatja a korai tesztelést
Vízesés modell - A tesztelés csak akkor kezdődőhet el, ha miinden fejlesztési tevékenység befejeződött, az egyes tesztszintekhez kapcsolódó tesztek végrehajtása egymás után történik
Agile - Több részletben teszteli a rendszert, mivel a szoftver fokozatosan bővül, és a rendszer és több részletben van tervezve


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">
