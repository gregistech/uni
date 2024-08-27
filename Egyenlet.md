---
dg-publish: true
---
[[Lineáris egyenlet]]
[[Másodfokú egyenlet]]

[[Gyökös egyenlet megoldása]]
[[Exponenciális egyenlet megoldása]]
[[Logaritmusos egyenlet megoldása]]

[[Egyenletrendszer]]

Az egyenlet a matematikában egyenlőségjellel összekapcsolt két kifejezés. A két kifejezést az egyenlet bal és jobb oldalának nevezzük. Az egyenlet az algebra, sőt az egész matematika egyik legfontosabb fogalma. Például $$3|x|+1=2$$ egy egyszerűbb egyenlet, melynek bal oldala a „3 · |x| + 1” kifejezés, jobb oldala pedig az egyetlen számból álló „2” kifejezés. Az ismeretlenek előtt álló állandó szorzókat gyakran az egyenlet együtthatóinak nevezzük. Mint ahogy a kifejezések, ebből következően az egyenletek is többnyire (bár nem kötelezően) változókat vagy határozatlan mennyiségeket is tartalmaznak, melyeket ismeretleneknek nevezünk (a fenti példában az $x$ az ismeretlen). Az egyenletek, ill. egyenlőtlenségek többnyire kétféle alapvető helyzetben szoktak előkerülni:

Egy, akár elméleti, akár gyakorlati probléma megfogalmazása során számszerű összefüggéseket sikerül feltárni a problémával kapcsolatos legfontosabb mennyiségeket leíró változók között, és a probléma valamely paraméterek konkrét értékének megkeresését igényli (például mennyi festékmennyiség kell adott területű fal lefestéséhez). Ez tipikusan a matematika alkalmazásának szituációja. Ilyenkor az egyenletek megoldásán van a hangsúly. Inkább elméleti igényű az a feladat, amikor valamilyen - nem feltétlenül absztrakt - struktúra általános, mennyiségi jellegű leírása a cél. Például a mechanikai testek mozgása mozgásegyenletekkel, a hővezetés differenciálegyenletekkel stb. írható le a fizikában, a matematikában pedig a geometriai alakzatok adhatóak meg egyenletekkel (pl. egy origó középpontú, 1 sugarú kör egyenlete $$x^{2}+y^{2}=1$$). Ilyenkor az egyenletek által leírt összefüggések egyrészt akár fontosabbak is lehetnek, mint a megoldásuk, másrészt a megoldás folyamata meg is fordulhat (például egy parabola egyenletét felírva, a megoldáshalmaz adott, és ehhez kell egyenletet keresni). Ha mást nem mondunk, akkor az egyenletekben szereplő műveleti jelek és függvényjelek a valós vagy komplex számokon értelmezett szokásos műveletek és függvények, a számok valós ill. komplex számok, és az ismeretlenek értéke is valós vagy komplex. Azonban természetesen más struktúrákban is értelmezhető az egyenlet fogalma (amint ezt a hővezetés differenciálegyenleteinek példája is mutatja). Az egyenlet értelmezése és megoldása függ az illető alaphalmaztól, melyben értelmezve van. Például a $$6x=2$$ egyenletnek egészen más a jelentése és a megoldása, ha

az egész számokon a valós számokon a $$\mathbb {Z}_{10}$$ maradékosztály felett értelmezzük. Ugyanis az első esetben nincs megoldás, a második esetben egy megoldás van, $$x=\frac {1}{3}$$, a harmadik esetben két megoldás van: $$x_{1}=2$$ és $$x_{2}=7$$. Egy egyenletnek tehát csak adott struktúrán belül van jelentése.

## A megoldás vagy gyök fogalma

Az egyenlet megoldásán az ismeretlen(ek) mindazon értékeinek meghatározását értjük, amelyeket behelyettesítve az egyenletbe, annak két oldala egyenlővé válik. Ezeket az értékeket az egyenlet megoldásainak vagy gyökeinek nevezik. Például a fenti $$3|x|+1 = 2$$ valós együtthatós egyenletnek két megoldása van, $\frac{1}{3}$ és $-\frac{1}{3}$. Mindazonáltal nem minden egyenlet tartalmaz ismeretlent. Például a $$2(x+1)=2x+2$$ egyenletet a szokásos módszerek szerint: a zárójel felbontásával és a mérlegelv alkalmazásával megoldva,

