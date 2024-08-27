---
dg-publish: true
---
Egyenletrendszerről beszélünk a matematikában akkor, ha van legalább 2 olyan egyenlet, melyeknek külön-külön vett megoldáshalmazuknak metszete megoldásul szolgálhat az egyenletrendszerre nézve. Az egyenletrendszereket úgy definiáljuk, hogy az egyes egyenleteket egymás alá írjuk, majd egyik oldalról egy egybefoglaló kapcsos zárójellel látjuk el a rendszert (ettől a konvenciótól itt eltekintünk).

Az **egyenletrendszerek** több egyenletből állnak, amelyekben több ismeretlen szerepel. Az egyenletrendszer megoldása az ismeretlenek olyan értékeinek meghatározása, amelyek kielégítik az összes egyenletet.

[[Két ismeretlenes egyenletrendszer]]
[[Három ismeretlenes egyenletrendszer]]

## Egyenletrendszerek kategóriái

(Az egyenletrendszerek kategorizálásánál az egyenlet szócikkben olvashatóakhoz képest hasonlóan jártam el.)
Az egyenletrendszereket az egyenletekhez hasonlóan többféle szempont alapján csoportosíthatjuk:
1) Jellegszerűen:
- Algebrai egyenletrendszerek
- Transzcendens egyenletrendszerek
- Hibrid egyenletrendszerek
- Differenciál-egyenletrendszerek.
  
2) Fokális szempont alapján:
- Lineáris
- Másodfokú (kvadratikus)
- Harmadfokú
- Negyedfokú
- Magasabb fokú
  
3) Az ismeretlenek és az egyenletek számának relatív aránya alapján: 
$$|N| := \text{az ismeretlenek száma}; \quad |M| := \text{az egyenletek száma a rendszerben}$$

$$|N| < |M| \quad \text{(Legtöbbször nincs egyértelmű megoldás csak ellentmondás)}$$
$$|N| = |M| \quad \text{(Általában egy megoldás (gyök) van.)}$$
$$|N| > |M| \quad \text{(Legtöbbször van megoldás (megoldáshalmaz) /parciális megoldás/)}$$

## Megoldási alternatívák - (Lineáris egyenletrendszerekre nézve)

A különböző egyenletrendszerek megoldhatóságát az egyenletek típusa, száma és jellege alapján mérlegelhetjük; ezeknek függvényében változhat az, hogy melyik operációt illetve számítási algoritmust tudjuk alkalmazni, illetve gyakran előfordul, hogy egyik módszerrel könnyebben megoldhatóak különböző egyenletrendszerek mint egy másik módszer felhasználásával. Néhány nevezetesebb és ismertebb eljárást soroltam fel és ismertetek: (Esetünkben tekintsünk minden egyenletrendszert -a fentiek alapján- $$|N| = |M|$$ típusúnak!)

### Egyenlő együtthatók

Az egyenlő együtthatók módszerét főként kettő- és három egyenletből álló egyenletrendszerek esetében alkalmazzuk. Legyen adott egy kétismeretlenes egyenletrendszer:
$$3x + 5y = 15$$
$$2x - 4y = 20$$

Ahogyan az a módszer elnevezéséből is következik, az eljárás lényege, hogy az egyenletekben szereplő egyik ismeretlen együtthatói ekvivalensek legyenek egymással. Ezt követően a két egyenletet összeadjuk vagy kivonjuk egymásból annak függvényében, miképp tudjuk az aktuális egyik ismeretlent kiejteni a rendszerből. Küszöböljük ki az $$x$$-es ismeretlent! Ennek érdekében szorozzuk meg az első egyenletet 2-vel, a másodikat pedig 3-mal:
$$6x + 10y = 30$$
$$6x - 12y = 60$$

Vonjuk ki az egyik egyenletet a másikból: (I - II)
$$22y = -30$$
$$y = -\frac{30}{22}$$

