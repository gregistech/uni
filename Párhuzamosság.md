---
dg-publish: true
---
Az euklideszi geometriában két [[egyenes]] párhuzamos, ha egysíkúak, és nem metszik egymást. Emellett az egyeneseket párhuzamosnak tekintik önmagukkal, hogy a párhuzamosság ekvivalenciareláció legyen. A hiperbolikus geometriában irányított egyenesek párhuzamosságáról beszélnek. Azok az irányított egyenesek párhuzamosak, amelyek elválasztják a metsző és a nem metsző irányított egyeneseket. A szóhasználat nem egységes. Ezeket az egyeneseket hívják elpattanónak, vagy az összes nem metszőt párhuzamosnak. Gyakran mondják, hogy „a párhuzamosok a végtelenben metszik egymást”. Ez affin szemléletre utal, azaz arra, hogy minden egyenest egy-egy végtelen távoli ponttal bővítettünk, és hogy az egy párhuzamos nyalábba tartozó egyenesek végtelen távoli pontja közös. Ha nem teszünk különbséget végtelen távoli és közönséges pontok között, akkor a projektív geometriához jutunk, ahol már nincsenek párhuzamosok. A háromdimenziós euklideszi térben teljesülnek a következők:

Két egyenes kitérő, ha nincsenek egy síkban.  
Egyenes és sík párhuzamos, ha nem metszik egymást, vagy a sík tartalmazza az egyenest.  
Két sík párhuzamos, ha nem metszik egymást, vagy egybeesnek.  
Magasabb dimenziós terekben más alterek párhuzamossága is értelmezve van.  
A hiperbolikus, az affin és a projektív geometriában is hasonlók teljesülnek. Vektorterekben két egyenes párhuzamos, ha irányvektoraik lineárisan összefüggnek, ahol is az egyenesek értelmezhetők az egydimenziós alterek mellékosztályaiként.

## Jelölése

A párhuzamosság jele $\parallel$. Például $AB \parallel CD$ azt jelenti, hogy az AB egyenes párhuzamos a CD egyenessel. A Unicode karakterkészletben a 'párhuzamos' és a 'nem párhuzamos' jelek kódja rendre U+2225 (∥) és U+2226 (∦).

## Tulajdonságai

Az euklideszi és az affin síkgeometriában teljesül:  
Adott egyeneshez adott ponton át egy, az adott egyenest (közönséges pontban) nem metsző egyenes húzható. Ez a kijelentés az euklideszi geometria párhuzamossági axiómája, ami szükséges az euklideszi geometria felépítéséhez. Elhagyásával az abszolút geometriát kapjuk, ami az euklideszi és a hiperbolikus geometria közös általánosítása. A hiperbolikus geometriában a hiperbolikus axióma helyettesíti:  
Adott egyeneshez adott ponton át több, az adott egyenest nem metsző egyenes húzható.  

Mindkét irányhoz tartozik egy-egy párhuzamos. Szögük a párhuzamossági szög kétszerese, ami csak a pont-egyenes távolságtól és a görbülettől függ. Az euklideszi síkban ez a szög mindig derékszög, ami azt jelenti, hogy a két párhuzamos egybeesik. Rögzített hiperbolikus síkban minél messzebb van a pont az egyenestől, annál közelebb kerül a távolsági szög a derékszöghöz. A hiperbolikus geometria távolságvonalai hiperciklusok. Az analitikus geometriában az euklideszi párhuzamossági axióma bizonyítható. Tehát ez a geometria az euklideszi geometriát modellezi. Tetszőleges dimenziós euklideszi, affin és hiperbolikus terekben az egyenesek párhuzamossága ekvivalenciareláció. Ennek osztályai a párhuzamos nyalábok, amelyek speciális sugársorok. Tetszőleges dimenziójú euklideszi geometriában bármely párhuzamos egyenespár távolsága állandó, azaz akárhol metsszük el őket egy rájuk merőleges egyenessel, a párhuzamos egyenespár mindig ugyanolyan hosszú szakaszt metsz ki belőle. A hiperbolikus geometriákban ez csak akkor igaz, ha a két egyenes egybeesik. Az euklideszi síkgeometriában két egyenes akkor és csak akkor párhuzamos, ha az egyik minden pontja azonos távolságra van a másik egyenestől. Egy másik ekvivalens tulajdonság, hogy nem metszik egymást. Egy harmadik ekvivalens tulajdonság szerint, ha egy mindkettőt metsző egyenessel metsszük őket, akkor mindkettő mellett ugyanakkora szögek keletkeznek. Mindezek az ekvivalens tulajdonságok különböző szerkesztési módszerekhez vezetnek. A gömbi geometriában nincsenek párhuzamos egyenesek, mert minden főkör metszi egymást. A távolságvonalak körök. Az euklideszi térbe ágyazva ezek a körök az adott főkört kimetsző síkkal párhuzamos síkkal metszhetők ki.

### Párhuzamosok távolsága

Legyen a két nem függőleges párhuzamos egyenlete  
\[
y=mx+b_{1}
\]  
\[
y=mx+b_{2},
\]  
ekkor a pontok koordinátái ennek az egyenletrendszernek a megoldásával nyerhetők:  
\[
egin{cases}
y=mx+b_{1}\
y=-rac{x}{m}
nd{cases}
\]  
és  
\[
egin{cases}
y=mx+b_{2}\
y=-rac{x}{m}
nd{cases}
\]  

