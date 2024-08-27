---
dg-publish: true
---
A gömb egy geometriai alakzat, mely jelenthet egy felületet (pontosabb megnevezése gömbhéj, esetleg üres gömb) és egy (tömör) testet egyaránt. A (héj)felület esetén egy adott ponttól a térben egyenlő távolságra lévő pontok, míg test esetén a legfeljebb az adott távolságra lévő pontok halmazát értjük rajta. A gömböt tekinthetjük a kör általánosításának is.

## Definíció

Gömbnek nevezzük a térben azon pontok halmazát, melyek egy adott $P$ ponttól legfeljebb egy rögzített $r$ távolságra vannak. Ekkor $P$-t a gömb középpontjának, $r$ értékét pedig a gömb sugarának nevezzük. A $P$ ponttól pontosan $r$ távolságra lévő pontokat együttesen a gömb felületének, vagy felszínének nevezzük. Ha $r = 1$, akkor egységgömbről beszélünk.

### Egyenletek

Az analitikus geometriában, az $(x_0, y_0, z_0)$ középpontú és $r$ sugarú gömböt azok az $(x, y, z)$ pontok alkotják, melyekre fennáll az alábbi egyenlőtlenség:

$$
(x - x_{0})^{2} + (y - y_{0})^{2} + (z - z_{0})^{2} \leq r^{2}.
$$

Az egyenlőség a felületi pontokban teljesül:

$$
(x - x_{0})^{2} + (y - y_{0})^{2} + (z - z_{0})^{2} = r^{2}.
$$

A belső pontokban szigorú egyenlőtlenség áll fenn:

$$
(x - x_{0})^{2} + (y - y_{0})^{2} + (z - z_{0})^{2} < r^{2}.
$$

Az $r$ sugarú gömb felületi pontjai paraméterezhetőek a gömbi koordináták segítségével is:

$$
x = x_{0} + r \sin \theta \cos \phi,
$$

$$
y = y_{0} + r \sin \theta \sin \phi \quad (0 \leq \theta \leq \pi, -\pi < \phi \leq \pi),
$$

$$
z = z_{0} + r \cos \theta.
$$

Az origó középpontú, tetszőleges sugarú gömbfelület a következő differenciálegyenlettel írható le:

$$
x\,dx + y\,dy + z\,dz = 0.
$$

Az egyenlet jól visszatükrözi a tényt, hogy a gömbfelületen mozgó pont helyvektora és sebességvektora mindig merőleges egymásra.

### Vektortérben

Legyen $V$ egy (nem feltétlenül véges dimenziós) vektortér valamely $\|.\|$ normával. Ekkor a $v \in V$ középpontú $r$ sugarú gömbfelület megfogalmazható a következőképpen:

$$
G := \{u \in V : \|u - v\| = r\}.
$$

Észrevehető, hogy háromdimenziós esetben a klasszikus gömbfelülethez, kétdimenzióban a körhöz jutunk az euklideszi normával. A gömb belső pontjainak halmaza, más szóval a $v \in V$ pont $r$ sugarú környezete, szintén a háromdimenziós eset általánosításaként adható meg.

$$
K_{r}(v) := \{u \in V : \|u - v\| < r\}.
$$

### Metrikus térben

Legyen $(X,\rho)$ metrikus tér. Ekkor a $x \in X$ középpontú $r$ sugarú gömbfelület megfogalmazható a következőképpen:

$$
G_{r}(x) := \{y \in X : \rho(x, y) = r\}.
$$

A gömb belső pontjai pedig egyenlőtlenség segítségével:

$$
K_{r}(x) := \{y \in X : \rho(x, y) < r\}.
$$

Utóbbit nevezik nílt gömbnek is, a $G_{r}(x) \cap K_{r}(x)$ halmazt pedig zárt gömbnek. Ezeknek lényeges analízisbeli alkalmazásaik vannak.

### Forgástestként

A gömb úgy is definiálható, hogy az a test, ami egy kört átmérője körül megforgatva keletkezik. Ha a kört ellipszissel helyettesítjük, akkor az eredmény forgásellipszoid lesz.

## Terminológia

