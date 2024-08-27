---
dg-publish: true
---
### Bizonyítás

Használjuk a lenti ábra jelöléseit:

Ha a $D$ pontból párhuzamost húzunk a $b$ oldallal, akkor az így keletkezett $DE$ szakasz megegyezik $b$-vel. Az így kapott háromszög három oldala $a-c$, $b$ és $d$. Fejezzük ki $\alpha$-t a koszinusztétellel:

$
\cos \alpha = \frac{(a-c)^{2}+d^{2}-b^{2}}{2d(a-c)}
$

Ebből fejezzük ki $\sin \alpha$-t:

$
\cos^{2} \alpha = \Bigg(\frac{(a-c)^{2}+d^{2}-b^{2}}{2d(a-c)}\Bigg)^{2}
$

$
\sin^{2} \alpha = 1 - \cos^{2} \alpha = 1 - \Bigg(\frac{(a-c)^{2}+d^{2}-b^{2}}{2d(a-c)}\Bigg)^{2} = \frac{4d^{2}(a-c)^{2}-\Big((a-c)^{2}+d^{2}-b^{2}\Big)^{2}}{4d^{2}(a-c)^{2}}
$

$
\sin \alpha = \frac{\sqrt{4d^{2}(a-c)^{2}-\Big((a-c)^{2}+d^{2}-b^{2}\Big)^{2}}}{2d(a-c)}
$

Az $ADE$ háromszögben fejezzük ki $m$-et $d$ és $\sin \alpha$ segítségével:

$
m = d \cdot \sin \alpha = \frac{\sqrt{4d^{2}(a-c)^{2}-\Big((a-c)^{2}+d^{2}-b^{2}\Big)^{2}}}{2(a-c)}
$

A szorzattá alakításokat annak segítségével végezzük el, hogy két négyzetszám különbsége felírható a két szám összegének és különbségének szorzataként:

$
\frac{\sqrt{4d^{2}(a-c)^{2}-\Big((a-c)^{2}+d^{2}-b^{2}\Big)^{2}}}{2(a-c)}=
$

$
= \frac{\sqrt{\Big(2d(a-c)-(a-c)^{2}-d^{2}+b^{2}\Big)\Big(2d(a-c)+(a-c)^{2}+d^{2}-b^{2}\Big)}}{2(a-c)}
$

$
= \frac{\sqrt{\Big(b^{2}-(a-c-d)^{2}\Big)\Big((a-c+d)^{2}-b^{2}\Big)}}{2(a-c)}
$

$
= \frac{\sqrt{(b-a+c+d)(b+a-c-d)(a-c+d-b)(a-c+d+b)}}{2(a-c)}
$

$
m = \frac{\sqrt{(a+b-c+d)(a-b-c+d)(a+b-c-d)(-a+b+c+d)}}{2(a-c)}
$

Ezt az $m$-et behelyettesítjük a 

$
T = \frac{a+c}{2} m
$

képletbe:

$
T = \frac{a+c}{2} \cdot \frac{\sqrt{(a+b-c+d)(a-b-c+d)(a+b-c-d)(-a+b+c+d)}}{2(a-c)}
$

$
T = \frac{a+c}{4(a-c)} \cdot \sqrt{(a+b-c+d)(a-b-c+d)(a+b-c-d)(-a+b+c+d)}
$

Ha a trapézunk húrtrapéz, akkor területét Brahmagupta képletével is kiszámolhatjuk hiszen ekkor húrnégyszög is egyben.
