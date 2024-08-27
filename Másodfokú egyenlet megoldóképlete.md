---
dg-publish: true
---
A gyökök kiszámítására a másodfokú egyenlet megoldóképletét használjuk.

$x={\frac {-b\pm {\sqrt {b^{2}-4ac}}}{2a}}$

[[Másodfokú egyenlet megoldóképletének diszkriminánsa]]
[[Másodfokú egyenlet gyöktényezős alakja]]

### Megoldóképlet levezetése teljes négyzetté alakítással

A másodfokú egyenlet megoldóképletét a teljes négyzetté való kiegészítéssel vezethetjük le.

$ax^{2}+bx+c=0$

Elosztva a másodfokú egyenletet $a$-val (ami megengedett, mivel $a \neq 0$).

$x^{2}+{\frac {b}{a}}x+{\frac {c}{a}}=0$

ami átrendezve

$x^{2}+{\frac {b}{a}}x=-{\frac {c}{a}}$

Az egyenletnek ebben a formájában a bal oldalt teljes négyzetté alakítjuk. Egy konstanst adunk az egyenlőség bal oldalához, amely 

$x^{2}+2xy+y^{2}$

alakú teljes négyzetté egészíti ki. Mivel $2xy$ ebben az esetben ${\frac {b}{a}}x$, ezért $y={\frac {b}{2a}}$ így ${\frac {b}{2a}}$ négyzetét adva mindkét oldalhoz azt kapjuk, hogy

$x^{2}+{\frac {b}{a}}x+{\frac {b^{2}}{4a^{2}}}=-{\frac {c}{a}}+{\frac {b^{2}}{4a^{2}}}$

A bal oldal most $\left(x+{\frac {b}{2a}}\right)$ teljes négyzete. A jobb oldalt egyszerű törtként írhatjuk fel, a közös nevező $ 4a^{2} $.

$\left(x+{\frac {b}{2a}}\right)^{2}={\frac {b^{2}-4ac}{4a^{2}}}$

Négyzetgyököt vonva mindkét oldalból

$\left|x+{\frac {b}{2a}}\right|={\frac {\sqrt {b^{2}-4ac}}{|2a|}} \Leftrightarrow x+{\frac {b}{2a}}=\pm {\frac {\sqrt {b^{2}-4ac}}{2a}}$

Kivonva ${\frac {b}{2a}}$-t mindkét oldalból megkapjuk a megoldóképletet:

$x=-{\frac {b}{2a}}\pm {\frac {\sqrt {b^{2}-4ac}}{2a}}={\frac {-b\pm {\sqrt {b^{2}-4ac}}}{2a}}$

Szélsőérték helye: $-{\frac {b}{2a}}$

Ha a diszkrimináns értéke negatív, a következőképpen kell számolni:

$x=-{\frac {b}{2a}}\pm {\frac {\sqrt {(-1)(4ac-b^{2})}}{2a}}=-{\frac {b}{2a}}\pm i{\frac {\sqrt {4ac-b^{2}}}{2a}}$

A megoldás ilyenkor egy komplex konjugált gyökpár lesz.

### Alternatív módja a megoldóképlet levezetésének

Az előző levezetéssel szemben szinte törtmentesen is teljes négyzetté alakíthatunk, ha első lépésben beszorzunk $ 4a $-val. Ekkor a következőképpen járhatunk el:

$ax^{2}+bx+c=0$

$4a^{2}x^{2}+4axb+4ac=0$

$4a^{2}x^{2}+4axb+b^{2}+4ac=b^{2}$

$(2ax)^{2}+2(2ax)(b)+b^{2}+4ac=b^{2}$

$(2ax+b)^{2}+4ac=b^{2}$

$(2ax+b)^{2}=b^{2}-4ac$

$|2ax+b|={\sqrt {b^{2}-4ac}}$

$2ax+b=\pm {\sqrt {b^{2}-4ac}}$

$2ax=-b\pm {\sqrt {b^{2}-4ac}}$

Végeredményül pedig ugyanúgy eljutunk a közismert képlethez:

$x={\frac {-b\pm {\sqrt {b^{2}-4ac}}}{2a}}$