$${\begin{aligned}2x+2&=2x+2&/-2\\2x&=2x&/-2x\\0&=0\\\end{aligned}}$$

egyenlethez juthatunk. Ez utóbbi felfogható akár „nullismeretlenes” egyenletnek is (noha a szakirodalom nem szokta alkalmazni ezt a kifejezést). Az is látható, hogy az ekvivalens átalakítások akár csökkenthetik is ismeretlenek számát. Az egyenlet megoldása és gyöke között különbség tehető, mint a következőkben le van írva: Az $$x^{2}-6x+9=0$$ egyenletnek egy megoldása van, a $3$, de két gyöke, amit a másodfokú egyenlet megoldóképlete ad: 

$$x_{1}={\frac {-b+{\sqrt {b^{2}-4ac}}}{2a}}$$ és $$x_{2}={\frac {-b-{\sqrt {b^{2}-4ac}}}{2a}}$$ gyanánt. A két gyök azonos (egybeesik), mert a diszkrimináns zéró. Az egyenlet megoldáshalmaza az a halmaz, amelynek elemei az egyenlet megoldásai. Az egyenlet megoldásai az egyenlet azon gyökei, amelyek elemei az egyenlet értelmezési tartományának. Két egyenlet ekvivalens, azaz egyenértékű, ha egyenlő a megoldáshalmaza és az értelmezési tartománya. Az egyenletek megoldása során lehetőleg ekvivalens átalakításokat kell használni, de erre nincs mindig lehetőség. Lehet, hogy törtes egyenletet fel kell szorozni a nevezők legkisebb közös többszörösével, vagy négyzetre kell emelni. Kikötések segítségével a hamis gyökök kizárhatók, vagy ellenőrzéssel felismerhetők. Ami valamelyik kifejezésbe nem helyettesíthető be, az nem lehet megoldás még akkor sem, ha egyik oldalba sem helyettesíthető be. Célszerű azonban a lehetséges számítási hibák miatt minden egyenletmegoldást ellenőrizni, azaz visszahelyettesíteni az eredeti egyenletbe. Ügyelni kell arra, hogy ne veszítsünk gyököt, mivel azt utólag nem lehet megtalálni. Ezt szükség esetén esetszétválasztással kell megelőzni.

## Egyenletek osztályzása

### Az ismeretlenek száma szerint

Az ismeretlenek száma szerint beszélünk egyismeretlenes, kétismeretlenes, illetve többismeretlenes egyenletről.

### Az alaphalmaz szerint

Azzal a megállapítással összhangban, miszerint egy egyenletnek csak adott struktúrán belül van értelme, az egyenleteknek sokszor alaphalmazt adunk meg, melyben a megoldásokat keressük. Ez számtalanféleképp lehetséges, de a gyakorlatban elkülöníthető néhány fontos alaptípus és elnevezés:

diofantoszi egyenletek: egész együtthatós egyenletek, melyek megoldásai egész számok; komplex (változós vagy együtthatós) egyenletek: együtthatóik és megoldásaik komplex számok; függvényegyenletek: függvényváltozókat tartalmaznak, vagyis megoldásaik - általában valós-valós - függvények. Speciális esetük a differenciál- és az integrálegyenletek. Nevezetes függvényegyenlet (a parciális differenciálegyenletek közé tartozó) pl. a Schrödinger-egyenlet; mátrixegyenletek: az együtthatók és a megoldások mátrixok; differenciaegyenletek, melyek megoldásai sorozatok. Például $$x_{n}-x_{n-1}-x_{n-2}=0$$ egy másodrendű, lineáris differenciaegyenlet, melynek (egyik) megoldása a Fibonacci-sorozat. A differenciálegyenletekben az ismeretlen egy függvény, és az egyenlet a függvény és valahányadik deriváltja között állapít meg összefüggést. A legmagasabb derivált adja meg az egyenlet rendjét. A természettudományos modellezés gyakran eredményez differenciálegyenleteket. A közönséges differenciálegyenletekben a függvényt egy változó szerint deriválják. Például $$f'(x)+xf(x)=0$$ elsőrendű lineáris differenciálegyenlet. A parciális differenciálegyenletekben a függvényt több változó szerint deriválják. Például $$\frac {\partial f(x,t)}{\partial t}+\frac {\partial f(x,t)}{\partial x}=0$$ elsőrendű parciális differenciálegyenlet. A differenciálegyenletek keverednek is. Az integro-differenciálegyenletekben szerepelnek a függvény deriváltjai és integráljai. Az algebrai differenciálegyenletekben algebrai és differenciálegyenletekre jellemző kifejezések fordulnak elő, mint például az Euler-Lagrange-egyenlet a matematikai ingára:

