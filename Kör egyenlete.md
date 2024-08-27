---
dg-publish: true
---

A [[kör]] általános egyenlete: $Ax^2 + Ay^2 + Cx + Dy + E = 0$ (ezt kapjuk a lenti egyenlet felbontását követően); 

A kör egyenlete teljes négyzetté alakítás után: 
$$(x - u)^2 + (y - v)^2 = r^2$$

(ahol $u$ és $v$ változók a kör középpontjának az origóhoz viszonyított távolságát mutatják $u:= abszcissza; v:= ordináta$, $r$ pedig a kör sugarának hossza egységben); Tehát ha a kör középpontja $C$, akkor $C(u; v)$ koordinátákkal rendelkezik az egyenletből következtetve. Az origó középpontú kör egyenlete: $x^2 + y^2 = r^2$ (tehát ha a kör középpontját tekintem $C$-nek, akkor $C(0; 0)$, mert origó középpontú a kör). Legyen adott egy $C(x_1; y_1)$-nem origó- középpontú kör, melynek egyik, a körvonalon levő pontja $P(x_2; y_2)$. A kör egyenletét nagyon egyszerűen felírhatjuk, ha a második, általános helyzetű kör egyenletének általános alakját vesszük:

$(x - x_1)^2 + (y - y_1)^2 = |-CP\rightarrow|^2;$

vagy: $(x - x_1)^2 + (y - y_1)^2 = |-PC\rightarrow|^2;$

ahol: $|-CP\rightarrow| = |-PC\rightarrow| = | r |;$ mert a kör sugarát a kör középpontja és a körvonal egy tetszőleges pontja között fennálló távolság adja. A kör egyenlete Pitagorasz tételére visszavezethetően kanonikus egyenletként is értelmezhető, mivel könnyen észrevehető belőle Pitagorasz tételének $a^2 + b^2 = c^2$ (két befogó négyzeteinek összege és az átfogó négyzete között fennálló ekvivalencia) általános formulája.

### A kör egyenleteihez kapcsolódó alapfeladatok

Határozzuk meg annak a körnek az egyenletét, melynek adott két olyan $A(a_1; a_2)$ és $B(b_1; b_2)$ pontja, mely a kör átmérőjének két végpontja! A rendelkezésre álló adatokból meghatározható a kör középpontja, melyet az $AB$ szakasz $FAB$ felezőpontja ad, ahol: 
$FAB\left[\frac{(a_1+b_1)}{2}; \frac{(a_2+b_2)}{2}\right].$ 
FAB = $O(középpont)$ a kapott egyenlet a fenti definíciók alapján:
$\left[x - \frac{(a_1 + b_1)}{2}\right]^2 + \left[y - \frac{(a_2 + b_2)}{2}\right]^2 = |-AO\rightarrow|^2$
ahol $|-AO\rightarrow|= |-BO\rightarrow|= | r |$.

## A kör érintőjének egyenlete

Minden olyan esetben, ahol nem ismert az adott $P$ pontból húzható kör egyenletének meghatározásánál a $P$ pont helyzete a körhöz viszonyítva, ott végezzük el a szükséges számításokat ennek érdekében; erről a definíciós kifejtés végén olvashatsz.

### Ha $P$ rajta van a kör körvonalán

Adott egy $(k)$ kör egyenlete és egy, a kör körvonalán elhelyezkedő $(P)$ pont, melyből egy $(e)$ érintőt írunk a körhöz. Ha ismeretében vagyunk a kör egyenletének vagy a kör középpontjának, akkor a középpont koordinátáinak felhasználásával adódik az alábbi képlet, hogy:

$
e: (x - x')(p_1 - x') + (y - y')(p_2 - y') = r^2
$ 

ahol: $C:=a\; kör\; középpontja;$ 
$P:= a\; körvonal\; egy\; pontja;$
és $C(x'; y');$ 
valamint $P(p_1; p_2)$.

### Ha $P$ a körön kívül helyezkedik el

