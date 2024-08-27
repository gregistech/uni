---
dg-publish: true
---
### Vektorok hosszainak (abszolút értékeinek) kiszámítása

Legyen egy vektor, melynek kezdőpontja $A$, végpontja $B$ pont. Legyenek $A$ koordinátái $(x_1, y_1)$, $B$ koordinátái pedig $(x_2, y_2)$. Ahhoz, hogy az $AB$ vektor hosszát meghatározhassuk, ki kell számolnunk iránykoordinátáit:

$AB = (x_2 - x_1, y_2 - y_1)$

$A$ irányvektor meghatározása után a Pitagorasz-tétel segítségével számíthatjuk ki a vektor hosszát, azaz vesszük az abszcissza ($x$) négyzetét, majd az ordináta ($y$) négyzetét, képezzük a kettő összegét, majd négyzetgyököt vonunk:

$|AB| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$

Láthattuk a fentiek alapján, hogy egy vektor iránykoordinátáját úgy határozhatjuk meg, ha a vektor végpontjából kivonjuk a kezdőpontot. Ahhoz, hogy ezen vektor hosszát meghatározzuk, számunkra mindegy, hogyan írjuk fel az irányvektor koordinátáit (melyik irányba), hiszen négyzetre emelést követően pozitív értéket kapunk ott is ahol egyébként negatív volt, de a precizitás érdekében feltétlenül úgy írjuk fel az iránykoordinátákat, hogy az eleget tegyen az irányvektor jelölésének!