$${\begin{aligned}{\ddot {x}}_{1}&=2x_{1}\lambda \\{\ddot {x}}_{2}&=2x_{2}\lambda -1\\0&=x_{1}^{2}+x_{2}^{2}-1\end{aligned}}$$

A sztochasztikus differenciálegyenletekben véletlen mennyiségek is szerepelnek. Például a Black-Scholes-egyenlet a pénzügyi matematikában:

$$\mathrm {d}S_{t}=rS_{t}{\mathrm {d}}t+\sigma S_{t}{\mathrm {d}}W_{t}$$

### A megoldhatóság szerint

Ha egy egyenletnek az alaphalmaz minden eleme megoldása, azonosságnak nevezzük, ha viszont egyáltalán nincs megoldása az alaphalazon, ellentmondásnak, vagy megoldhatatlannak. Ha van legalább egy megoldása, megoldhatónak nevezzük. Azonosságokra példák:

$$(a+b)+c=a+(b+c)$$ a valós és a komplex számokon; illetve Abel-csoportokban az additív jelöléssel.

$$(a+b)^{2}=a^{2}+2ab+b^{2}$$, ahol $a,b$ valós számok Euler-azonosság: $$e^{i\varphi }=\cos \left(\varphi \right)+i\sin \left(\varphi \right)$$, ahol $\varphi$ valós. A megoldhatóság függ az alaphalmaztól. Például:

$$x^{2}=2$$ megoldhatatlan a racionális számok körében. A valós számokon megoldható, és megoldásai $\lbrace {\sqrt {2}},-{\sqrt {2}}\rbrace $.

$$x^{2}=-2$$ megoldhatatlan a valós számok körében, de a komplex számokon igen, és megoldásai $\lbrace {\sqrt {2}}i,-{\sqrt {2}}i\rbrace $.

### A műveletekkel való kifejezhetősége szerint

Legyen adott egy matematikai struktúra az A halmaz felett. Az A-ból A-ba képező valamely $f$ függvény vagy kifejezhetőek az adott struktúra nyelvén (azaz csak a struktúrabeli műveleteket, az „alapműveleteket” tartalmazó, algebrai kifejezésekkel), vagy nem. Az előbbi esetben az $f$ függvényt algebrainak nevezzük a struktúra felett, míg az utóbbi esetben transzcendensnek. Ilyen például az abszolútérték-függvény vagy a trigonometrikus függvények a valós számtest felett. Az alsó- és középfokú oktatásban a valós számok körében gyakran előforduló egyenlettípusok:

Algebrai egyenlet: Lineáris v. elsőfokú egyenlet, Másodfokú egyenlet, Harmadfokú egyenlet, Transzcendens egyenlet, Abszolútértékes egyenlet, Exponenciális egyenlet, Trigonometrikus egyenlet stb.

### Lineáris egyenletek

A lineáris egyenletek legfeljebb elsőfokúak, és a $$T\left(x\right)=a$$ alakra hozhatóak, ahol $a$-ban nem szerepel az ismeretlen. Továbbá:

$$T\left(\lambda x+\mu y\right)=\lambda T\left(x\right)+\mu T\left(y\right)$$

