---
dg-publish: true
---
Formális definíció szerint véges sorozaton a természetes számok egy véges $\{1, 2, \ldots, n\}$ részhalmazán értelmezett, végtelen sorozaton (régiesen: haladványon) pedig a természetes számok halmazán (általában $\mathbb{Z}^{+}$-on) értelmezett függvényt értünk. A kérdéses természetes számokat (a sorozat értelmezési tartományának elemeit) indexeknek, a hozzájuk rendelt elemeket (a sorozat értékkészletének elemeit) a sorozat tagjainak nevezzük. Egy sorozat (leggyakoribb) jelölése: $(a_{1}, a_{2}, \ldots)$ illetve $(a_{n})$.

Időnként szükségünk van a semmilyen elemet nem tartalmazó üres sorozatra. Ennek hossza 0, és $()$-val vagy $\lambda$-val jelölik.

## A sorozat fogalmáról és jelöléséről

Szemléletesen, egy sorozaton dolgok (például: számok, függvények) egy listáját értjük, ahol a lista tagjainak sorrendje jól meghatározott. Egy elem többször is (akárhányszor) előfordulhat. Például a $(C,Y,R)$ betűk egy sorozata, ami különbözik az $(Y,C,R)$-től, hiszen a sorrend fontos. Amikor elemek egy sorozatáról beszélünk, akkor lényeges a tagok sorrendisége, rendezettsége, mely egyértelműen meghatározott. Ez a tulajdonság azonban nem alkalmas a sorozat fogalmának egyértelmű meghatározására. A különböző tárgyalási szinteken más és más sorozatfogalommal van dolgunk. Némely, elsősorban metamatematikai jelentőségű elméletben alapfogalomnak tekinthető, de az „alkalmazott” tudományágakban (ide tartozik az akadémikus matematika szinte egésze, mint például a halmazelmélet, az analízis, a számítógéptudomány stb.) általában származtatott fogalom.

### Véges és végtelen sorozat

A sorozatok lehetnek végesek, mint az előbbi példában, vagy végtelenek, mint például a pozitív páros számokból $(2,4,6,\ldots)$ képezett sorozat. A sorozat tagjait elemeknek (vagy tagoknak) szokás hívni, az elemek számát pedig a sorozat hosszúságának (ami végtelen is lehet). 

Véges sorozat – a véges matematikában, a formális nyelvekkel foglalkozó matematikai logikában és informatikában a véges sorozat lényegében a rendezett pár fogalmának általánosítása két elemről tetszőleges $ n $ természetes szám elemszámú elemre. Jelölése például:

$$
(a_{1}, a_{2}, \ldots, a_{n})
$$

Végtelen sorozat – ha egy végtelen elemet tartalmazó sorozatra, mint teljes egészre kívánunk hivatkozni, akkor elkerülhetetlen, hogy a végtelen matematikájának fogalmait használjuk, azaz a halmazelméletet. Ekkor a végtelen sorozaton a természetes számok $ \mathbb{N} $ halmazán értelmezett függvényeket értjük, melyfüggvények ílymódon maguk is rendezett párok speciális halmazai. Ekkor a sorozat jelölése inkább 

$$
(a_{n})_{n \in \mathbb{N}}
$$

vagy a $ f : \mathbb{N} \to H $ (ahol $ H $ tetszőleges halmaz) ritkábban 

$$
(a_{1}, a_{2}, \ldots, a_{n}, \ldots)
$$

Általánosított sorozat – a transzfinit matematikában a sorozat fogalma többféleképpen is általánosítható. Nem kell feltennünk, hogy $ \mathbb{N} $-en legyen értelmezve egy (általánosított) sorozat. Például elegendő, ha egy olyan rendezett halmazon, mely felfelé irányított vagy egy tetszőleges jólrendezett halmazon, sőt, elég, ha az összes rendszám osztályán értelmezett egyértelmű hozzárendelés. Ekkor is a sorozatokhoz hasonló tulajdonságú fogalmakat kapunk. Rekurzív sorozatok – ezek akárhány eleme kiszámítható a megelőző elemeinek segítségével. Ezekre természetesen gondolhatunk úgy is, mint halmazelméleti függvényekre, de nem eltekintve lényeges kiszámíthatósági tulajdonságától a rekurzív matematika egy alapfogalmaként is szerepeltethetjük. Egy rekurzív sorozat és egy halmazelméleti sorozat között különbséget tehetünk, amennyiben felfigyelünk arra, hogy a rekurzív sorozatok elemei véges eljárással, konstruktív módon adottak, ellentétben az általános halmazelméleti függvényfogalomtól, mely nem követeli meg semmilyen képlet létezését.

