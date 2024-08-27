---
dg-publish: true
---
### A sík normálvektoros egyenlete

Definiáljuk a síkot, mint a térnek $3$ nem egybeeső ponthalmaza által meghatározott háromszöget! Legyenek az említett háromszög csúcsai $A$, $B$ és $C$! Az $S$ sík normálvektoros egyenletének általános alakja: 

$
S: \mathbf{n_0}(\mathbf{r} - \mathbf{r_0}) = 0
$ 

Ekkor az alábbiak szerint járunk el:

Kijelöljük a háromszög egy pontját (legyen $A$), majd kiszámítjuk a kijelölt pontból a másik két pont felé mutató irányvektorok komponenseit ($\mathbf{r_{AB}}, \mathbf{r_{AC}}$); Kiszámítjuk e két vektornak egymással vett vektoriális szorzatával kapott egységvektort ($\mathbf{n_0} = \frac{\mathbf{r_{AB}} \times \mathbf{r_{AC}}}{|\mathbf{r_{AB}} \times \mathbf{r_{AC}}|}$); Felírjuk az $S$ sík normálvektoros egyenletét:

$
S: n_0^x(x - x_1) + n_0^y(y - y_1) + n_0^z(z - z_1) = 0.
$ 

(ahol $(n_0^x, n_0^y, n_0^z) = \mathbf{n_0}$ (a síkra merőleges egységvektor komponensei) és $(x_1, y_1, z_1) = A$ (a háromszög $A$ csúcsának komponensei)) A fenti egyenletben szereplő zárójeleket felbontva majd rendezve jutunk ugyanezen $S$ sík általános alakjához:

$
S: Ax + By + Cz + D = 0
$ 

(ahol $A, B, C, D \in \mathbb{R}$)