valamilyen $\lambda, \mu$ együtthatókkal. Vannak olyan egyenletek is, melyekben szerepelnek például másodfokú, egymást kiejtő tagok is, de amíg egyenletrendezéssel nem ejtik ki ezeket, addig az egyenlet nem számít lineárisnak. Lineáris egyenleteket nemcsak számok, hanem vektorok körében is fel lehet írni, és az egyenletet vektortér fölött megoldani. Ekkor $$T\left(x\right)$$ és $a$ egy vektortér elemei, és a megoldást ebben a vektortérben vagy egy másik vektortérben lehet keresni. Megoldhatók a szuperpozíciós elv alapján: egy inhomogén egyenlet megoldása megkapható, mint a hozzá tartozó homogén egyenlet megoldásának és egy partikuláris megoldásnak összege. Ez a lineáris egyenletrendszerekre is teljesül. A linearitás miatt a homogén egyenletek, egyenletrendszerek mindig megoldhatók; egy megoldásuk a nulla, illetve a nullvektor. Ha egy homogén egyenlet megoldása egyértelmű, akkor egy inhomogén egyenlet megoldása is egyértelmű. Egy hasonló, de mélyebb kijelentés a Fredholm-alternatívák.

### Polinomegyenletek

A polinomegyenletekben polinomok szerepelnek, mindkét oldalon. Ha legalább az egyik foka egynél magasabb, akkor az egyenlet nemlineáris. A következő egyenletek számára léteznek megoldóképletek, illetve megoldhatók gyökjelekkel:

másodfokú egyenlet, az $$ax^{2}+bx+c=0$$ alakra rendezve, illetve a teljes négyzetté való kiegészítés módszerével; harmadfokú egyenlet, az $$ax^{3}+bx^{2}+cx+d=0$$ alakra hozva; negyedfokú egyenlet, az $$ax^{4}+bx^{3}+cx^{2}+dx+e=0$$ alakból kiindulva. Itt inkább az algoritmust használják, a megoldóképlet összetettsége miatt. Ötödfokútól kezdve a polinomegyenletek nem oldhatók meg gyökjelekkel.

### Törtes egyenletek

A törtes egyenletekben az ismeretlen megjelenik legalább egyik oldal nevezőjében, például $$\frac {x+2}{x^{2}+3}=\frac {2}{x+1}$$. A megoldás útja a felszorzás a nevezőkkel, majd továbbszámolás a kapott polinomegyenlettel. Itt arra kell figyelni, hogy ragaszkodni kell az eredeti értelmezési tartományhoz, hiszen megoldásként adódhatnak olyan számok is, amelyek nem helyettesíthetők vissza. Felszorzás előtt kikötéseket kell tenni. Visszahelyettesítéskor ügyelni kell arra, hogy ami valamelyik kifejezésbe nem helyettesíthető be, az nem lehet megoldás még akkor sem, ha egyik oldalba sem helyettesíthető be.

### Gyökös egyenletek

Gyökös egyenletekben legalább egy, az ismeretlennel alkotott kifejezés gyökjel alatt áll. Például $$\sqrt{x}=1-x$$. A gyökös egyenletek tekinthetők speciális hatványegyenleteknek, $$\frac{1}{n}$$ kitevővel. Megoldási módszerük egy gyökös kifejezés elkülönítése, és a megfelelő hatványra (a példában négyzetre) emelése. Ezzel a módszerrel az összes gyök kiküszöbölhető. Ügyelni kell arra, hogy a páros hatványra emelés nem ekvivalens átalakítás, hamis gyököket hozhat be. Ezeket esetszétválasztással, kikötésekkel, de ellenőrzéssel is ki lehet zárni. Például a fenti egyenlet négyzetre emelése a $$x=(1-x)^{2}$$ egyenletet eredményezi, melynek negatív gyöke hamis gyök. Nem lehet az eredeti egyenlet megoldása, mert az egyenlet bal oldala erre az értékre nem értelmezett.

### Exponenciális és logaritmikus egyenletek

Exponenciális egyenletekben az ismeretlen legalább egyszer kitevőben szerepel. Például $$2^{3x+2}=4^{x+1}$$ exponenciális egyenlet. Logaritmikus egyenletekben az ismeretlen egy kifejezésének logaritmusa szerepel. Az exponenciális egyenletek megoldhatók logaritmálással, logaritmusos egyenletek exponenciális vételével. A logaritmikus egyenletekhez kikötéseket kell tenni, mivel csak pozitív számnak van logaritmusa. A hamis gyökök ellenőrzéssel is kizárhatók.

