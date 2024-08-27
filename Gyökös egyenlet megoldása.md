---
dg-publish: true
---
A **[[gyök]]ös egyenletek** olyan egyenletek, amelyekben az ismeretlen változó gyök alatt szerepel. Az általános forma:
$$
\sqrt[n]{f(x)} = g(x)
$$
ahol $n$ a gyök fokszáma, $f(x)$ és $g(x)$ pedig valamilyen függvények.

### Megoldási módszer

A gyökös egyenletek megoldásakor a gyököt el kell tüntetni, hogy egy hagyományosabb egyenletet kapjunk. Ennek lépései:
1. **Mindkét oldalt n-edik hatványra emeljük**:
$$
\left(\sqrt[n]{f(x)}\right)^n = \left(g(x)\right)^n
$$
2. **Az így kapott egyenletet megoldjuk**.
3. **Ellenőrizzük** a kapott megoldásokat, mivel az emelés hamis gyököket is eredményezhet.

### Példa

Oldjuk meg a következő gyökös egyenletet:

$$
\sqrt{x + 3} = x - 1
$$
**Megoldás:**
1. Mindkét oldalt négyzetre emeljük:
$$
(\sqrt{x + 3})^2 = (x - 1)^2
$$
$$
x + 3 = x^2 - 2x + 1
$$
2. Az egyenletet átrendezzük:
$$
x^2 - 3x - 2 = 0
$$
3. A másodfokú egyenletet megoldjuk:
$$
x_1 = -1, \quad x_2 = 2
$$
4. Ellenőrizzük a gyököket az eredeti egyenletben:
- $x = 2$ valódi megoldás.
- $x = -1$ hamis gyök, mert $\sqrt{-1 + 3}$ nem egyenlő $-1 - 1$-gyel.

Tehát az egyetlen megoldás $x = 2$.