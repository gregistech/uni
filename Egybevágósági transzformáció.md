---
dg-publish: true
---
Egybevágósági transzformációnak (továbbiakban röviden egybevágóságnak) nevezzük a tér önmagára vonatkozó kölcsönösen egyértelmű leképezését, amely a szakaszokat velük egybevágó szakaszokba viszi. A tér egybevágóságai a kompozíció műveletével csoportot alkotnak. Ez a csoport nem kommutatív. A műveletet jobbról balra végezzük el, azaz pl ha $T$ egy tengelyes tükrözés, $F$ pedig egy forgatás, akkor $TF$ esetén előbb a forgatást végezzük el, és csak aztán a tükrözést.

## A síkbeli egybevágóságok tulajdonságai

Tétel: Az egybevágóság egyenestartó transzformáció.  
Bizonyítás: Legyenek $A$, $B$, $C$ egy egyenes három különböző pontja, ebben a sorrendben, ekkor
$$
{\overline {AB}}+{\overline {BC}}={\overline {AC}}.
$$
Indirekt tegyük fel, hogy a $T$ egybevágóság ezt a három pontot olyan $A'$, $B'$, $C'$ pontokba viszi, amelyek nem egy egyenesen vannak, tehát egy háromszög csúcspontjai. Mivel $T$ egybevágóság, ezért az
$$
{\overline {A'B'}}+{\overline {B'C'}}={\overline {A'C'}}
$$
egyenletnek teljesülnie kell. Viszont mivel $A'$, $B'$, $C'$ egy háromszög három csúcsa, az oldalaira igaz a háromszög-egyenlőtlenség:
$$
{\overline {A'B'}}+{\overline {B'C'}}>{\overline {A'C'}},
$$
ami ellentmondás, mert nyilván nem lehet, hogy két mennyiség egyenlő, ugyanakkor az egyik nagyobb mint a másik. Tehát az indirekt feltevés hamis, vagyis igaz az állítás.

Tétel: Ha egy egybevágóságnak létezik 2 (különböző) fix pontja, akkor a két pontot összekötő egyenes minden pontja fix.  
Bizonyítás: Legyen $A$, $B$ a két különböző fix pont, $e$ pedig az általuk meghatározott egyenes. Legyen $P$ egy, az $A$-tól és a $B$-től különböző pontja $e$-nek. Indirekt tegyük fel, hogy $P'$ (P képe) egy $P$-től különböző pontja az egyenesnek. Mivel egybevágóságról van szó:
$$
{\overline {PA}}={\overline {P'A}}\quad {\overline {PB}}={\overline {P'B}}
$$
teljesülnek, azaz $A$ és $B$ rajta vannak a $PP'$ felező merőlegesén. Mivel azonban az $e$-n is rajta vannak, és a felező merőleges csak egy pontban metsz $e$-t:
$$
A=B,
$$
ami ellentmondás, tehát $e$ minden pontja fix.

Tétel: Ha egy egybevágóságnak létezik 3 nem kollineáris fix pontja, akkor a sík minden pontja fix, azaz az egybevágóság identitása a síknak.  
Bizonyítás: Legyenek $A$, $B$, $C$ a fix pontok. Ekkor az általuk alkotott háromszög mindhárom oldalegyenese fix. Vegyünk fel egy tetszőleges $P$ pontot a síkon, és legyen $Q$ az egyik oldalegyenes belső pontja. A Pasch-axióma miatt létezik olyan $R$ pont, hogy a $PQ$ egyenes $R$-ben metszi egy másik egyenes belső pontját. Mivel $Q$, $R$ fix pontok (az oldalegyenesek minden pontja fix), az $RQ$ egyenesnek is minden pontja fix, tehát $P$ is az.

Az eddigi tételek igazak a térben is, a következőkben viszont szigorúan egysíkúak leszünk.

### Tengelyes tükrözés

Tengelyes tükrözés: A síknak egy adott $t$ egyenesre való tükrözése az a leképezés, amely egy tetszőleges $P$ ponthoz azt a $P'$ pontot rendeli képként, amelyre igaz, hogy
$$
PP'\perp t
$$
és
$$
PP'\cap t.
$$
A $t$ egyenes pontjai fixek. A tükrözést a tengellyel lehet jellemezni. Kétszer egymás után ugyanarra az egyenesre tükrözés az identitás (azaz:
$$
t\cdot t=t^{2}=1\Leftrightarrow t^{-1}=t).
$$

Tétel: Az egyenesre vonatkozó tükrözés egybevágóság.  
Bizonyítás:
$$
\Delta _{PTU}\cong \Delta _{P'TU}
$$
mivel a $TU$ oldal közös,
$$
PT\cong P'T
$$
és a $PTU$ szög egyenlő a $P'TU$ szöggel. Ebből következik, hogy
$$
{\overline {PU}}\cong {\overline {P'U}}
$$
és $PUT$ szög egyenlő $P'UT$ szöggel, tehát $QUP$ szög egyenlő $Q'UP'$ szöggel. Ezekből:
$$
\Delta _{PUQ}\cong \Delta _{P'UQ'}\Rightarrow {\overline {PQ}}\cong {\overline {P'Q'}}.
$$

Tétel: Ha a sík egy identitástól különböző $T$ egybevágóságnak van két fix pontja, akkor $T$ a fixpontokat összekötő egyenesre vonatkozó tengelyes tükrözés.  
Bizonyítás: Legyen $t$ a két fix ponton ($A$-n és $B$-n) áthaladó egyenes. Ekkor $t$ minden pontja fix, és tetszőleges $t$-n kívüli $P$ pont nem lehet fix (ld: előző tételek), tehát $P'$ különbözik $P$-től. Mivel $T$ egy egybevágóság:
$$
{\overline {PA}}={\overline {P'A}}\quad {\overline {PB}}={\overline {P'B}}
$$
tehát $t$ a $PP'$ szakasz felező merőlegese. Azaz:
$$
PP'\perp t\quad {\overline {PT}}\cong {\overline {P'T}}\Rightarrow
$$
$P'$ a $P$ pont tükörképe $t$-re.

Tétel: Ha a sík egy $F$ egybevágóságának pontosan 1 fix pontja van, akkor $F$ előáll két tengelyes tükrözés kompozíciójaként, melyek tengelyei áthaladnak a fixponton.  
Bizonyítás: Legyen $A$ a fix pont. Ekkor tetszőleges $A$-tól különböző $P$ esetén $P'$ különbözik $P$-től. Legyen $t$ a $PP'$ felezőmerőlegese. A rajta van $t$-n, mert
$$
{\overline {PA}}\cong {\overline {P'A}} 
$$
(ugyanis $F$ egybevágóság). Tehát a $tF$ egybevágóságnak $A$ fix pontja és $P$ is önmagára képződik (ugyanis:
$$
P\longmapsto ^{\mathbf {F}}P'\longmapsto ^{t}P).
$$
Tehát $A$ és $P$ két fix pontja a $tF$ egybevágóságnak
$$
\Rightarrow t\mathbf {F}=s\Rightarrow \mathbf {F}=ts.
$$

## Jegyzetek

## Lásd még

Transzformáció
![[T%C3%BCkr%C3%B6z%C3%A9s.png]]
![[20080516015013%21T%C3%BCkr%C3%B6z%C3%A9s.png]]