### Trigonometrikus egyenletek

A trigonometrikus egyenletekben az ismeretlen egy szögfüggvény argumentumában szerepel. Például $$\sin(x)=\cos(x)$$. A trigonometrikus függvények ciklikussága miatt a trigonometrikus egyenletek megoldásai is ciklikusan ismétlődnek. Néha a megoldást egy ciklusra korlátozzák, ilyenkor az ismétlődés kizárt. A megoldások ciklikusságát egy egész paraméter bevezetésével fejezik ki:

$$x=\frac{\pi}{4}+\pi k$$, ahol $k\in \mathbb {Z}$. Amennyiben az egyenletben szereplő trigonometrikus függvény nem folytonos, úgy kikötéseket kell tenni. Hasonlósan, ha a folytonos trigonometrikus függvény a nevezőbe kerül. Az ellenőrzés is segít kizárni a hamis gyököket.

### Paraméteres egyenletek

A paraméteres egyenletekben van legalább egy ismeretlen, melynek értékét ismertnek tételezik fel. Erre példák a megoldóképletek. Az $$x^{2}+px+q\;=\;0$$ másodfokú egyenlet megoldóképlete:

$$x_{1,2}\;=\;-{\frac {p}{2}}\pm {\sqrt {{\frac {p^{2}}{4}}-q}}$$. Itt a $p, q$ paraméterek értéke attól az egyenlettől függ, melyre a megoldóképletet alkalmazzuk. Ha $$4q\leq p^{2}$$, akkor a megoldások valósak, különben komplexek.

### Definiáló egyenletek

A definiáló egyenletek új szimbólumokat vezetnek be. Ekkor általában a definiálandó szimbólumot írják balra, majd egy („:=“) jelet írnak, és utána a definiáló kifejezést. A : a definiált szimbólum oldalán áll. Alternatívaként írnak egyenlőségjelet, és rá a def rövidítést, ekkor a definiálandó szimbólumnak a bal oldalon kell állnia. Például, ha $f$ függvény, akkor deriváltja az $$f'(x_{0}):=\lim _{x\to x_{0}}{\frac {f(x)-f(x_{0})}{x-x_{0}}}$$ helyen.

### Alak szerint

A homogén egyenletek alakja $$T(x)=0$$, tehát nincs bennük konstans tag. A $T$ bal oldalt függvénynek tekintve, az egyenlet megoldása a bal oldal nullhelye, illetve gyöke. Ha az egyenlet nem homogén, akkor inhomogén. A lineáris egyenletrendszerek és a lineáris differenciálegyenletek körében a homogén rendszerek fontos szerephez jutnak. A fixpontegyenletek alakja $$T(x)=x$$, és megoldása a bal oldal, mint függvény fixpontja. A sajátérték-problémák alakja $$T(x)=\lambda x$$, ahol a $\lambda$ sajátérték és az $x\neq 0$ sajátvektor is ismeretlen, tehát ez egy többismeretlenes egyenlet. A sajátérték-problémának több alkalmazása is van, használják mátrixok elemzéséhez és felbontásához, továbbá a kvantummechanikában és a szerkezeti mechanikában is.

## Egyenlőségláncok

Az egyenlőségláncokban nem két oldal van összekapcsolva egyenlőségjellel, hanem több kifejezés egyenlőségét követeljük meg. Ahhoz, hogy igazak legyenek, az összes egyenlőségnek teljesülnie kell. Például $$17+3=20/2=10+7=17$$ hamis, viszont $$17+3=40/2=10+10=20$$ igaz. Az értelmezést megkönnyítik az egyenlőség tulajdonságai. Gyakran megtalálhatók becslésekben, egyenlőtlenségekkel együtt. Például $$n\geq 3$$ esetén $$2n^{2}=n^{2}+n^{2}\geq n^{2}+3n>n^{2}+2n+1=(n+1)^{2}$$.

## Egyenletrendszerek

