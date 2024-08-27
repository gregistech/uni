---
dg-publish: true
---
A vektor a matematikában használatos fogalom, a lineáris algebra egyik alapvető jelentőségű mennyisége. Általában az ember a vektorokkal mint irányított szakaszokkal szokott találkozni, de a matematikában a jelentése ennél lényegesen bőségesebb. A fogalom különböző irányú általánosításai egyes tudományágakban is megjelennek. Így például a biológiában vektornak nevezik a fertőzéseket terjesztő élőlényeket, hatásokat. Az analógia teljesen világos, a hordozótól a fertőzöttig vezető utat pont a köztes gazda jelenti, azaz két pontot egy meghatározott irányban köt össze. A matematikában azonban sokkal elvontabb vektorokat is ismerünk. Ezek haszna sokszor a laikusok számára végképp nem nyilvánvaló, és ritkán ismertek, közismertek. Alkalmazásaik azonban széles körűek, különösen a modern tudományokban.

[[Két pontból vektor]]
[[Vektor hossza]]
## Általános leírás

A vektor a matematikában egy felettébb fontos fogalom. Alkalmazásai rendkívül sokrétűek, a geometriától az absztrakt analízisig mindenhol lehet velük találkozni. Ennek megfelelően az értelmezése is többféleképpen történhet. Maguk a vektorok a számok egyfajta általánosításainak is tekinthetőek. Ezzel a megközelítéssel főleg az algebrai definíciók dolgoznak, és ekkor legjellemzőbb alkalmazásaik az egyenletrendszerek kezelése. Mivel a fogalom eredete a fizika, ezért fizikai és geometriai meggondolások is szolgálhatnak alapjául, ekkor főleg a viselkedésük lesz a definíció alapja. A legközkeletűbb értelmezése a fogalomnak is geometriai: olyan szakasz, amit a nagyságán túl az iránya is jellemez. Ez szinte tipizálja a fogalmat, hiszen így olyan mennyiségeket, mint a sebesség vagy az erő, kényelmesen szemléletessé tudunk tenni. A vektorok legáltalánosabb, és így legmélyebb definícióját az analízisben találjuk, ahol a vektorok egy bizonyos típusú halmazhoz rendelhető másik halmaz elemei. Ez felettes értelmezése a fenti két definíciónak, hiszen mindkettőt magába foglalja.

## Definíció

### Lineáris algebra

Legyen ${\mathcal {E}}$ euklideszi geometriai tér. Ekkor a ${\mathcal {E}}\times {\mathcal {E}}$ halmaz elemeit, mint rendezett párokat irányított szakasznak nevezzük. Tekintsük most a térben a párhuzamos eltolásokat. Ezek segítségével ${\mathcal {E}}\times {\mathcal {E}}$ felett egy ekvivalenciarelációt határozhatunk meg. Két pontpárt, $(A,B)$-t és $(C,D)$-t ekvivalensnek tekintünk, ha van olyan $p$ párhuzamos eltolás, hogy $p(A)=C$ és $p(B)=D$. Az ekvivalenciarelációk a halmazt faktorhalmazokra bontják. Az ${\mathcal {E}}\times {\mathcal {E}}$ felett az előbbiekben bevezetett ekvivalenciareláció faktorhalmazait szabadvektoroknak, a faktorhalmazok elemeit a szabadvektor reprezentánsainak nevezzük.

### Geometria