### Példák

$$
(1, 0, 0, 2, 1)
$$
egész számok ötelemű sorozata

$$
(\sin , \cos , \operatorname{tg} , \operatorname{ctg})
$$
trigonometrikus függvények négyelemű sorozata

$$
(2, 3, 5, 7, 11, 13, \ldots)
$$
Prímszámok sorozata

$$
(\{\}, \{1\}, \{1,2\}, \{1,2,3\}, \ldots)
$$
Halmazok végtelen sorozata

$$
(x_{0}, x_{1}, x_{2}, x_{3}, \ldots)
$$
Általános végtelen sorozat, nullától indexelve

## Sorozatok megadása

A sorozatokat különféleképpen lehet megadni:

- Az összes elem felsorolása (csak véges esetben)
- A kiszámítás módjával:
  - Függvényegyenlet
  - Sor
  - Rekurzió
  - Algoritmus

### Megadás első néhány elemmel

Az első néhány elemmel való megadás matematikailag problematikus, habár hasonló sorozatfolytatós feladatok intelligenciatesztekben is szerepelnek. Ennek az az oka, hogy képzési szabály hiányában a következő elem bármi lehet:

Az első néhány elem $0, 1, 2, 3$. A legvalószínűbb szabály az, hogy ez a természetes számok felsorolása, azaz a folytatás $4, 5, 6, \ldots$. Egy másik szabály lehet, hogy a sorozat periodikusan ismétlődik, azaz a folytatás $0, 1, 2, 3, 0, \ldots$, az egész számok maradékai néggyel osztva. De lehet más is a modulus, például öt, de semmi sem tiltja, hogy ez ne lehessen $232$, és ne előjeles maradékokat képezzünk. Ebben az esetben a sorozat: $0, 1, 2, 3, \ldots, 2147483647, -2147483648, -2147483647, \ldots, -1$, ami elölről kezdi a periódust. A $3, 1, 4, 1, 5$ sorozat egyik logikus folytatása $1, 6, 1, 7, \ldots$. De fel lehet ismerni a pi első számjegyeit is, és a sorozatot úgy folytatni, hogy $9, 2, 6, \ldots$. Igazából bármi lehet a következő szám. Interpolációval ugyanis lehet az adott elemekre polinomot illeszteni, melynek értékei megadják a sorozat hátralevő tagjait. Az On-Line Encyclopedia of Integer Sequences (OEIS) sok matematikailag releváns sorozatot tartalmaz. Ebben lehet részsorozat szerint is keresni.

### Megadás függvénnyel

Egyes sorozatok megadhatók függvénnyel, ami minden természetes számhoz kiszámolja a sorozat annyiadik elemét. Tehát elvégzi az

$$
i \mapsto a_{i}
$$

számítást. A következő példákban az $ \mathbb{N}_{0} $ indexeket használjuk.

A természetes számok: $0, 1, 2, 3, \ldots$ Képzési szabálya 

$$
a_{i} = i.
$$

A páratlan természetes számok: $1, 3, 5, 7, \ldots$ Képzési szabálya 

$$
a_{i} = 2i + 1.
$$

A $2$ hatványai: $1, 2, 4, 8, \ldots$ Képzési szabálya 

$$
a_{i} = 2^{i}.
$$

A függvény ismeretében az első néhány tag kiszámítható. Ehhez be kell helyettesíteni az $i = 0$,$i = 1$,$i = 2$, … értékeket, és elvégezni a számításokat. Ezzel a számolással meghatározható, hogy hogy viselkedik a sorozat eleje. Azonban ebből nem lehet messzemenő következtetéseket levonni. Példa erre az 

$$
a_{i} = \frac{1}{1 + (i - 1000)^{2}}
$$ 