A fenti képletnek van egy aprócska szépséghibája: ha adott egy $Q$ pont, mely az előző példával szemben nem a kör körvonalán helyezkedik el, akkor a képlet nem működik; hibás. Legyen adott az előzőhöz hasonlóan minden, annyi különbséggel, hogy a $P$ pont a körön kívül foglaljon helyet! Ekkor nem konkrét képletet fogunk felhasználni, hanem az elemi geometriából megismert Thálesz-tételt alkalmazzuk a $P$ pont és a kör középpontja között fennálló távolságra nézve. Vegyük a $PC$ távolság szakaszfelező pontját (ez lesz a Thálesz-kör középpontja), majd $PC$ felének hosszát, s a kapott két adat segítségével írjuk fel ezen adatokkal értelmezett kör egyenletét. Ha felírtuk a Thálesz-kör egyenletét, akkor az eredeti kör egyenletével együtt egyenletrendszerbe kapcsoljuk, majd a négyzetes tagok kiküszöbölésével kifejezzük az egyik ismeretlent, mellyel behelyettesítünk az egyik egyenletbe, s így egy olyan egyismeretlenes másodfokú egyenletet kell megoldanunk, ahol a feladat értelmezéséből eredőleg ezen egyenlet diszkrimináns értékének nagyobbnak kell lennie, mint zérus, tehát:

Diszkusszió: $0 < (b^2 - 4ac)$. Ha az eddigiek során helyesen jártunk el, akkor az említett másodfokú egyenlet megoldása során $2$ valós gyököt kaptunk, majd kifejezzük a másik ismeretlen értékét is, s így a $4$ érték megfelelő párosítás után $1-1$ koordinátát fog meghatározni. E két koordináta bizonyítottan azoknak az egyeneseknek $1-1$ pontja, melyeket érintőként definiálunk, másik pontja pedig mindkettő érintőnek az egyenesen kívül eső $P$ pont. Így az egyenes egyenleténél megismert eljárás alapján meg tudjuk határozni mindkét érintőt, mint egyenesek egyenleteit. A $k$ kör; a Thálesz-kör és a $P$ pontból húzható érintők egyenlete (ha $P$ eleget tesz a diszkussziónak).

### Ha $P$ a körvonalon belül található

Az egy pontból húzható kör érintőjének egyenlete akkor nincs definiálva, ha a pont a körön belül helyezkedik el. Ekkor nem létezik olyan $e$ érintő, melynek egy pontja a kör körvonala és merőleges lenne ezen kör sugarára.

Ezért szükséges az egyenes egyenletének felírása előtt megvizsgálni, hogy az adott koordinátákkal rendelkező pont a:
1) kör körvonalán; (1 érintő)
2) a körön kívül; (2 érintő)
3) vagy a körön belül helyezkedik el. (nincs érintő) Annak függvényében teljesül a fent látható három eset egyike, hogy egyenlőtlenség vagy ekvivalencia áll fenn a képletbe történő behelyettesítés után, illetve hogy ha egyenlőtlenség áll fenn, akkor milyen az egyenlőtlenség iránya a konstansok között. Döntsük el, hogy milyen $P$ pontnak $k$ körhöz viszonyított relatív helyzete! Tegyük fel, hogy adott egy kör egyenlete $k: (x - x')^2 + (y - y')^2 = r^2$ formában, valamint adott egy $P(x_1; y_1)$ pont. Helyettesítsünk be $P$ koordinátájával $k$ egyenletébe:

$(x_1 - x')^2 + (y_1 - y')^2 = r^2.$

Ha az ekvivalencia nem áll fenn, akkor meg kell állapítanunk, hogy a jobb vagy a bal oldali érték nagyobb-e. A fent említett első eset teljesül, ha az egyenlőség fennáll:

$(x_1 - x')^2 + (y_1 - y')^2 = r^2;$ 

A második eset teljesül, ha a bal oldali érték nagyobb:

$(x_1 - x')^2 + (y_1 - y')^2 > r^2;$ 

A harmadik eset áll fenn, ha a jobb oldali érték nagyobb:

$(x_1 - x')^2 + (y_1 - y')^2 < r^2.$