A geometriában a vektorok az eltolások, mint transzformációk meghatározásában játszanak szerepet. Legyen ugyanis $\alpha$ és $\beta$ két párhuzamos sík. Ha a távolságuk $d\neq 0$, akkor a tér bármely $X$ pontjához olyan módon rendel hozzá egy $X'$ pontot, hogy $|XX'|=2d$. Ezen túl az $X$ és $Y$ pontok képe olyan, hogy $XX' || YY'$ és egyező irányításúak. Ezt a leképezést eltolásnak nevezzük. Világos, hogy az eltoláshoz elegendő az $(X,X')$ pontpárt megadni, mivel ez bármely pontnak a képét megadja a fentebbiek szerint. Az $(X,X')$ párt ekkor vektornak nevezzük. Eszerint egyébként a konkrét síkokra nincs is szükség, kizárólag a távolságuk és fekvésük lényeges. A fentebbiek során a lineáris algebrai definíció szerinti osztályozást is megvalósítottuk, tehát itt is lehet beszélni az adott irányítású és hosszúságú vektorok ekvivalenciaosztályáról, amit ez alapján szabadvektornak nevezünk. Ha rögzítünk egy $O$ pontot, akkor a szabadvektorok azon reprezentánsait, amik kezdőpontja $O$, kötött vektoroknak nevezzük. Ezek például egy koordináta-rendszer pontjait határozhatják meg.

### Analízis

Legyen $T$ test, $H$ pedig halmaz. Ha értelmezünk két függvényt:

\[
+:H\times H\rightarrow H,
\]

amit általában összeadásnak nevezünk, és 

\[
.:T\times H\rightarrow H,
\]

amit leggyakrabban skalárral való szorzás néven emlegetünk, úgy, hogy a $+$ asszociatív, kommutatív, invertálható és van neutrális eleme, valamint

\[
\forall \alpha ,\beta \in T \quad \text{és} \quad \forall x,y\in H \quad \text{esetén}
\]

\[
\alpha .(\beta .x)=(\alpha \cdot \beta ).x
\]
\[
(\alpha +\beta ).x=\alpha .x+\beta .x
\]
\[
\alpha .(x+y)=\alpha .x+\alpha .y
\]
\[
1.x=x
\]

teljesül, akkor $H$-t a $T$ test feletti vektortérnek nevezzük, $H$ elemeit pedig vektoroknak. Mint látható, az analitikus definíció olyan mértékben absztrakt, hogy egészen furcsa halmazokat is tudunk vektortérként kezelni. Ilyen lehet például a $T$-ben haladó konvergens sorozatok halmaza, vagy a $H\rightarrow T$ függvények halmaza.

[[Vektorműveletek]]

## Alkalmazások

A vektoroknak számtalan alkalmazása van. Ezek főleg a matematikához, fizikához és informatikához kötődnek. Legtöbbször egyfajta általánosítása a hagyományos vektorfogalomnak az egyes tudományágak saját fogalomalkotása, de az analógia legtöbbször nyilvánvaló.

### A matematikában

Jellemzően a lineáris algebrában fordulnak elő vektorok, illetve ehhez kapcsolódóan az analitikus geometriában. A lineáris algebra az egyenletrendszereket lineáris egyenletekhez hasonló módon kezelő eszközöket kap, ha az ismeretleneket és az egyenletek jobb oldalát egy-egy vektorként kezeljük, ekkor az együtthatók ugyanis egy leképezés mátrixának alakját fogja ölteni. Például. A koordinátageometriában a vektorok tulajdonképpen a pontokat jelölik ki, így helyvektorként funkcionálnak, a vektorokból pedig a fentebb említett műveletek segítségével a geometria legalapvetőbb ponthalmazai építhetőek fel. Ez egyben az összekötő kapocs is az algebra és a geometria között, aminek segítségével igazolható e két nagy terület egyenértékűsége. Ezen túl a vektor fogalom általánosabb, elvontabb formája segítségével az analízis sok fogalma is kényelmesebben kezelhetővé válik. Ilyen például az intervallum felett korlátos függvények halmaza, vagy egy test felett értelmezett operátorok tere. A vektorok segítségével lehet a Hilbert-tereket, mint speciális, skalárszorzatos tereket definiálni, amik a fizikai alkalmazások során nyernek jelentőséget, mivel a fizikai mennyiségeket a Hilbert-tereken ható operátorokkal jellemezzük.

### A fizikában

