---
dg-publish: true
---
[[Alapfogalom]]

[[Két egyenes metszéspontjának meghatározása]]

[[Végtelen]] [[Hosszúság|hosszú]], [[Nulla]] [[Szélesség]]ű vonal, amelyet két [[Pont]] határoz meg.
Az egyenes a pont és a sík mellett a geometria egyik alapfogalma. Leírása (és nem definíciója) szerint mindkét irányban végtelen, végtelenül keskeny vonal. Két pont közötti legrövidebb út szakasz. A modern axiomatikus elméletekben az egyenes belső tulajdonságok nélküli objektum; csak a más egyenesekkel, pontokkal és síkokkal való kapcsolata érdekes. Az analitikus geometriában az egyenes ponthalmaz. Pontosabban, az affin geometriában az egyenes egydimenziós altér.

## Az egyenes definiálhatóságáról

Euklidész Kr. e. 300 körül megjelent művében, az Elemekben először a vonalat definiálta:

„A vonal szélesség nélküli hosszúság” és csak ezután következik az egyenes:

„Egyenes vonal az, amelyik a rajta levő pontokhoz viszonyítva egyenlően fekszik.” Ez a megfogalmazás Eukleidész azon törekvéséből fakad, hogy mindent, amivel foglalkozik, pontosan meghatározzon, minden logikai rést lefedjen. Manapság az egyenest az elemi geometria axiomatikus tárgyalásában (például a Hilbert-féle axiómarendszerben) alapfogalomnak tekintjük, azaz nem vezetjük vissza további definícióval más fogalmakra. Másrészt az elemi geometria modelljeiben természetesen meg kell adnunk az egyenesnek megfelelő entitások halmazát, például a koordinátamodellben mint egy háromdimenziós vektortér egydimenziós altereinek eltoltjainak halmazát.

## Tulajdonságai

Habár nincs definiálva, mindenkiben él egy kép az egyenesről, amely szerint az egyenes egy pontokból álló 1 dimenziós objektum, azaz például a tér egy irányában végtelen hosszú, a többiben kiterjedés nélküli. A geometriában az egyenes következő tulajdonságait használjuk ki:

Két pont egyértelműen meghatároz egy egyenest, amiből következik, hogy két különböző egyenesnek nem lehet egynél több közös pontja. Ha egy síknak és egy egyenesnek legalább két közös pontja van, akkor az egyenes illeszkedik az adott síkra. Ha $A$, $B$, $C$ egy egyenes pontjai és $B$ az $A$ és $C$ pontok között fekszik, akkor egyszersmind a $B$ pont a $C$ és $A$ pontok között is fekszik. Ha $A$, $C$ egy egyenes pontjai, akkor létezik olyan $B$ pontja az egyenesnek, amely az $A$ és $C$ pontok között fekszik, és egyszersmind létezik olyan $D$ pontja, hogy a $C$ pont az $A$ és $D$ pontok között is fekszik. Az egyenes tetszőleges három pontja közül pontosan egy olyan pont van, amely a másik két pont között fekszik.

A projektív geometriában él a dualitás tétele (egyes rendszerek szerint axiómája). Ez egy szimmetriaelv, hogy ha egy $n$ dimenziós térben állítunk valamit a $k$ dimenziós és az $n-k-1$ dimenziós alterek illeszkedési tulajdonságairól, akkor az állítás igazságtartalma megmarad, ha a $k$ dimenziós alterek helyett $n-k-1$, az $n-k-1$ dimenziós altereket $k$ dimenziósakra cseréljük, az illeszkedési relációt pedig megtartjuk. Speciálisan, projektív síkokon az egyenesek és pontok duálisak. Így projektív síkokon képzelhető a pont végtelen hosszúnak, és az egyenes minden irányból végtelenül kicsinek. Három dimenziós projektív terekben a pontok és a síkok duálisak egymással, az egyenesek pedig egyenesekkel duálisak.

## Egyenes megadása az analitikus geometriában

Az analitikus geometriában a geometriai tér egy $n$-dimenziós vektortér a valós számok felett. Az egyenes egydimenziós affin altér, azaz egy $n-1$ dimenziós lineáris altér mellékosztálya. Három dimenzióban az analitikus geometria eleget tesz a Hilbert-féle axiómarendszernek; így az analitikus geometria egyenesei megfelelnek a Hilbert-féle axiómarendszereinek.

