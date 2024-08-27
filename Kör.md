---
dg-publish: true
---
[[Körcikk]]

A kör vagy körvonal egy geometriai alakzat. A geometriai meghatározás szerint kör alatt a geometriai sík tér azon pontjainak halmazát értjük, amely pontok a sík egy meghatározott pontjától (középpont) adott (sugárnyi) távolságra helyezkednek el. Körlapnak, illetve körlemeznek nevezhetjük a pontoknak azon halmazát, amelyeknek a kör középpontjától mért távolsága kisebb vagy egyenlő a kör sugarával.

## Nevezetes vonalak, körrészek

Az érintő olyan egyenes (ábrán: e), amelynek pontosan egy közös pontja van a körrel (É).  
A szelő (s) olyan egyenes, amely két pontban (M1 ill. M2) metszi a körvonalat.  
A húr olyan szakasz, mely a szelő (s) egyenes része, és végpontjai a körvonal pontjai (M1 ill. M2). Más szóval a húr nem más, mint a szelő és a körlap metszete (halmazmetszet).  
A húr illetve a szelő a körlapot két körszeletre bontja (vágja, szeli).  
A sugár vagy rádiusz ($r$) a kör középpontját és a kör egy pontját összekötő szakasz, de ezek hosszát is sugárnak szokták nevezni, habár sugárhossz lenne a helyes.  
Az átmérő ($d$) olyan húr, amely tartalmazza a középpontot (áthalad a középponton / belső pontja a középpont). E szakaszok hosszát is szokták egyszerűen átmérőnek nevezni. Az átmérő hossza kétszer akkora, mint a sugár hossza, azaz $d=2r$.  
A körvonalat bármely két pontja két diszjunkt összefüggő részre (vonalra) osztja. Ezeket a részeket körívnek, illetve egyszerűen ívnek ($i$) nevezzük.  
A körcikk olyan síkidom, melyet két sugár és egy ív határol. Ennek speciális esete a félkör, mely egyben speciális szelet is.  
A körgyűrű két koncentrikus kör közé eső sáv.  
A kör beleírható sokszögének, illetve húrsokszögnek nevezzük azt a szabályos sokszöget, melynek összes csúcsa a körívre illeszkedik, illetve minden oldala a kör húrja.  
A kör köréírható sokszögének, illetve érintősokszögnek nevezzük azt a szabályos sokszöget, melynek az összes oldala érinti a körívet.  
A körívtetőpont magassága - Egy húr középpontjára állított merőleges hossza a közelebbi körvonalig. Fontos elem az építészetben a kupolák és boltívek méretezésénél, valamint az optikában a fókuszpont megállapításához. Latinul sagitta (íj). Függvényként verszinusz néven ismeretes.

[[Kör kerülete]]
[[Kör területe]]

## Egységkör

Ha a kör sugara egységnyi, akkor egységkörnek is nevezik.

## Kör az analitikus (koordináta) geometriában

A koordinátageometriában, ahol a középponttól való eltérést $x$ ‒ $y$ mutatja, és a kör középpontja $(a,b)$, a kör sugara pedig $r$, a körvonal pontjait a következő egyenlettel határozhatjuk meg:  
$$(x-a)^{2}+(y-b)^{2}=r^{2}$$  

Ha a kör középpontja az origó, a képlet leegyszerűsödik:  
$$x^{2}+y^{2}=r^{2}$$  

## Számítógépes rajzolás

Kör – $r$ sugarú – $k_x$ x és $k_y$ y középpontú körnek az alábbi pszeudokóddal kaphatjuk meg a pontjait:  

$$\text{radian}:=2\pi;$$  
$$\text{for} I:=0 \text{ to round}(\text{radian} \cdot r) \text{ do begin}$$  
$$x_{\text{koordinatak}}[i]:=k_x+\sin(\text{radian} \cdot (i/(2 \cdot r \cdot \pi))) \cdot r$$  
$$y_{\text{koordinatak}}[i]:=k_y+\cos(\text{radian} \cdot (i/(2 \cdot r \cdot \pi))) \cdot r$$  
$$\text{end;}$$  

Beleszámítható sokszög – $r$ sugarú – $k_x$ x és $k_y$ y középpontú körben az alábbi pszeudokóddal kaphatjuk meg az $n$ oldalú sokszög csúcsait:  

$$\text{belsoszog}:=\frac{360}{n};$$  
$$\text{for} i:=0 \text{ to } n \text{ do begin}$$  
$$x_{\text{koordinatak}}[i]:=k_x+\sin(\text{belsoszog} \cdot (i/(2 \cdot r \cdot \pi))) \cdot r$$  
$$y_{\text{koordinatak}}[i]:=k_y+\cos(\text{belsoszog} \cdot (i/(2 \cdot r \cdot \pi))) \cdot r$$  
$$\text{end;}$$  

Köréírható sokszög – $r$ sugarú – $k_x$ x és $k_y$ y középpontú körben az alábbi pszeudokóddal kaphatjuk meg az $n$ oldalú sokszög csúcsait:  

$$\text{belsoszog}:=\frac{360}{n};$$  
$$\text{atfogo}:=\sqrt{(tan(\frac{\text{belsoszog}}{2}) \cdot r)^{2}+r^{2}};$$  
$$\text{for } i:=0 \text{ to } n \text{ do begin}$$  
$$x_{\text{koordinatak}}[i]:=k_x+\sin(\text{belsoszog} \cdot (i/(2 \cdot atfogo \cdot \pi))) \cdot atfogo$$  
$$y_{\text{koordinatak}}[i]:=k_y+\cos(\text{belsoszog} \cdot (i/(2 \cdot atfogo \cdot \pi))) \cdot atfogo$$  
$$\text{end;}$$  

![[K%C3%B6r.png]]