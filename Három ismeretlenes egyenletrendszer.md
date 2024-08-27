---
dg-publish: true
---
### Általános forma

A három ismeretlenes egyenletrendszer általános formája:

$$
\begin{aligned}
    a_1x + b_1y + c_1z &= d_1 \\
    a_2x + b_2y + c_2z &= d_2 \\
    a_3x + b_3y + c_3z &= d_3
\end{aligned}
$$

ahol $a_1$, $b_1$, $c_1$, $d_1$, $a_2$, $b_2$, $c_2$, $d_2$, $a_3$, $b_3$, $c_3$, $d_3$ konstansok, és $x$, $y$, $z$ az ismeretlenek.

### Megoldási módszerek

1. **Helyettesítéses módszer**:
    - Az egyik egyenletből kifejezzük az egyik ismeretlent ($x$-et, $y$-t vagy $z$-t), majd ezt behelyettesítjük a másik két egyenletbe, így egy két ismeretlenes egyenletrendszert kapunk.

2. **Gauss-elimináció**:
    - A Gauss-elimináció során az egyenleteket lépésről lépésre alakítjuk úgy, hogy végül egy felső háromszög mátrixot kapjunk, amelyet visszahelyettesítéssel oldunk meg.

### Példa

Oldjuk meg a következő egyenletrendszert:

$$
\begin{aligned}
    x + 2y + 3z &= 9 \\
    2x + 3y + z &= 8 \\
    3x + y + 2z &= 7
\end{aligned}
$$

**Megoldás Gauss-Eliminációval:**

1. Az első egyenletből kivonjuk a másodikat, majd a harmadikat, hogy kiküszöböljük az $x$-et:

$$
\begin{aligned}
    2y + 3z &= 9 - (2x + 3y + z) \quad \Rightarrow \quad -y + 2z = 1 \quad (\text{második sor}) \\
    3y + 5z &= 7 - (3x + y + 2z) \quad \Rightarrow \quad -2y + 5z = -2 \quad (\text{harmadik sor})
\end{aligned}
$$

2. A második egyenletet kivonjuk a harmadikból, hogy kiküszöböljük a $y$-t:

$$
3z = 3 \quad \Rightarrow \quad z = 1
$$

3. A $z$ értékét visszahelyettesítjük a második egyenletbe:

$$
-y + 2(1) = 1 \quad \Rightarrow \quad y = 1
$$

4. Végül $y$ és $z$ értékét visszahelyettesítjük az első egyenletbe:

$$
x + 2(1) + 3(1) = 9 \quad \Rightarrow \quad x = 4
$$

Tehát a megoldás: $x = 4$, $y = 1$, $z = 1$.