Egy egyenes egyenlete olyan egyenlet, melyet az egyenes minden pontja teljesít, és ha egy pont teljesíti, akkor rajta van az egyenesen. A síkban az egyenes egyenletének általában háromféle alakját használjuk (Descartes-féle koordináta-rendszerben):

1. Ha adott az egyenes egy pontja $(x_{0};y_{0})$ és egy $(A;B)$ normálvektora: 
   $$Ax + By = Ax_{0} + By_{0}.$$
   
2. Ha az egyenesnek egy pontja $(x_{0};y_{0})$ és a meredeksége (vagy iránytangense) $m$, akkor
   $$y = mx + b,$$ 
   ahol a b konstansra $$b = y_{0} - mx_{0}$$ teljesül.

3. Adva legyen az egyenes $P_{0}(x_{0};y_{0})$ pontja, és az $x$ tengellyek bezárt szöge $\alpha$. Ha az egyenes nem függőleges, akkor egyenlete 
   $$y = y_{0} + \operatorname{tg}(\alpha) \cdot (x - x_{0}).$$ 
   Ha függőleges, akkor egyenlete 
   $$x = x_{0}.$$

Ha adott az egyenes két pontja $P_{1}(x_{1};y_{1})$ és $P_{2}(x_{2};y_{2})$, akkor az egyenes bármely $P(x;y)$ pontja meghatározható az
   $$(x_{2} - x_{1})(y - y_{1}) = (y_{2} - y_{1})(x - x_{1})$$
összefüggés szerint. Legyenek $P$ és $Q$ az egyenes különböző pontjai. Ekkor az egyenes pontjaira teljesül, hogy 
   $$\vec{x} = \vec{OP} + t \cdot \vec{PQ},$$
ahol $$t \in \mathbb{R},$$ így az egyenes egyenlete 
$$g = \{X \mid \vec{OX} = \vec{OP} + t \cdot \vec{PQ}; t \in \mathbb{R} \}.$$

A térben már kevésbé szép, ekkor egyenletrendszerekkel írhatjuk le: Ha adott az egyenes egy pontja $(x_{0};y_{0};z_{0})$ és egy $(A;B;C)$ irányvektora:
   $$\begin{align*}
   x &= x_{0} + tA, \\
   y &= y_{0} + tB, \\
   z &= z_{0} + tC,
   \end{align*}$$
ahol a $t$ valós paraméter. Kicsit átalakítva az előző egyenletrendszert (amennyiben $ABC \neq 0$, azaz az irányvektor egyik koordinátája sem 0, nem párhuzamos egyik koordináta-tengellyel sem):
   $$(t =) \frac{x - x_{0}}{A} = \frac{y - y_{0}}{B} = \frac{z - z_{0}}{C}.$$

Az $n$ dimenziós térben az egyenest egy $n$ változós egyenletrendszer adja meg, amiben van egy független paraméter. Legyen 
$$\mathbf{p} \in \mathbb{R}^{n}$$ helyvektor, 
$$\mathbf{r} \in \mathbb{R}^{n} \setminus \{0\}$$ irányvektor. Ekkor a $\mathbf{p}$ ponton átmenő $\mathbf{r}$ irányú egyenes egyenlete:
$$g = \{\mathbf{p} + \lambda \mathbf{r} \mid \lambda \in \mathbb{R} \}.$$

Legyenek $\mathbf{p}_{1},\mathbf{p}_{2}\in \mathbb{R}^{n}$ helyvektorok úgy, hogy $\mathbf{p}_{1} \neq \mathbf{p}_{2}$. Ekkor egyértelműen létezik egy egyenes, ami mindkettőre illeszkedik, és egyenlete:
$$g = \{ \mathbf{p}_{1} + \lambda (\mathbf{p}_{2} - \mathbf{p}_{1}) \mid \lambda \in \mathbb{R} \} = \{(1 - \lambda) \mathbf{p}_{1} + \lambda \mathbf{p}_{2} \mid \lambda \in \mathbb{R} \}.$$

Két különböző vektor affin burka egyenes:
$$\{ \lambda \vec{v} + \mu \vec{w} \mid \lambda ,\mu \in \mathbb{R} , \lambda + \mu = 1 \},$$
ahol $\vec{v}, \vec{w}$ a vektorok.

## Egyenesek kölcsönös helyzete

