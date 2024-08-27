---
dg-publish: true
---
Egy tetszőleges $e$ [[egyenes]] egyenletét is többféle módon meghatározhatjuk:

- bármely egyenes egyenlete meghatározható két pontjának koordinátáiból;
- bármely, origón át nem haladó egyenes egyenlete meghatározható tengelymetszeteiből;
- bármely egyenes egyenlete felírható, ha ismerjük egy pontját és egyik tengelyhez viszonyított szögét (melyből felírható az egyenes iránytangense);
- továbbá felírhatjuk az $e$ egyenes egyenletét, ha ismerjük a vele párhuzamos egyenes egyenletét, és ismeretében vagyunk a két egyenes között fennálló előjeles távolságnak ($=$ a párhuzamos egyenes melyik oldalára esik - ellenkező esetben két egyenesről beszélhetünk: $e$ és $e'$);
- felírható az $e$ egyenes egyenlete, ha ismert egy rá merőleges egyenes egyenlete (normálvektor alkalmazása) és ismert a metszéspontjuk (metszéspont híján végtelen számú merőleges $e$ egyenes írható fel);
- felírható az $e$ egyenes egyenlete, ha adott egy rá illeszkedő pont és az egyenes irányvektora;
- felírható az $e$ egyenes egyenlete, ha adott egy rá illeszkedő pont és az egyenes normálvektora;
- felírható az egyenes egyenlete, ha ismerjük egy metsző egyenes egyenletét és az egyenesek által bezárt szöget, illetve a metszéspontot.
- felírható egy $e$ egyenes egyenlete, ha ismert két pont, melyektől egyenlő távolságra van az $e$ egyenes minden pontja.

## Az egyenes egyenletének felírásának módjai

### Kétdimenziós esetekben

[[Egyenes irányvektoros egyenlete]]

[[Irányvektorból normálvektor]]
[[Egyenes normálvektoros egyenlete]]
#### Az origón át nem haladó egyenes egyenletének tengelymetszetes alakja (Hesse-alak)

$\frac{x}{a} + \frac{y}{b} = 1$

ahol az egyenes által kimetszett tengelyrészek: $a$ (abszcissza); $b$ (ordináta).

#### Az egyenes meredekségével kifejezett egyenlet

$y - y_0 = m(x - x_0)$

ahol $m = \tan \beta$ (tehát $m =$ iránytangens) és $\tan \beta = \frac{b}{a}$ ($b=$ ordináta; $a=$ abszcissza értékek), melyből levezethető az egyenes irányszöge: $\beta$. Ez alól kivétel az $x=x_0$ képletű függőleges egyenes (melynek irányszöge $90°$).

### Háromdimenziós lineáris terek esetében

#### Az egyenes kanonikus egyenletrendszere

Legyenek adottak a tér $A=(x_1, y_1, z_1)$ és $B=(x_2, y_2, z_2)$ koordinátái, melyekről tudjuk, hogy a keresett $e$ egyenes tetszőleges két pontjai. Ekkor az egyenes kanonikus egyenletrendszere a következő:

$e: \frac{x-x_1}{x_2-x_1} = \frac{y-y_1}{y_2-y_1} = \frac{z-z_1}{z_2-z_1}$ 

(ahol a törtek nevezőjében található különbségek az $AB$ irányvektor megfelelő komponensei). Ez a képlet csak abban az esetben alkalmazható, ha $x_1 \neq x_2$, $y_1 \neq y_2$, $z_1 \neq z_2$. Az általános eset képlete:

$(x-x_1)(y_2-y_1) = (y-y_1)(x_2-x_1)$
$(y-y_1)(z_2-z_1) = (z-z_1)(y_2-y_1)$
$(z-z_1)(x_2-x_1) = (x-x_1)(z_2-z_1)$

#### Az egyenes paraméteres egyenletrendszere

Legyenek adottak a tér $A=(x_1, y_1, z_1)$ és $B=(x_2, y_2, z_2)$ koordinátái, melyekről tudjuk, hogy a keresett $e$ egyenes tetszőleges két pontjai. Ekkor az egyenes kanonikus egyenletrendszere az alábbi alakot veszi fel:

$x = (x_2-x_1)t + x_1$
$y = (y_2-y_1)t + y_1$
$z = (z_2-z_1)t + z_1$

(ahol $t \in \mathbb{R}$ és az egyenletrendszerben szereplő $t$ együtthatói pedig az $AB$ irányvektor megfelelő komponensei).

Megjegyzés: Bármely térbeli egyenes egyenletét meghatározhatjuk a harmadrendű determináns felhasználásával, ahol a determinánst zérussal tesszük ekvivalenssé. A harmadrendű determinánst előbb felbontjuk másodrendű determinánsokra, majd a lineáris algebrában a másodrendű determinánsoknál már ismert eljárással kiértékeljük az ismeretlenek együtthatóit.

$\mathbf{p} - \mathbf{p_1} \parallel \mathbf{p_2} - \mathbf{p_1} \leftrightarrow$ 

$(\mathbf{p} - \mathbf{p_1}) \times (\mathbf{p_2} - \mathbf{p_1}) = \mathbf{0} \leftrightarrow$ 

$\begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ x-x_1 & y-y_1 & z-z_1 \\ x_2-x_1 & y_2-y_1 & z_2-z_1 \end{vmatrix} = \left( \begin{vmatrix} y-y_1 & z-z_1 \\ y_2-y_1 & z_2-z_1 \end{vmatrix}, -\begin{vmatrix} x-x_1 & z-z_1 \\ x_2-x_1 & z_2-z_1 \end{vmatrix}, \begin{vmatrix} x-x_1 & y-y_1 \\ x_2-x_1 & y_2-y_1 \end{vmatrix} \right) = \mathbf{0}$