sorozat, mely az első ezer tagjáig emelkedik, utána azonban újra csökken, ahogy azt a nagyobb tízhatványok is mutatják. A másik irány azonban nem ilyen egyértelmű, emiatt ezeket a feladatokat úgy szokták kitűzni, hogy könnyen észre lehessen venni a szándékolt szabályt. Néhány ilyen szabály:

Váltakozik-e az előjel? Ha igen, akkor a képzési szabályba bekerül egy 

$$
(-1)^{i}
$$ 

tényező. Ha a sorozat elemei törtek, akkor lehet külön szabályt keresni a számlálóra és a nevezőre. Például $1/1, 2/2, 3/4, 4/8, \ldots$ képzési szabálya 

$$
a_{i} = \frac{i + 1}{2^{i}}.
$$

Ha az elemek különbsége állandó, akkor a sorozat feltehetően számtani. A számtani sorozatok általános képzési szabálya 

$$
a_{i} = a_{0} + d \cdot i
$$ 

ahol $d$ a sorozat különbsége. Például az $1, 3, 5, 7, \ldots$ sorozat képzési szabálya 

$$
a_{i} = 1 + 2i.
$$

Ha az elemek különbségének különbsége állandó, akkor a sorozat másodrendű számtani sorozat, ami felfogható sorként. Például a háromszögszámok sorozata: $1, 3, 6, 10, 15, \ldots$, különbségeik $1, 2, 3, 4, \ldots$. Ha az elemek hányadosa állandó, akkor a sorozat mértani. A mértani sorozatok általános képzési szabálya 

$$
a_{i} = a_{0} \cdot q^{i}$$

ahol $q$ a sorozat hányadosa. Például a $100, 80, 64, 51.2, \ldots$ sorozat elemenként $0.8$-ed részére csökken. Képzési szabálya 

$$
a_{i} = 100 \cdot 0.8^{i}.$$

Előfordul, hogy a sorozat első elemei ismeretlenek. A szabály felismerését nehezítheti az egyszerűsítés is. Például a fenti $1/1, 2/2, 3/4, 4/8, \ldots$ törtekből álló sorozat egyszerűsítve $1, 1, 3/4, 1/2, \ldots$.

### Megadás sorként

A sor egy olyan sorozat, melynek $n$-edik eleme egy másik sorozat első $n$ elemének összege. Jelölje a sort 

$$
(s_{n})_{n \in \mathbb{N}} 
$$

a másik sorozatot 

$$
(a_{i})_{i \in \mathbb{N}} .$$

Ekkor teljesül, hogy 

$$
s_{n} = a_{0} + a_{1} + \ldots + a_{n} = \sum_{i=0}^{n} a_{i}$$ 

minden $n$-re. A szumma jellel írt 

$$
\sum_{i=0}^{n} a_{i} 
$$ 

kifejezés az 

$$
a_{0} + a_{1} + \ldots + a_{n} 
$$ 

kifejezés rövidítése. A szumma jelen belül és kívül különböző indexeket kell használni. Ahhoz, hogy kiszámoljuk 

$$
s_{n} = \sum_{i=0}^{n} a_{i} 
$$ 

értékét, ismernünk kell az $n$ értékét. Ezzel szemben az $i$ index nem egy előre adott szám, hanem befutja a $0, 1, \ldots,$  $n$ értékeket, és hozzájárul 

$$
a_{0}, a_{1}, \ldots, a_{n} 
$$ 

kiszámításához. Minden sorozat felfogható sorként, és konstruálható hozzá a különbségek sorozata, így a sorozat és a sor fogalma nem választható szét élesen. Az idősoranalízis sorai is sorozatok. Sok magyarázó modell azonban nem közvetlenül az abszolút értékeket, hanem azok időbeli változásait használja, tehát az abszolút értékeket sorként fogja fel. Különös jelentőséget nyer a sorozatok sorként való felfogása, hogyha az összegzés tetszőleges adott indexre elvégezhető. Például a számtani és a mértani sorozatok összegzési képlete ismert. A sorok vizsgálata segít eldönteni, hogy egy sorozat konvergens-e, és ha igen, akkor mi a határértéke. Egy sor konvergenciájából pedig következik, hogy a különbségsorozat konvergens, és határértéke nulla.

### Megadás rekurzióval