Egyenesek kölcsönös helyzete (pirossal és kékkel) a térben:

Párhuzamosság: A két egyenes eltolással átvihető egymásba. A párhuzamosság ekvivalenciareláció. Egybeesés: A két egyenes összes pontja ugyanaz, azaz ponthalmazként megegyeznek. Nullvektorral való eltolással vihetők egymásba. Valódi párhuzamosság: A két egyenes nem esik egybe, de irányuk megegyezik. Nullvektortól különböző vektorral való eltolással átvihetők egymásba. Metszők: Az egyeneseknek egy közös pontja van. Kitérők: Az egyeneseknek nincs közös pontjuk, és nem vihetők eltolással egymásba. Csak legalább háromdimenziós térben lehetséges.

## Metszéspont a síkban

A síkban két, $a_{1}x + b_{1}y = c_{1},\ a_{2}x + b_{2}y = c_{2}$ egyenlettel adott, metsző egyenes metszéspontjának számításához a Cramer-szabály nyújt segítséget:
$$x_{s} = \frac{c_{1}b_{2} - c_{2}b_{1}}{a_{1}b_{2} - a_{2}b_{1}}, \quad y_{s} = \frac{a_{1}c_{2} - a_{2}c_{1}}{a_{1}b_{2} - a_{2}b_{1}}.$$

Ha $a_{1}b_{2} - a_{2}b_{1} = 0$, akkor az egyenesek párhuzamosak. Ha az egyenesek két-két pontjukkal adottak, azaz az első egyenes a $P_{1} = \begin{pmatrix}x_{1} \\y_{1}\end{pmatrix}$ és $P_{2} = \begin{pmatrix}x_{2} \\y_{2}\end{pmatrix}$ pontokkal, a második pedig a $P_{3} = \begin{pmatrix}x_{3} \\y_{3}\end{pmatrix}$ és $P_{4} = \begin{pmatrix}x_{4} \\y_{4}\end{pmatrix}$ pontokkal, akkor ki kell számítani az egyenesek egyenleteit. Így az $S = \begin{pmatrix}x_{s} \\y_{s}\end{pmatrix}$ metszéspontra adódik, hogy 
$$x_{s} = \frac{(x_{2} - x_{1})(x_{3}y_{4} - y_{3}x_{4}) - (x_{4} - x_{3})(x_{1}y_{2} - y_{1}x_{2})}{(x_{2} - x_{1})(y_{4} - y_{3}) - (y_{2} - y_{1})(x_{4} - x_{3})}$$
és 
$$y_{s} = \frac{(y_{2} - y_{1})(x_{3}y_{4} - y_{3}x_{4}) - (y_{4} - y_{3})(x_{1}y_{2} - y_{1}x_{2})}{(x_{2} - x_{1})(y_{4} - y_{3}) - (y_{2} - y_{1})(x_{4} - x_{3})}.$$

Szemben az egyenesekkel, a síkban a nem párhuzamos szakaszok nem feltétlenül metszik egymást. Legyen a két szakasz $(x_{1},y_{1}),(x_{2},y_{2})$ és $(x_{3},y_{3}),(x_{4},y_{4})$. Ekkor a szakaszok paraméteres egyenlettel írhatók le:
$$(x(s),y(s)) = (x_{1} + s(x_{2} - x_{1}),y_{1} + s(y_{2} - y_{1})),$$
$$(x(t),y(t)) = (x_{3} + t(x_{4} - x_{3}),y_{3} + t(y_{4} - y_{3})).$$
ahol $0 \leq s,t \leq 1$. Ha létezik az $(x_{0},y_{0})$ metszéspont, akkor vannak olyan $s_{0},t_{0}$ paraméterek, hogy 
$$s(x_{2} - x_{1}) - t(x_{4} - x_{3}) = x_{3} - x_{1},$$ 
$$s(y_{2} - y_{1}) - t(y_{4} - y_{3}) = y_{3} - y_{1}.$$