A rendszer megoldásaként a 
\[
\left(x_{1},y_{1}
ight) = \left(rac{-b_{1}m}{m^{2}+1},rac{b_{1}}{m^{2}+1}
ight)
\]
és a 
\[
\left(x_{2},y_{2}
ight) = \left(rac{-b_{2}m}{m^{2}+1},rac{b_{2}}{m^{2}+1}
ight)
\]
pontok adódnak. Távolságuk:  
\[
d=\sqrt{\left(rac{b_{1}m-b_{2}m}{m^{2}+1}
ight)^{2}+\left(rac{b_{2}-b_{1}}{m^{2}+1}
ight)^{2}}\,,
\]  
egyszerűbb alakban  
\[
d=rac{|b_{2}-b_{1}|}{\sqrt{m^{2}+1}}\,.
\]  

Ha az egyenesek egyenlete  
\[
ax+by+c_{1}=0
\]  
\[
ax+by+c_{2}=0,
\]  
akkor távolságuk  
\[
d=rac{|c_{2}-c_{1}|}{\sqrt{a^{2}+b^{2}}}.
\]  

## Általánosítása vektorterekben

Az $n$-dimenziós $K$ test fölötti $A$ vektortér alterei, $A_{1},A_{2}$ az $U_{1},U_{2} < K^{n}$ lineáris alterek mellékosztályaiként írhatók le az $A$-hoz tartozó koordináta-vektortérben. Ekkor 
\[
A_{1}=P_{1}+U_{1}
\]  
és  
\[
A_{2}=P_{2}+U_{2}
\]  
valami $P_{1},P_{2}$-re.  

Az $A_{1}$ és $A_{2}$ terek párhuzamosak, ha  
\[
U_{1} \subseteq U_{2}
\]  
vagy  
\[
U_{2} \subseteq U_{1}.
\]  

Ugyanez átfogalmazható csak geometriai fogalmakkal:  

Az $A_{1}$ és a $A_{2}$ terek párhuzamosak, ha az $A$ affin térben van egy $	au$ párhuzamos eltolás, hogy  
\[
	au (A_{1})\subseteq A_{2}
\]  
vagy  
\[
A_{2} \subseteq 	au (A_{1}).
\]  

Vektoriálisan, $	au$ eltolásvektora  
\[
ec{v} \in K^{n}  
\]  
(lehet például  
\[
ec{v}={\overrightarrow{P_{1}P_{2}}}
\]  
az előző megfogalmazás szerint) és akkor az állítás:  
Az $A_{1}$ és az $A_{2}$ terek párhuzamosak, ha van egy  
\[
ec{v} \in K^{n}
\]  
eltolás, hogy  
\[
A_{1} + ec{v} \subseteq A_{2} 
\]  
vagy  
\[
A_{2} \subseteq A_{1} + ec{v}. 
\]  

Ezeket a definíciókat rendszerint legalább egydimenziós alterekre alkalmazzák, hiszen eszerint a pontok és az üres halmaz mindennel párhuzamos lenne.

### Tulajdonságai

Az így általánosított párhuzamosság a vektortér rögzített dimenziójú eltolt alterein ekvivalenciareláció. Ezek az osztályok a párhuzamos nyalábok, vagy párhuzamos altérsorok. Ha a rögzített dimenzió 1, akkor párhuzamos egyenesnyalábról, ha 2, akkor párhuzamos síksorról, ha $n-1$, akkor párhuzamos hipersíksorról van szó. Az affin geometria nyelvén azok a $k$ dimenziós affin alterek párhuzamosak, amelyek a végtelen távoli hipersíkon $(k-1)$-dimenziós altérben metszik egymást. Az összes affin altér halmazán a párhuzamosság szimmetrikus és reflexív, de nem tranzitív reláció.

## Rokon fogalmak

A párhuzamos eltolás minden pontot egy adott távolsággal tol el egy adott irányban. Vektoriálisan,  
\[
x \mapsto x + a.
\]  
Így futhatnak párhuzamosan félegyenesek és szakaszok is. Hasonlóan eltolhatók görbék is a normálisuk irányában. A $\gamma (s) \in \mathbb{R}^{2}$ görbének párhuzamos görbéi a $\gamma (s) \pm an(s)$ görbék, ahol $n(s)$ normálvektora $\gamma (s)$-nek. Erre példák a koncentrikus körök. Zárt test párhuzamos teste az a test, amit úgy kapunk, hogy a testhez hozzávesszük a legfeljebb egy adott távolságra levő pontokat. Vektoriálisan,  
\[
K + B_{r} = \{x + y \mid x \in K, y \in B_{r}\}
\]  
, ahol  
\[
B_{r} = \{y \mid \|y\| \leq r\}
\]  
az $r$ sugarú, origó középpontú gömböt jelöli.

## Kapcsolódó szócikkek

Párhuzamossági axióma  
Homotécia  
Párhuzamos szelők tétele

## Források

Obádovics J. Gyula: Matematika  
Euklidesz: Elemek (Mayer Gyula ford.), Gondolat, 1983. [1]  
Fried Ervin: Algebra I., Elemi és lineáris algebra, Nemzeti Tankönyvkiadó, Bp., 2000.  
H. S. M. Coxeter: Projektív geometria  
Reiman István: Geometria és határterületei  
http://www.bethlen.hu/matek/mathist/forras/Egyenesek_parhuzamos_meroleges.htm Archiválva 2015. február 28-i dátummal a Wayback Machine-ben  
https://web.archive.org/web/20100214200004/http://matek.ymmf.hu/gyakorlofeladatok/Geometriai_alapismeretek.pdf  
http://www.comgim.sk/wp-content/uploads/2010/01/28-Térgeometriai-alapfogalmak-térelemek-kölcsönös-helyzete2.doc  