Egy egyenes, ami metszi a gömböt, legfeljebb két pontban metszi. Ha a gömb egy pontpárján átmenő egyenes tartalmazza a gömb középpontját, akkor a pontpár egyik eleme a másik átellenes vagy antipodális pontja. Egy kör a gömb főköre, ha teljes egészében rajta van a gömbön, és középpontja megegyezik a gömb középpontjával. Bár a Föld nem pontosan gömb, vagy forgásellipszoid alakú, gömbök esetén gyakran alkalmazzuk a Földre és más csillagászati testekre megszokott terminológiát. Ha egy gömbi pontot Északi-sarknak nevezünk, akkor átellenes pontja a Déli-sark, az egyenlítő pedig a pontpár két tagjától egyenlő távolságra húzódó főkör. A két sarkot összekötő körök a hosszúsági körök, vagy meridiánok. Az egyenlítővel párhuzamos körök a szélességi körök.

## Felszín és térfogat

A gömb felszíne:

$$
A = 4\pi r^{2},
$$

[[Gömb térfogata]]

Ezeket többféleképpen, integrálszámítással, közelítő poliéderekkel vagy a Cavalieri-elv segítségével lehet belátni. A gömbnek van a legkisebb felülete az adott térfogatú testek közül. Másként fogalmazva, rögzített felület esetén a gömb rendelkezik a testek közül a legnagyobb térfogattal (izoperimetrikus egyenlőtlenség). Ennek folyománya, hogy a szabad folyadékfelszínek a gömbhöz minél inkább közeli alakzatokat igyekszenek felvenni. Egy adott gömb körülírt hengerének térfogata éppen másfélszerese a gömb térfogatának, és a felszíne is másfélszerese a gömb felszínének. Ezt már Arkhimédész is tudta. Ennek belátásához írjuk fel a henger térfogatát és felszínét is:

$$
\begin{aligned}
A & = 2\pi r^{2} + 2\pi r \cdot 2r = 6\pi r^{2} \\
V & = \pi r^{2} \cdot 2r = 2\pi r^{3}
\end{aligned}.
$$

Elvégezve az osztásokat kapjuk az eredményt.

## Gömbi geometria

A gömb felületének pontjai is alkalmasak geometria bevezetésére, ezt gömbi geometriának nevezzük. Ennek a geometriának főleg a távolsági közlekedésben van szerepe, de sok elméleti alkalmazása is van. Ugyanakkor jó néhány meglepő vagy váratlan tulajdonsággal is rendelkezik, ez pedig a szemlélet fejlesztésére is alkalmassá teszi. Az egyik legismertebb ilyen a navigációs paradoxon, ami szerint a "legrövidebb" és "legegyenesebb" útvonalak különböznek. Például a Földön, mivel jó közelítéssel gömbnek tekinthető, egy objektum helyzetét megadhatjuk a Föld középpontjától való $R$ távolsággal, a $\lambda$ hosszúsági fokkal, és a $\phi$ szélességi fokkal. Sokszor a távolságot nem adják meg, mivel a felszínen közel állandó, legfeljebb amikor lényeges, a felszíntől mért távolság formájában. Ezen paramétereket földrajzi koordináta-rendszernek is nevezik. Ennek a leképezésnek egyik folyománya, hogy a gömb ekvivalens egy 

$$
[0;R] \times [0;2\pi] \times [0;\pi]
$$

kockával.

## Topológia

Az $n$-gömb olyan topologikus tér, ami homeomorf az $n+1$ dimenziós golyó határával. Magyarul, homeomorf az euklideszi $n$-gömbbel.

A 0-gömb pontpár a diszkrét topológiával.  
Az 1-gömb homeomorf a körrel; tehát minden csomó 1-gömb.  
A 2-gömb homeomorf a (közönséges) gömbbel. Így minden ellipszoid 2-gömb.  
Az $n$-gömböt $S_{n}$-nel jelölik. Ez kompakt topologikus sokaság, aminek nincs határa. Nem feltétlenül differenciálható; ha mégis, akkor lehet, hogy nem diffeomorf az euklideszi gömbbel.  
Az euklideszi $n$-gömb kompactsága könnyen bizonyítható a Borel–Lebesgue-tétellel: A gömb egy egypontú halmaz ősképe az $\|x\|$ folytonos függvényre nézve, ezért a gömb zárt. $S_{n}$ nyilván korlátos is. Tehát korlátos és zárt, így kompakt. Az $n$-dimenziós gömb térfogata $r = 1$-re $n = 5$-ig növekszik, majd a nullához konvergál.

## További információk

Mathworld honlap (angol)  
További gömbábrázolások a Vidám Matek angol honlapról  
Vetülettan (magyar)

## Megjegyzések

## Források
![[Einstein_gyro_gravity_probe_b.jpg]]
![[Sphere_3d.png]]
![[Sphere_wireframe_10deg_6r.svg]]
![[The_Earth_seen_from_Apollo_17.jpg]]