A rekurzióval való megadáshoz felsoroljuk az első néhány elemet, melyekből rekurzívan képezhetők rendre a sorozat elemei. Jelölje 

$$
m \geq 1$$ 

a felsorolt elemek számát, ekkor a rekurzió az 

$$
a_{i-m}, \ldots, a_{i-1} 
$$

elemekből számítja ki az 

$$
a_{i} 
$$ 

elemet. A legismertebb rekurzív sorozat a Fibonacci-sorozat. Itt 

$$
m = 2$$ 

az első két elem 

$$
a_{0} = 0$$ 

és 

$$
a_{1} = 1$$ 

illetve a rekurzív szabály 

$$
a_{i} = a_{i-2} + a_{i-1}.$$

Moivre és Binet explicit képlete az aranymetszéssel és az arany aránnyal áll kapcsolatban:

$$
a_{i} = \frac{1}{\sqrt{5}}\left(\left(\frac{1+\sqrt{5}}{2}\right)^{i}-\left(\frac{1-\sqrt{5}}{2}\right)^{i}\right) = \frac{\Phi^{i}-\bar{\Phi}^{i}}{\Phi - \bar{\Phi}}
$$

Ebben a felírásban is mindig egész elemeket kapunk, mivel 

$$
\sqrt{5}
$$ 

páratlan hatványai kiesnek. Egyes sorozatok esetén a függvénnyel való megadásból rekurzió vezethető le. Például a mértani sorozat 

$$
a_{i} = a_{0} \cdot q^{i} 
$$ 

képzési szabályából adódik, hogy 

$$
a_{i} = q \cdot a_{i-1}.
$$

Például az 

$$
a_{1} = 2, \quad a_{i + 1} = \frac{a_{i}}{2} + \frac{1}{a_{i}}
$$

rekurzió a $2, \frac{3}{2}, \frac{17}{12}, \ldots$, racionális számokból álló sorozatot definiálja, melynek határértéke 

$$
\sqrt{2}.
$$

### Megadás algoritmussal

Egyes sorozatokat nem függvénnyel, hanem algoritmussal szokás megadni. Egy ilyen sorozat a prímszámoké. Már az ókori görögök (és esetleg indiaiak) ismertek egy módszert, mellyel a sorozat elemei kiszámíthatók, ez Erathoszthenész szitája. Azonban nincs ismert módszer arra, hogy adott $i$ esetén meghatározzuk az $i$-edik prímszámot, anélkül, hogy ismernénk az összes nála kisebb prímet. Ha nem a tizedik vagy századik, hanem a 

$$
10^{20} 
$$ 

adik prímet akarjuk ismerni, akkor megugrik a számítási igény. Az egy sorozat kiszámításához szükséges legrövidebb algoritmus hossza a Kolmogorov-bonyolultsága. Néha ezt az elnevezést szűkebb értelembe, véges sorozatokra használják, melyek véges halmazba mennek. A pontos érték az algoritmust leíró programozási nyelvtől függ; azonban az invarianciatétel szerint ez a különbség egy nyelvfüggő additív konstans.

## A sorozatok típusai és tulajdonságai

Egy adott sorozat részsorozata egy olyan sorozat, amit az eredeti sorozat néhány elemének elhagyásával kapunk, anélkül, hogy az elemek egymáshoz viszonyított sorrendjét megváltoztatnánk.

### Monoton növekvő vagy csökkenő sorozatok

- Egy sorozat **növekvő**, ha minden $n$-re $a_{n+1} > a_n$.
- Egy sorozat **csökkenő**, ha minden $n$-re $a_{n+1} < a_n$.

Ha egy sorozat elemei egy részben rendezett halmaz részhalmazát alkotják, akkor monoton növekvő sorozatnak nevezzük azt a sorozatot, amelyben minden elem nagyobb, vagy egyenlő ($\geq$) az őt megelőző elemnél. Ha minden elem nagyobb ($>$) az őt megelőző elemnél, akkor a sorozat szigorúan monoton növekvő. A monoton csökkenő sorozatot hasonlóképpen definiáljuk. Ha e kettő közül bármelyik feltételnek eleget tesz a sorozat, akkor monoton sorozatnak nevezhetjük, ami a monoton függvény egy speciális esete. Az esetleges kétértelműségek elkerülése végett használhatjuk a nem-csökkenő, illetve nem-növekvő kifejezéseket is. Ha a sorozat elemei egész számok, akkor egész sorozatról, ha polinomok, polinom sorozatról beszélünk.