A fizikában a vektorokat más szemlélettel definiáljuk, mint a matematikában. Mivel a fizika a világot koordináta-rendszerekben írja le, a legfontosabb mennyiségeket a koordináta-rendszerek közötti átmenet szempontjából, azaz a transzformációk során mutatott viselkedésük szerint írjuk le. Az alaptípus a koordináta-rendszert kifeszítő, egységvektorokból álló generátorhalmaz. Ekkor vektornak nevezünk minden olyan fizikai mennyiséget, amelyek úgy transzformálódnak, mint a koordináta-rendszert kifeszítő egységvektorok. A vektorok azonban nem feltétlenül viselkednek azonosan a fentebbi meghatározással. A vektori szorzat esetén például a tükrözés során a két tényező előjelet vált, a szorzatvektor viszont nem:

\[
\left(-{\vec {x}}\right)\times \left(-{\vec {y}}\right)=\left(-1\right)^{2}\left({\vec {x}}\times {\vec {y}}\right).
\]

Az ilyen vektort, mivel tulajdonképpen egy tengelyt jelöl ki, axiálvektornak nevezünk. A köznapi szemlélet szempontjából a fizikai vektorok legfontosabb tulajdonsága, hogy a nagyságuk mellett irányításuk is van. Ez alapján definiálhatóak a vektormennyiségek: olyan fizikai mennyiség, amit két mennyiség, irány és nagyság jellemez. Ez egyben három paramétert igényel, azonban speciális esetekben a koordináta-rendszer megfelelő megválasztásával egy vagy kettő zérussá tehető. Ez az oka, hogy a bevezető fizikai tanulmányok során az egyenes vonalú mozgások, állandó irányú hatások játszanak elsődleges szerepet. A klasszikus fizika háromdimenziós vektorokkal foglalkozik, a relativisztikus fizika azonban a téridő leírására már négy paramétert alkalmaz, így itt a vektorok viselkedése teljesen váratlanná válhat a laikus szemlélő számára. A vektorokat három nagy csoportba sorolhatjuk: időszerű, fényszerű és térszerű vektorok. Az időszerű vektorok hosszának négyzete pozitív, ezen vektorokhoz mindig találunk olyan koordináta-rendszert, hogy a vektor az időtengellyel párhuzamos lesz. Ha két esemény időszerű kapcsolatban van egymással, akkor mindig van olyan megfigyelő, aki számára a két esemény ugyanott, de egymás után történik. A legegyszerűbb időszerű kapcsolat a kauzalitás, azaz az egyik pont, mint esemény, oka a másiknak. Ha egy vektor időszerű, akkor minden megfigyelő számára időszerű a kapcsolat, ez fejezi ki a relativitáselmélet determinisztikusságát. A térszerű vektorok hossznégyzete negatív, azaz ezekhez mindig találunk olyan koordináta-rendszert, aminek egy térbeli koordinátatengelyével párhuzamosak. A gyakorlatban a térszerű kapcsolat két esemény között azt jelenti, hogy van olyan megfigyelő, aki számára a két esemény egyszerre történik, de eltérő helyeken. A fényszerű vektorok hossznégyzete nulla, ezek tehát a koordináta-rendszerek transzformációja során nem változnak. Az elnevezés tükrözi szerepüket: a fényszerű vektorokat a fénysugarak jelölik ki, azaz a fény sebessége minden megfigyelő számára egyenlő.

### A számítástechnikában

A számítástechnikában általában az egydimenziós tömböket nevezik vektornak, ez megfelel ugyanis a vektorkoordináták mátrixreprezentációjának. Ugyanakkor azonban egy tömb elemei nem csak számok lehetnek, ennyiben a matematikai vektorfogalomtól el is tér. A konkrét értelmezés általában a programozási nyelv része. Például a C++-ban a Vector egy konténer osztály, aminek elemei tetszőleges, akár több különböző típusba tartozó adatok lehetnek.


![[Vector_addition3.svg]]