Ha több egyenlőség egyidejű teljesülését kívánjuk meg, akkor egyenletrendszerről beszélünk. Többnyire több ismeretlent tartalmaznak.

### Lineáris egyenletrendszerek

Egy egyenletrendszer lineáris, ha minden eleme lineáris. Például az $${\begin{aligned} x+y+z&=5\\ 2x-z&=13 \end{aligned}}$$ egyenletrendszer lineáris, az $x,y,z$ ismeretlenekkel. Ha az együtthatókat mátrixként, a konstans tagokat vektorként fogjuk fel, akkor egyetlen egyenletet látunk, melynek megoldása vektor. A lineáris algebra ezt a felfogást támogatja. Így az egyenlet az $$\mathbf {A} \cdot \mathbf {x} =\mathbf {b}$$ alakot ölti, ahol $\mathbf {A}$ az együtthatók mátrixa, $\mathbf {b}$ a konstans tzagok vektora, és $\mathbf {x}$ az ismeretlen vektor. A szorzás a mátrix-vektor szorzás. A fenti egyenletben tehát $$\mathbf {A} ={\begin{pmatrix} 1&1&1\\ 2&0&-1\end{pmatrix}}$$, $$\mathbf {x} ={\begin{pmatrix} x\\ y\\ z\end{pmatrix}}$$ és $$\mathbf {b} ={\begin{pmatrix} 5\\ 13\end{pmatrix}}$$. Az egyenletrendszer szinguláris, ha mátrixa szinguláris. Ezt jelzi, ha két sora, illetve oszlopa arányos. Ekkor az egyenletrendszer degenerált. A degeneráltság az alulhatározottság egyik oka. Egy másik ok, ha kevesebb az egyenlet, mint ahány ismeretlen van. Ekkor vagy nincs megoldás, vagy a megoldások alteret alkotnak. Ha több az egyenlet, mint az ismeretlen, akkor a rendszer általában ellentmondásos, megoldás nincs. Túlhatározottnak nevezik. A nem degenerált eseteket Gauss-eliminációval, illetve LU-felbontással, a degenerált eseteket szinguláris ́érték-dekompozícióval oldják meg. Túlhatározott esetekben a legkisebb négyzetek módszerével keresnek közelítő megoldást. Dupla pontossággal legfeljebb néhány száz egyenletből álló rendszerek oldhatók meg. A numerikusan szinguláris mátrixokat is szingulárisként kezelik, különben hibát kapnak a kerekítési hibák miatt.

## Nemlineáris egyenletrendszerek