Ahogy a fenti esetben, úgy most is a Cramer-szabály segít nekünk. Ezután még azt is vizsgálnunk kell, hogy $0 \leq s_{0} \leq 1,\ 0 \leq t_{0} \leq 1$. Ha ez teljesül, akkor a paraméterek behelyettesítésével megkapjuk a szakaszok metszéspontjának koordinátáit. Legyenek például a szakaszok $(1,1),(3,2)$ és $(1,4),(2,-1)$. Ekkor az egyenletrendszer 
$$2s - t = 0$$ 
$$s + 5t = 3$$
így 
$$s_{0} = \frac{3}{11}, t_{0} = \frac{6}{11},$$ 
és a szakaszok metszik egymást. A metszéspont koordinátái 
$$\left(\frac{17}{11},\frac{14}{11}\right).$$

Két ponttal adott egyenesek metszéspontja is számítható ugyanígy, ám ekkor nem kell vizsgálni, hogy $0 \leq s_{0} \leq 1,\ 0 \leq t_{0} \leq 1$.

## Egyenesek szöge a síkban

Ha egy egyenes egyenlete 
$$ax + by = c$$ 
formában adott, akkor irányszögére, $\alpha$-ra teljesül, hogy:
$$\operatorname{tg} \alpha = \frac{a}{b},$$
ami következik a tangens definíciójából. Alkalmazva a tangens inverz függvényét, az árkusz tangenst:
$$\alpha = \operatorname{arctg}\frac{a}{b}.$$

Ha ezek az egyenletek nincsenek definiálva, akkor $b = 0$, az egyenes függőleges. A tangensfüggvénynek pólusa van a $\alpha = 90^\circ$ és az $\alpha = -90^\circ$ helyen. 

Legyenek $g_{1}$ és $g_{2}$ egyenesek a síkban, és legyenek adva az 
$$g_{1} = \{\mathbf{p_{1}} + \lambda \mathbf{r_{1}} \mid \lambda \in \mathbb{R} \}$$ 
és 
$$g_{2} = \{\mathbf{p_{2}} + \lambda \mathbf{r_{2}} \mid \lambda \in \mathbb{R} \}$$ 
egyenletekkel adva úgy, hogy $\mathbf{p_{1}}$ és $\mathbf{p_{2}}$ helyvektorok, és $\mathbf{r_{1}}$ és $\mathbf{r_{2}}$ lineárisan független irányvektorok! Ekkor a két egyenes által bezárt $\theta$ szögre teljesül, hogy:
$$\theta = \operatorname{arccos}\frac{\mathbf{r_{1}} \cdot \mathbf{r_{2}}}{|\mathbf{r_{1}}||\mathbf{r_{2}}|}.$$

Az egyenesek merőlegesek, más szóval, ortogonálisak akkor, ha derékszöget zárnak be, azaz 
$$\theta = 90^\circ.$$ 
Ez pontosan akkor teljesül, ha az irányvektorok skaláris szorzata nulla, azaz 
$$\mathbf{r_{1}} \cdot \mathbf{r_{2}} = 0.$$

Ha az egyenesek egyenlete 
$$a_{1}x + b_{1}y = c_{1}$$ 
és 
$$a_{2}x + b_{2}y = c_{2}$$ 
alakban adott, akkor az általuk közrezárt szög, $\theta$ irányszögeik különbsége:
$$\theta = \alpha_{1} - \alpha_{2}.$$

A tangensfüggvény addíciós tételeivel:
$$\operatorname{tg}\theta = \operatorname{tg}(\alpha_{1} - \alpha_{2}) = \frac{\operatorname{tg} \alpha_{1} - \operatorname{tg} \alpha_{2}}{1 + \operatorname{tg} \alpha_{1} \operatorname{tg} \alpha_{2}}.$$

Mivel 
$$\operatorname{tg} \alpha_{1} = \frac{a_{1}}{b_{1}}$$ 
és 
$$\operatorname{tg} \alpha_{2} = \frac{a_{2}}{b_{2}},$$ 
következik, hogy:
$$\frac{\operatorname{tg} \alpha_{1} - \operatorname{tg} \alpha_{2}}{1 + \operatorname{tg} \alpha_{1} \operatorname{tg} \alpha_{2}} = \frac{\frac{a_{1}}{b_{1}} - \frac{a_{2}}{b_{2}}}{1 + \frac{a_{1}a_{2}}{b_{1}b_{2}}} = \frac{a_{1}b_{2} - a_{2}b_{1}}{a_{1}a_{2} + b_{1}b_{2}}}.$$

Végeredményben
$$\operatorname{tg} \theta = \frac{a_{1}b_{2} - a_{2}b_{1}}{a_{1}a_{2} + b_{1}b_{2}}.$$