### Korlátosság

- Egy sorozat **felülről korlátos**, ha létezik egy $M$ szám, hogy minden $n$-re $a_n \leq M$.
- Egy sorozat **alulról korlátos**, ha létezik egy $m$ szám, hogy minden $n$-re $a_n \geq m$.
- Ha a sorozat mind felülről, mind alulról korlátos, akkor **korlátos sorozat**ról beszélünk.

Egy sorozat felülről korlátos, ha van egy $M$ szám, hogy minden $i \in \mathbb{N}$ esetén 

$$
a_{i} \leq M.
$$ 

Hasonlóan, egy sorozat alulról korlátos, ha van egy $m$ szám, hogy minden $i \in \mathbb{N}$ esetén 

$$
a_{i} \geq m.
$$ 

Egy sorozat korlátos, ha felülről és alulról is korlátos. A legkisebb felső korlát a sorozat szuprémuma, a legnagyobb alsó korlát a sorozat infimuma. Szintén általánosítható legalább részben rendezett halmazokra.

### Konvergencia

A végtelen sorozatok lehetnek konvergensek, azaz tarthatnak egy objektumhoz, vagy divergensek. Az analízis foglalkozik a sorozatok határértékével. Ez alapján definiálnak számos fontos fogalmat, mint függvények határértéke, folytonosság, deriválás és Riemann-integrál. A Taylor-sorokból előállítható analitikus függvények sorában máshonnan ismert sorozatok jelennek meg együtthatókként. Így az elemi függvények is, mint a tangens a Bernoulli-számokhoz vagy a szekáns hiperbolikus a Euler-számokhoz. Egy sorozat konvergenciájának bizonyítására fontos eszköz a teljes indukció. A korlátosság bizonyítható konvergenciakritériumokkal, például egy monoton és korlátos sorozat konvergens.

### További tulajdonságok

Ha egy sorozat elemeinek előjele váltakozik, akkor a sorozat alternáló. Ha egy sorozat minden eleme ugyanaz, akkor a sorozat konstans. Számok esetén számtani sorozat $0$ különbséggel, és mértani sorozat $1$ hányadossal. Ha az elemek rendezett halmazból valók, akkor a sorozat nemnövekvő és nemcsökkenő. Korlátos sorozat, infimuma és szuprémuma a konstans elem. Konvergens, és határértéke a konstans elem. Ha egy sorozat minden eleme egy adott indextől ugyanaz, akkor a sorozat stacionárius. Ha egy sorozat határértéke nulla, akkor az nullsorozat. Ha egy sorozat első néhány elemének ismétléséből áll, akkor a sorozat periodikus. Egy ismétlődő szakasz hossza a sorozat periódusa. Az analízis feladatai közé tartozik kideríteni, hogy egy sorozat konvergens-e, és ha igen, akkor mi a határértéke. A divergens sorozatoknak is lehetnek sűrűsödési pontjai, például a $-1/2, 3/4, -5/6, 7/8, \ldots$ sorozat sűrűsödési pontjai $-1$ és $1$. A Bolzano–Weierstrass-tétel szerint valós számok minden konvergens sorozatának van sűrűsödési pontja.

## Sorozatok az analízisben

A matematikai analízisben a sorozatokat általában ilyen formában említik:

$$
(x_{1}, x_{2}, x_{3}, \ldots)
$$ 

vagy 

$$
(x_{0}, x_{1}, x_{2}, \ldots)
$$ 

azaz elemek végtelen sorozata, természetes számokkal indexelve. (Néha kényelmes lehet, ha a sorozat nem $1$ vagy $0$ indexszel kezdődik. Például az 

$$
x_{n} = \frac{1}{\mathrm{lg}(n-5)}
$$

sorozat csak az $n \geq 7$-n értelmezett.) Végtelen sorozatoknál általában elégséges feltenni, hogy a sorozat elemei egy elég nagy $n$ (tehát nagyobb, mint valamilyen adott $N$) indextől kezdve definiáltak. A legelemibb sorozatok numerikusak, tehát valós vagy komplex számok sorozatai. Általában azonban egy sorozat az értékeit felveheti valamely vektortérből (például az analízisben gyakori esetben függvényterekből vagy topológiai térből), vagy legáltalánosabb esetben absztrakt halmazértékű sorozatokról is beszélünk.