Ha van a rendszerben nemlineáris egyenlet, akkor a rendszer nemlineáris. Például : $${\left\{ \begin{array}{rcl} 3x^{2}+2xy&=&1\\ \sin(x)\cdot \ln(y)&=&e^{x} \end{array} \right.}$$ nemlineáris az $x$ és $y$ ismeretlenekkel. Ezek megoldására nincs általános módszer. Előfordul, hogy nem lehet egzakt módszerrel kiszámolni a megoldást, hanem Newton-módszerrel közelítő megoldáshoz lehet jutni. Egy ökölszabály szerint az egyértelmű megoldhatósághoz annyi egyenlet kell, ahány ismeretlen. Ez azonban nem biztos, hogy így van, például, ha magas fokszámú polinomok szerepelnek, akkor sok megoldás lehetséges. Az implicitfüggvény-tétel támogatja az ökölszabályt.

## Megoldási eljárások

A megoldás az a folyamat, amivel meghatározzuk az összes olyan helyettesítést, melyre az egyenlet igaz. Azt is mondjuk, hogy kielégíti, eleget tesz az egyenletnek. Az egyenlet megoldásai alkotják az egyenlet megoldáshalmazát. Az ellentmondások megoldáshalmaza üres. Az egyes egyenletek megoldási módszerei egyenlettípustól függően nagyon különbözhetnek. Nemcsak egy differenciálegyenlet megoldásának menete különbözhet nagyon egy diofantosziétól, de már a legegyszerűbb valós együtthatós egyismeretlenes első- és másodfokú egyenletek megoldása is általában másféle gondolkodási műveleteket igényel. Az egyenletek megoldásával kapcsolatos legfontosabb fogalmak: mérlegelv, megoldóképlet, közelítő megoldás. Mindezek a módszerek analitikus megoldás keresésére alkalmasak. Az ekvivalens átalakítások lényege az, hogy megőrizzék az eredeti egyenlet gyökeit, és új gyökök ne kerüljenek be. Van, hogy az analitikus megoldás nem található meg ekvivalens átalakításokkal, így adódhatnak hamis gyökök. Az ellenőrzés nemcsak a hamis gyökök kizárására, hanem a számolási hibák felismerésére is alkalmas. Az ellenőrzés azt jelenti, hogy a megtalált gyököket visszahelyettesítik az eredeti egyenletbe. Nevezetes, egyenletformában is megfogalmazható, geometriai eredetű problémák, melyeknek nincs megoldása, vagy nem található meg analitikus vagy engedélyezett módszerekkel. Ilyen a körnégyszögesítés (közelítő megoldás lehetséges), kockakettőzés (közelítőleg lehetséges), illetve a Nagy Fermat-tételben szereplő egyenlet (ha van megoldás, akkor az nem fér számítógépbe). Sok más egyenlettel együtt ekkor a numerikus módszerek segíthetnek megoldást találni. Ismert eljárás a Newton-módszer, vagy a közelítő geometriai szerkesztések. A Galjorkin-módszer végtelen dimenziós terekben keres megoldást, ahol a közelítést véges dimenzióban adja meg. Az egyenletek megoldásairól különböző állítások bizonyíthatók be akkor is, ha a megoldást (egyelőre) nem találjuk. Így lehet kérdés a megoldás létezése, egyértelműsége, vagy függése a paraméterektől. Ha ez a függés folytonos, akkor a probléma korrekt. Ez a numerikus megoldás szempontjából is fontos. Ezzel látható be az is, hogy a numerikus megoldás valóban a megfelelő megoldás közelítése.

## Az egyenletfogalom története

Az egyiptomiak és más ókori keleti népek az egyenleteket szöveges feladatok formájában fogalmazták meg. Minthogy ismerték a természetes és a pozitív törtszámokat, az alaphalmaz általában a pozitív racionális számok halmaza volt. A római korban Diophantosz kialakított egy szórövidítésekből álló pre-algebrai nyelvet, melyen „egyenleteket” írhatott fel. Problémái már nem geometriai motivációjúak voltak, mint görög elődei esetében. A negatív számokat ő sem fogadta el megoldásként. Megoldási módszere gyakran a hamis feltevés módszere volt. Általában megelégedett egyetlen megoldás megtalálásával. A hindu Brahmagupta már elfogadta a negatív számokat (a mínuszjel nála a számjel fölé tett pont volt), adósság-vagyon formájában és a számegyenesen is interpretálta őket, és ennek segítségével nagy lépést tett a másodfokú egyenletek felírásában és megoldásában. A betűparaméter fogalmát még nem ismerte, így csak numerikus példákon keresztül tudott foglalkozni velük; a megoldáshoz általában teljes négyzetté kiegészítés segítségével jutott el. Fibonacci idejéig Európában csak szöveges formában tudtak egyenleteket felírni, ám Fibonacci újra bevezette a hinduk által már többé-kevésbé elfogadott negatív számokat, a mintegy két évszázaddal utána következő Regiomontanus pedig - többek között - a gyökmennyiségeket, ami az irracionális számok és kifejezések diadala volt. L. Pacioli és N. Chuguet visszatértek a Diophantosz által már bevezetni kezdett szinkopált algebrai nyelvhez. Olaszországban mindeközben eljutottak a harmadfokú egyenlet megoldásáig, megkezdve a komplex számok fogalmának elterjedését. R. Descartes a koordináta-rendszer és az analitikus geometria elterjesztésével megteremtette a kapcsolatot az alakzatok és az egyenletek között. Az újkor végén óriási áttörést jelentettek E. Galois és N. H. Abel – igaz, negatív jellegű (lehetetlenséget bizonyító) – eredményei a magasabbfokú algebrai egyenletek gyökkifejezésekkel való megoldhatatlanságáról.

![[First_Equation_Ever.png]]