Alkalmazva a tangens inverz függvényét kapjuk, hogy:
$$\theta = \operatorname{arctg} \frac{a_{1}b_{2} - a_{2}b_{1}}{a_{1}a_{2} + b_{1}b_{2}}.$$

Az egyenesek pontosan akkor merőlegesek, ha a nevező nulla, azaz 
$$a_{1}a_{2} + b_{1}b_{2} = 0.$$ 
Ekkor a fenti egyenletek nincsenek értelmezve, mivel a tangensfüggvénynek pólusa van a $\alpha = 90^\circ$ és az $\alpha = -90^\circ$ helyen.

## Távolságok a síkban

Adva legyen a $(x_{0},y_{0})$ pont, és az $ax + by + c = 0$ egyenletű egyenes. Távolságuk:
$$\frac{|ax_{0} + by_{0} + c|}{\sqrt{a^{2} + b^{2}}}.$$

Az egyenes $(x_{0},y_{0})$ ponthoz legközelebbi pontjának koordinátái:
$$\left(x = \frac{b(bx_{0} - ay_{0}) - ac}{a^{2} + b^{2}}, y = \frac{a(-bx_{0} + ay_{0}) - bc}{a^{2} + b^{2}}\right).$$

Ha az egyenes két pontjával van adva, akkor $ax + by + c = 0$ alakú egyenletének együtthatói:
$$a = y_{2} - y_{1}, \quad b = x_{1} - x_{2}, \quad c = x_{2}y_{1} - x_{1}y_{2}$$
és ezek az együtthatók helyettesíthetők be a képletekbe.

## Távolságok a térben

A $$\vec{p_{0}} = (x_{0},y_{0},z_{0})$$ pont és az $$\vec{p_{1}} = (x_{1},y_{1},z_{1}),$$  illetve $$\vec{p_{2}} = (x_{2},y_{2},z_{2})$$ pontokon átmenő egyenes távolsága:
$$\frac{\left|(\vec{p_{2}} - \vec{p_{1}}) \times (\vec{p_{1}} - \vec{p_{0}})\right|}{\left| \vec{p_{2}} - \vec{p_{1}} \right|} = \frac{\left|(\vec{p_{0}} - \vec{p_{1}}) \times (\vec{p_{0}} - \vec{p_{2}})\right|}{\left| \vec{p_{2}} - \vec{p_{1}} \right|}.$$

Ha az egyik egyenes a $$\vec{p_{1}} = (x_{1},y_{1},z_{1})$$ és $$\vec{p_{2}} = (x_{2},y_{2},z_{2})$$ pontokon, a másik a $$\vec{p_{3}} = (x_{3},y_{3},z_{3})$$ és $$\vec{p_{4}} = (x_{4},y_{4},z_{4})$$ pontokon halad át, akkor távolságuk:
$$\frac{\left|(\vec{p_{3}} - \vec{p_{1}}) \cdot ((\vec{p_{2}} - \vec{p_{1}}) \times (\vec{p_{4}} - \vec{p_{3}}))\right|}{\left|(\vec{p_{2}} - \vec{p_{1}}) \times (\vec{p_{4}} - \vec{p_{3}})\right|}.$$


## Hivatkozások

David Hilbert: Grundlagen der Geometrie, B.G. Taubner, Leizig, 2. kiadás, 1903 Hajós György: Bevezetés a geometriába, Nemzeti Tankönyvkiadó, Budapest, 10. kiadás, 1994, ISBN 963-18-5622-4 Strommer Gyula: Geometria, Nemzeti Tankönyvkiadó, Budapest, 2. kiadás, 1993, ISBN 963-18-5312-8

## Források

Line szócikk a MathWorld lapján Euklidész: Elemek görögül és angolul Euklidész: Elemek 1. könyv magyarul

## Jegyzetek

## Fordítás

Ez a szócikk részben vagy egészben a Gerade című német Wikipédia-szócikk fordításán alapul. Az eredeti cikk szerkesztőit annak laptörténete sorolja fel. Ez a jelzés csupán a megfogalmazás eredetét és a szerzői jogokat jelzi, nem szolgál a cikkben szereplő információk forrásmegjelöléseként.
![[Is-linesegm.svg]]
![[Lines_crossing.svg]]
![[Lines_parallel.svg]]
![[Lines_skew.svg]]