Helyettesítsünk vissza az eredeti egyenletrendszer egyik tetszőleges egyenletébe:
$$3x - \frac{150}{22} = 15$$
$$66x - 150 = 330$$
$$66x = 480$$
$$x = \frac{80}{11}$$

### Behelyettesítés

Vegyük alapul az előző egyenletrendszert:
$$3x + 5y = 15$$
$$2x - 4y = 20$$

Majd oldjuk meg a behelyettesítés módszerével! Az eljárás lényege abban merül ki, hogy legalább az egyik ismeretlen értékét kifejezzük, majd a kifejezett összefüggéssel behelyettesítünk az egyenletrendszer egy másik egyenletének megfelelő ismeretlenjének helyére:
$$3x + 5y = 15 \quad \Rightarrow \quad x = \frac{15 - 5y}{3}$$
$$2x - 4y = 20$$
$$2\left(\frac{15 - 5y}{3}\right) - 4y = 20$$
$$30 - 10y - 12y = 60$$
$$-22y = 30$$
$$y = -\frac{30}{22}; \quad x = \frac{80}{11}$$

### Determinálás

A determináns szó jelentése: meghatározni, lineáris egyenletrendszerek megoldása során pedig az alábbi sorokban látható módszert a determináns alkalmazásával Cramer-szabálynak szokás nevezni. A Cramer-szabályt egyenletrendszerek megoldása során kizárólag lineáris egyenletrendszerek esetében használhatjuk fel, amikor is az egyenletrendszer határozott (a különböző ismeretlenek és az egyenletek száma egyenlő) és a rendszer determinánsa $$D$$ nem zérus! A determinánsokban olyan mátrixszerű elrendezésben írjuk fel az egyenletrendszer ismeretlen tagjainak együtthatóit valamint a konstans tagokat, melyek segítségével meghatározhatóak (determinálhatóak) az ismeretlenek lehetséges értékei.

Vegyük alapul az előző egyenletrendszert:
$$3x + 5y = 15$$
$$2x - 4y = 20$$

$$D_x := \text{az } x \text{ determinánsa}; \quad D_y := \text{az } y \text{ determinánsa}; \quad D := \text{a rendszer determinánsa}$$

Feltétel: $$D \neq 0$$.

$$D_x = \begin{vmatrix} 15 & 5 \\ 20 & -4 \end{vmatrix} = 15 \cdot (-4) - 20 \cdot 5 = -60 - 100 = -160$$

$$D_y = \begin{vmatrix} 3 & 15 \\ 2 & 20 \end{vmatrix} = 3 \cdot 20 - 2 \cdot 15 = 60 - 30 = 30$$

$$D = \begin{vmatrix} 3 & 5 \\ 2 & -4 \end{vmatrix} = 3 \cdot (-4) - 2 \cdot 5 = -12 - 10 = -22$$

$$x = \frac{D_x}{D}$$
$$y = \frac{D_y}{D}$$
$$x = \frac{-160}{-22} = \frac{80}{11}; \quad y = \frac{30}{-22}$$

### Gauss-elimináció

### Lineáris bázistranszformáció

Tekintsük adottnak azon lineáris egyenletrendszereket, melyekben az ismeretlenek száma több, mint a rendszerben szereplő egyenletek száma. Ekkor határozatlan egyenletrendszerről beszélhetünk, melyeket az előző módszerekkel nem, vagy csak hosszadalmasabban tudunk megoldani. A továbbiakban az egyenletrendszerben szereplő ismeretleneket együtthatóikkal együtt egy úgynevezett vektortér elemeiként értelmezzük, melyek a lineáris kombináció definíciója alapján vektorokat alkotnak egy $$n$$ dimenziós vektortérben, ahol a dimenziószám éppen a különböző $$x, y, z, ... i$$ ismeretlenek számosságával egyenlő. Ekkor a lineáris bázistranszformáció a bázistranszformáció szakaszra való kattintás után felugró szócikkben olvashatóak alapján történik. Megj.: A lineáris bázistranszformációs eljárás és a Gauss-elimináció között szoros párhuzam vonható a vektorokra nézve.

