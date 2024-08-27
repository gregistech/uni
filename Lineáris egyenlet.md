---
dg-publish: true
---
[[Első fokú, abszolút értéket is tartalmazó egyenletek és egyenlőtlenségek megoldása]]

Lineáris egyenleteknek nevezzük az $L_1(x)+c_1=L_2(x)+c_2$ alakú egyenleteket, ahol $L_1$ és $L_2$ lineáris operátor (lineáris leképezés) $c_1$ és $c_2$ konstans, $x$ pedig ismeretlen. 

A szakirodalom általában csak az $L(x)=c$ alakú egyenletekre korlátozódik, ugyanis bizonyítható, hogy $L=L_1-L_2$ és $c=c_2-c_1$ helyettesítéssel az egyenlet a másikba transzformálható, tehát a két definíció lényegében egyenértékű. 

A szakirodalom nagyon sokszor kiegyenlíti a lineáris egyenletet az elsőfokú egyenlettel, habár például a $0\cdot x=2$ egyenlet lineáris, de nem elsőfokú (csak látszólag), mivel lényegében a $0=2$ egyenletről van szó, amelyből „kiesett” az ismeretlen, és így nulladfokú. Az ismeretlen ($x$) lehet rendezett pár, számhármas, számnégyes stb., így lényegében az előbbi definíció magába foglalja az egy- és többismeretlenes lineáris egyenleteket is. 

Az $L(x)=c$ képlet helyett általában csak egyszerűen $Lx=c$ képletet írnak.  
## Lineáris egyenletek megoldása

Az $Lx=c$ egyenlet megoldása az $x=L^{-1}c$, ha az $L$ operátornak létezik inverze ($L^{-1}$), azaz ha az $L$ bijektív. Ha az $L$ nem bijektív, akkor az $Lx=c$ egyenletnek több (általában végtelen sok) megoldása van.  

A valós számok halmazán, egy ismeretlen esetében, ez így néz ki: Az $a\cdot x = b$ egyenlet megoldáshalmaza  ${\displaystyle {\Big \{}{\frac {b}{a}}{\Big \}}}$, azaz egy megoldása van, a ${\displaystyle {\frac {b}{a}}}$, ha $a \neq 0$ ${\displaystyle {\Big \{}{\Big \}}}$, (=∅), azaz nincs megoldása, ha $a = 0$ és $b \neq 0$ ${\displaystyle \mathbb {R} }$, azaz bármely szám megoldása, ha $a = 0$ és $b = 0$  

## Lineáris egyenletek logikai kapcsolata más matematikai elemekkel

Az elsőfokú egyenleteket elsősorban az egyenesekkel és azok egyenletével tudjuk összefüggésbe hozni, mivel bármely lineáris egyenlet egy egyenest definiál a numerikus analízis nyelvén. Az egyenes egyenletét lineáris függvényként is értelmezhetjük, tehát a lineáris algebra elsőfokú egyenletéből rögtön találunk párhuzamokat koordinátageometriai és az analízisben előforduló fogalmakkal.  

Az egyenes egyenletének kanonikus alakja:  
${\displaystyle Ax+By-C=0.}$

A lineáris függvények formája:  
${\displaystyle y=ax+b.}$  

Lineáris egyenletrendszerek:  
$A_1x + B_1y = C$  
$A_2x + B_2y = D$