## Sorok

Ha adott egy 

$$
(x_{n}) := (x_{1}, x_{2}, x_{3}, \ldots)
$$ 

sorozat, akkor részletösszegei 

$$
(S_{1}, S_{2}, S_{3}, \ldots)
$$ 

sorozata (ahol $ S_{n} $ a sorozat első $ n $ tagjának összege, a részletösszeg) nem más, mint az 

$$
(x_{n}) 
$$ 

-ből képezett sor. Például $(1, 3, 6, 10, 15, \ldots)$ az $(1, 2, 3, 4, 5, \ldots)$ sorozat sora. A soroknak számos matematikai alkalmazása van.

[[Számtani sorozat]]
[[Mértani sorozat]]
[[Hatványfüggvényen alapuló sorozat]]

### Végtelen sorozatok a számítógép-tudományban

Egy véges halmaz ábécéjéből kiválasztott számjegyek vagy karakterek végtelen sorozatait az elméleti számítógép-tudomány vizsgálja. Gyakran egyszerűen betűsorozatoknak vagy jelsorozatoknak nevezik őket (megkülönböztetve a véges hosszú stringektől vagy karakterláncoktól). Például a végtelen bináris sorozatokat a bitek (a $ \{0,1\} $ ábécéből vett karakterek) végtelen sorozata alkotja. Az összes végtelen bináris sorozatot tartalmazó 

$$ 
\mathcal{C} = \{0, 1\}^{\infty} 
$$ 

halmazt Cantor-térnek is nevezik. Egy végtelen bináris sorozat meghatározhat egy formális nyelvet (karakterláncok egy halmaza), ha a sorozat $n$-edik bitje akkor és csak akkor $1$-es, ha az $n$-edik karakterlánc (lexikografikus sorrend szerint) a nyelvhez tartozik. Ezért, a komplexitási osztályok elmélete, amely nyelvek halmazaival foglalkozik, tulajdonképpen végtelen sorozatok halmazait tanulmányozza. A 

$$ 
\{0, 1, \ldots, b-1\} 
$$ 

ábécéből vett végtelen sorozat meghatározhat egy $b$ számrendszerbeli valós számot is. Gyakran éppen ez az ekvivalencia teszi lehetővé a valós analízis eszköztárának felhasználását a komplexitási osztályokon.

## Általánosítások

A topológiában a háló a sorozatok általánosítása. A sorozatok lehetnek általánosított függvények is, egy osztály értékeit, például halmazokat felvéve.

## Sorozatterek

A sorozatokból sorozatterek képezhetők, melyeket a funkcionálanalízisben előszeretettel használnak példák képzésére.

## Lásd még

Számtani sorozat Mértani sorozat OEIS

### A sorozat fogalmának általánosításai

elemrendszer Háló (topológia)

### Speciális sorozatok

Nevezetes számsorozatok

### Sorozatanalízis

Numerikus sorozatok Cauchy-sorozat Sequence space Sorozat határértéke Sor

## Források

Bourbaki: Éléments de mathématique. Theorie des Ensembles II/ III, Paris, 1970 Harro Heuser: Lehrbuch der Analysis, Teil 1, Teubner Verlag, Stuttgart

## Fordítás

Ez a szócikk részben vagy egészben  a   Folge (Mathematik) című német Wikipédia-szócikk fordításán alapul.  Az eredeti cikk szerkesztőit annak laptörténete sorolja fel. Ez a jelzés csupán a megfogalmazás eredetét és a szerzői jogokat jelzi, nem szolgál a cikkben szereplő információk forrásmegjelöléseként.

## További információk

The On-Line Encyclopedia of Integer Sequences

## Jegyzetek
![[Family_of_parabolas.svg]]
![[Lagrange_polynomials_for_continuations_of_sequence_1%2C2%2C3.gif]]
![[Wikibooks-logo-hu.svg]]
