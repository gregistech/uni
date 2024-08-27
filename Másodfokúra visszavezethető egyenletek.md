---
dg-publish: true
---
 Az ilyen típusú egyenletek megoldásai a másodfokú polinom gyökei, melyek különböző módszerekkel határozhatók meg.

## Szorzattá Bontás

A szorzattá bontás módszere az alábbi lépésekből áll:

1. **Keressük meg a megfelelő párokat**, amelyek szorzata $ac$, és összegük $b$.
2. **Bontsuk szét a középső tagot** két olyan kifejezésre, amelyek összege $bx$ és szorzatuk $ac$.
3. **Csoportosítsuk** és bontsuk ki az egyes csoportokat közös tényezők alapján.

### Példa

Oldjuk meg a következő másodfokú egyenletet szorzattá bontással:
$$
x^2 + 5x + 6 = 0
$$
**Megoldás:**

1. Megkeressük a számokat, amelyek szorzata $6$ és összege $5$. Ezek a számok: $2$ és $3$.
2. Az egyenletet felírjuk:

$$
x^2 + 2x + 3x + 6 = 0
$$
3. Csoportosítás és szorzattá bontás:
$$
x(x + 2) + 3(x + 2) = 0
$$
4. Közös tényező kiemelése:
$$
(x + 3)(x + 2) = 0
$$
5. A gyökök meghatározása:
$$
x + 3 = 0 \quad \text{vagy} \quad x + 2 = 0
$$
$$
x = -3 \quad \text{vagy} \quad x = -2
$$

## A Másodfokú Polinom Gyökeinek Meghatározása

Ha az egyenlet nem bontható szorzattá egyszerűen, használhatjuk a **másodfokú képletet**:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
A gyökök meghatározásának lépései:
1. **Diszkrimináns kiszámítása**: [[Másodfokú egyenlet megoldóképletének diszkriminánsa]]
2. **Gyökök meghatározása** a [[Másodfokú egyenlet megoldóképlete]] alapján.

### Példa

Oldjuk meg a következő másodfokú egyenletet a másodfokú képlet segítségével:
$$
2x^2 + 3x - 2 = 0
$$
**Megoldás:**
1. Számoljuk ki a diszkriminánst:
$$
D = 3^2 - 4 \cdot 2 \cdot (-2) = 9 + 16 = 25
$$
2. Mivel $D > 0$, két valós gyök van, és a gyökök:
$$
x = \frac{-3 \pm \sqrt{25}}{2 \cdot 2} = \frac{-3 \pm 5}{4}
$$
3. A gyökök:
$$
x_1 = \frac{2}{4} = 0.5 \quad \text{és} \quad x_2 = \frac{-8}{4} = -2
$$