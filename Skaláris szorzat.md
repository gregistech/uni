---
dg-publish: true
---
A geometriában a sík két, egymással $\theta$ szöget bezáró $\mathbf{a},\mathbf{b}$ vektorának skaláris szorzata az 

$$\mathbf{a} \cdot \mathbf{b} = |\mathbf{a}|\,|\mathbf{b}|\cos \theta$$ 
valós szám. 
Két geometriai vektor skaláris szorzatát tehát úgy kapjuk meg, hogy összeszorozzuk a hosszukat és az általuk közbezárt szög koszinuszát. 

A skaláris szorzás ezek szerint kétváltozós függvény, amely a vektorpárokat a valós számokra képezi. Bár a vektorok skaláris szorzása számos tekintetben hasonlít a számok szorzására, lényeges különbség az, hogy míg két szám szorzata ismét szám, két vektor skaláris szorzata nem vektor, hanem szám (skalár; innen ered az elnevezés), így szigorúan véve ez a leképezés nem is nevezhető műveletnek. 

A skaláris szorzatot néha belső szorzatnak is nevezik. Szokásos jelölése: $\mathbf{a} \cdot \mathbf{b}, \quad \mathbf{a}\mathbf{b}, \quad (\mathbf{a},\mathbf{b}), \quad \langle \mathbf{a},\mathbf{b} \rangle.$

A skaláris szorzatnak fontos közvetlen alkalmazásai vannak a geometriában és a fizikában, igazi jelentőségét azonban az adja, hogy a skalárszorzat-fogalomnak számos általánosítása és absztrakciója van, amelyek révén alkalmazható a koordinátageometriában, a lineáris algebrában, a vektoranalízisben, a funkcionálanalízisben, az ortogonális függvénysorok elméletében, a statisztikában és a számítástechnikában is.

A széleskörű alkalmazhatóság kulcsa az a megfigyelés, hogy ha a két összeszorzandó síkvektor koordinátáival adott: 
$\mathbf{a} = [a_{1},a_{2}]$ és $\mathbf{b} = [b_{1},b_{2}],$ akkor skaláris szorzatuk épp az 
$$\mathbf{a} \cdot \mathbf{b} = a_{1}b_{1}+a_{2}b_{2}$$ 
mennyiség. Ez az összefüggés lehetővé teszi, hogy a skalárszorzat fogalmát tetszőleges n-dimenziós valós vektorterek elemeire is kiterjesszük, és az $\mathbf{a} = [a_{1},a_{2},\ldots ,a_{n}]$ és $\mathbf{b} = [b_{1},b_{2},\ldots ,b_{n}]$ n-dimenziós vektorok skalárszorzatát az 
$$\mathbf{a} \cdot \mathbf{b} =\sum_{i=1}^{n}a_{i}b_{i}=a_{1}b_{1}+a_{2}b_{2}+\cdots +a_{n}b_{n}$$ 

egyenlőséggel definiáljuk. 

Ennek révén aztán a lineáris algebrában szokásos absztrakt vektorokkal kapcsolatban is beszélhetünk olyan alapvetően geometriai jellegű fogalmakról, mint a hosszúság, a hajlásszög, az irány, a merőlegesség és a párhuzamosság, valamint a vetület. Ugyanakkor a fordított irányú kapcsolat lehetővé teszi, hogy geometriai feladatokat aritmetikai, algebrai számítások elvégzésére vezessünk vissza, ami a koordinátageometria és a geometria fizikai-műszaki alkalmazásainak az alapja.

## Motiváció és történeti háttér

Történetileg a skaláris szorzás motivációját a mechanikai munka fizikai fogalma adja. Ismert, hogy ha egy test valamilyen erő hatására a kérdéses erő irányába elmozdul, akkor az erő által végzett munka (a test mozgási energiájának növekedése) az erő és az elmozdulás szorzata. Az erő és az elmozdulás azonban egyaránt vektormennyiségek, és előfordulhat, hogy irányuk nem esik egybe. Ilyenkor az erő által végzett munka továbbra is lineáris függvénye mind az erőnek, mind az elmozdulásnak, de a munka tényleges mértékének kiszámításában csak az erőnek az elmozdulás irányába eső komponense játszik szerepet. Ha $$\theta$$ jelöli az $$\vec {F}$$ erővektor és az $$\vec {AB}$$ elmozdulásvektor hajlásszögét, akkor ez a komponens épp az erővektor $$\cos \theta$$-szorosa, így az erő által végzett munka 

$$|{\vec {F}}|\,|{\vec {AB}}|\cos \theta = \vec {F} \cdot \vec {AB}$$ 

skaláris szorzata. Az analitikus geometriában először Lagrange 1773-as, *Solutions analytiques de quelques problèmes sur les pyramides triangulaires* című művében bukkan fel a skaláris szorzat. A fogalom modern tárgyalása Gibbs 1901-es (tanítványa, Edwin Bidwell Wilson által lejegyzett) *Vector Analysis* című művében jelenik meg.

## Geometriai jelentése

Jelölje az $\vec {a}$ és $\vec {b}$ vektorok hosszát $a = |\vec {a}|$ és $b = |\vec {b}|$, illetve legyen az $\vec {a}$ és $\vec {b}$ vektorok által közrezárt szög
$$\varphi = \sphericalangle (\vec {a},\vec {b}).$$ 
Ekkor 
$$\vec {a} \cdot \vec {b} := |\vec {a}||\vec {b}|\cos \sphericalangle (\vec {a},\vec {b}) = ab\cos \varphi.$$ 

Szigorúan véve egyik tényező sem lehet a nullvektor, hiszen akkor a közrezárt szög nem definiálható. Definíció szerint, ha $\vec {a} = \vec {0}$ vagy $\vec {b} = \vec {0}$, akkor 
$$\vec {a} \cdot \vec {b} := 0$$

Ahogy szorzáskor, itt is szokás elhagyni a szorzásjelet, ha ez nem okoz félreértést:

$$\vec {a} \cdot \vec {b} = \vec {a} \vec {b}.$$ 

Ahelyett, hogy $\vec {a} \cdot \vec {a}$ írható az is, hogy $\vec {a}^{2}$ vagy $|\vec {a}|^{2}$ 

További szokásos jelölések még $\vec {a} \circ \vec {b},\ \vec {a} \bullet \vec {b}$ és $\langle \vec {a},\vec {b} \rangle.$ 

## Alapvető tulajdonságai

A skalárszorzat definíciójából közvetlenül következnek az alábbi tulajdonságok. Ha $\vec {a}$ és $\vec {b}$ párhuzamosak és egyező irányításúak, azaz $\varphi = 0^{\circ }$, akkor 
$$\vec {a} \cdot \vec {b} = ab.$$ 
Speciálisan, a skalárszorzattal kiszámítható egy vektor hossza: 
$$\vec {a} \cdot \vec {a} = |a|^{2}.$$ 

Ha $\vec {a}$ és $\vec {b}$ párhuzamosak, de ellenkező irányításúak, vagyis $\varphi = 180^{\circ }$, akkor: 
$$\vec {a} \cdot \vec {b} = -ab.$$ 
[[Skaláris szorzat merőleges vektorokkal]]

Követve azt a konvenciót, hogy a nullvektor minden vektorra merőleges, a fentieket úgy foglalhatjuk össze, hogy két vektor akkor és csak akkor merőleges, ha a szorzatuk nulla. 

Ha $\vec {a}$ és $\vec {b}$ hegyesszöget zár be, akkor 
$$\vec {a} \cdot \vec {b} > 0.$$ 
Ha $$\vec {a}$$ és $$\vec {b}$$ szöge tompaszög, akkor 

$$\vec {a} \cdot \vec {b} < 0.$$ 

Ha 

$$|\vec {a} \cdot \vec {b}| \leq |\vec {a}||\vec {b}|$$ 

(Cauchy-Schwarz-egyenlőtlenség) és 

$$|\vec {a} \cdot \vec {b}| =|\vec {a}||\vec {b}| \iff \vec {a},\vec {b}$$ 

lineárisan összefüggők. A skaláris szorzat szimmetrikus (a műveleteknél megszokott szóhasználattal: kommutatív), mivel 

$$\mathbf {a} \cdot \mathbf {b} = |\mathbf {a}|\,|\mathbf {b}|\,\cos \theta = |\mathbf {b}|\,|\mathbf {a}|\,\cos \theta = \mathbf {b} \cdot \mathbf {a}.$$ 

Egy vektor önmagával vett skaláris szorzata a vektor hosszúságának a négyzete: 

$$\mathbf {a} \cdot \mathbf {a} = |\mathbf {a}|\,|\mathbf {a}|\,\cos 0^{\circ} = |\mathbf {a}|^{2}.$$ 

Ebből következően 

$$\mathbf {a} \cdot \mathbf {a} \geq 0$$ 

és 

$$\mathbf {a} \cdot \mathbf {a} = 0$$ 

akkor és csak akkor, ha 

$$\mathbf {a} = \mathbf {0}.$$ 

Az ilyen leképezéseket pozitív definitnek nevezzük. Minden argumentumában homogén: 

$$(r\vec {a}) \cdot \vec {b} = r (\vec {a} \cdot \vec {b}) = \vec {a} \cdot (r\vec {b})$$ 

minden $$\vec {a}$$ és $$\vec {b}$$ vektorra és minden $$r \in \mathbb {R}$$ valós számra. Minden argumentumában additív: 

$$\vec {a} \cdot (\vec {b} + \vec {c}) = \vec {a} \cdot \vec {b} + \vec {a} \cdot \vec {c}$$ 

és 

$$(\vec {a} + \vec {b}) \cdot \vec {c} = \vec {a} \cdot \vec {c} + \vec {b} \cdot \vec {c}$$ 

minden $$\vec {a},\vec {b}, \vec {c}$$ vektorra. Mivel a skaláris szorzat nem a tényezőkkel azonos dimenziójú vektor, hanem skalár, azért valódi asszociativitás nem értelmezhető. 

Általában 

$$(\vec {a} \cdot \vec {b}) \vec {c} \neq \vec {a} (\vec {b} \cdot \vec {c})$$ 

hiszen az első szorzatban egy $$\vec {c}$$, a második szorzatban egy $$\vec {a}$$ irányú vektort kapunk.

## Bilinearitás

A skalárszorzat bilineáris, azaz mindkét változójában lineáris. Ez azt jelenti, hogy tetszőleges $$\lambda$$ skalárra és $$\mathbf {a},\mathbf {b},\mathbf {c}$$ vektorokra (B1) 

$$(\lambda \mathbf {a}) \cdot \mathbf {b} = \lambda (\mathbf {a} \cdot \mathbf {b})$$ 

és (B2) 

$$(\mathbf {a} + \mathbf {b}) \cdot \mathbf {c} = (\mathbf {a} \cdot \mathbf {c}) + (\mathbf {b} \cdot \mathbf {c})$$ 

. A szimmetriatulajdonság miatt ezekből már következik, hogy (B3) 

$$\mathbf {a} \cdot \lambda \mathbf {b} = \lambda (\mathbf {a} \cdot \mathbf {b})$$ 

és (B4) 

$$\mathbf {a} \cdot (\mathbf {b} + \mathbf {c}) = (\mathbf {a} \cdot \mathbf {b}) + (\mathbf {a} \cdot \mathbf {c}).$$ 

(B1) közvetlenül következik a definícióból, hiszen 

$$(\lambda \mathbf {a}) \cdot \mathbf {b} = |\lambda \mathbf {a}|\,|\mathbf {b}|\cos \theta =\lambda |\mathbf {a}|\,|\mathbf {b}|\cos \theta = \lambda (\mathbf {a} \cdot \mathbf {b}).$$ 

A bilinearitás a (valós) skaláris szorzat egyik legfontosabb tulajdonsága amellett, hogy kiszámítható vele egy vektor normája (hossza). Ezeken alapul a skaláris szorzás alkalmazása a lineáris algebrában.

## Példák

Legyen $$|\vec {a}| = 5$$ és $$|\vec {b}| = 3$$! Ekkor a skalárszorzat a közrezárt szögtől függ: Ha a bezárt szög 0 fok, akkor 

$$\cos 0^{\circ} = 1,$$ 

így 

$$\vec {a} \cdot \vec {b} = 5 \cdot 3 \cdot \cos 0^{\circ} = 15.$$ 

Ha a bezárt szög 60 fok, akkor 

$$\cos 60^{\circ} = {\tfrac {1}{2}},$$ 

ezért 

$$\vec {a} \cdot \vec {b} = 5 \cdot 3 \cdot \cos 60^{\circ} = 7{,}5.$$ 

Ha a bezárt szög 90 fok, akkor 

$$\cos 90^{\circ} = 0,$$ 

emiatt 

$$\vec {a} \cdot \vec {b} = 5 \cdot 3 \cdot \cos 90^{\circ} = 0.$$ 

Bármely lineáris térben értelmezhető egy adott $$A$$ bázishoz tartozó skalárszorzat a következőképp. Ha $$\mathbf{x}$$ és $$\mathbf{y}$$ vektor az $$A$$ bázisban felírható:

$$\mathbf{x} = x_{1}\mathbf{a}_{1}+x_{2}\mathbf{a}_{2}+\dots +x_{N}\mathbf{a}_{N}$$ 

és 

$$\mathbf{y} = y_{1}\mathbf{a}_{1}+y_{2}\mathbf{a}_{2}+\dots +y_{N}\mathbf{a}_{N},$$ 

akkor az ezen bázis által meghatározott skalárszorzat:

$$\langle \mathbf{x},\mathbf{y} \rangle_{A} = x_{1}y_{1}+x_{2}y_{2}+\dots +x_{N}y_{N}.$$

## Geometriai vonatkozások

Az euklideszi geometriában szoros összefüggés áll fenn a skalárszorzat és a hosszak, valamint a szögek között. Egy $$\mathbf{a}$$ vektorra 

$$\mathbf{a} \cdot \mathbf{a}$$ 

a hosszának (abszolút értékének) négyzete, és ha $$\mathbf{b}$$ egy másik vektor, akkor

$$\mathbf{a} \cdot \mathbf{b} = |\mathbf{a}|\,|\mathbf{b}|\,\cos \theta $$ 

ahol $$|\mathbf{a}|$$ és $$|\mathbf{b}|$$ jelöli az $$\mathbf{a}$$ és $$\mathbf{b}$$ vektor hosszát, $$\theta$$ pedig az általuk bezárt szög. Mivel $$|\mathbf{a}| \cdot \cos \theta$$ az $$\mathbf{a}$$ vektornak $$\mathbf{b}$$-re való vetülete, a skalárszorzatot geometriailag úgy lehet értelmezni, mint $$\mathbf{a}$$-nak $$\mathbf{b}$$ irányába eső komponensének és $$\mathbf{b}$$-nek a szorzatát. Mivel 

$$\cos 90^{\circ}$$ 

nullával egyenlő, két egymásra merőleges vektor szorzata mindig nulla. Ha $$\mathbf{a}$$ és $$\mathbf{b}$$ vektor hossza egységnyi (vagyis egységvektorok), skalárszorzatuk egyszerűen közbezárt szögük koszinuszát adja. Így a két vektor közötti szög:

$$\theta = \arccos \left({\frac {\mathbf{a} \cdot \mathbf{b}}{|\mathbf{a}|\,|\mathbf{b}|}}\right).$$ 

A fenti tulajdonságokat időnként a skalárszorzat definíciójaként is használják, különösen 2 és 3 dimenziós vektorok esetében. Több dimenziós esetben a képletet a szög értelmezéseként lehet használni.

## Példa számítások

Az: $$\mathbf{a} = \begin{pmatrix}1\\2\\3\end{pmatrix}$$  és $$\mathbf{b} = \begin{pmatrix}-7\\8\\9\end{pmatrix}$$  vektorok hossza:

$$|\mathbf{a}| = \sqrt{1^{2}+2^{2}+3^{2}}= \sqrt{14}\approx 3{,}74$$ 

és 

$$|\mathbf{b}|={\sqrt{(-7)^{2}+8^{2}+9^{2}}}={\sqrt{194}}\approx 13{,}93.$$ 

A közrezárt szög koszinusza:

$$\cos \sphericalangle (\mathbf{a},\mathbf{b})={\frac {36}{{\sqrt {14}}\cdot {\sqrt {194}}}}\approx 0{,}691.$$ 

Tehát 

$$\sphericalangle (\mathbf{a},\mathbf{b})=\arccos \left({\frac {36}{{\sqrt {14}}\cdot {\sqrt {194}}}}\right)\approx 46{,}3^{\circ}.$$ 

## Geometriai vonatkozás bizonyítása

Vegyük $$\mathbb{R}^{n}$$ tetszőleges elemét $$\mathbf{v} = v_{1}\mathbf{\hat{e}}_{1}+v_{2}\mathbf{\hat{e}}_{2}+\dots + v_{n}\mathbf{\hat{e}}_{n}.$$ A Pitagorasz-tétel egymást követő alkalmazásával 

$$\mathbf{v}|^{2}=v_{1}^{2}+v_{2}^{2}+...+v_{n}^{2}$$ 

De ez ugyanaz, mint a 

$$\mathbf{v} \cdot \mathbf{v} = v_{1}^{2}+v_{2}^{2}+...+v_{n}^{2}$$ 

ebből arra a következtetésre jutunk, hogy egy $$\mathbf{v}$$ vektor önmagával vett skaláris szorzata a vektor hosszának a négyzetét adja. 

Lemma: $$\mathbf{v} \cdot \mathbf{v} = |\mathbf{v}|^{2}.$$ Most vegyünk két vektort az origóban: $$\mathbf{a}$$-t és $$\mathbf{b}$$-t, melyek $$\theta$$ szöget zárnak közre. Definiáljunk egy harmadik, $$\mathbf{c}$$ vektort:

$$\mathbf{c} \ {\stackrel {\mathrm {def} }{=}}\ \mathbf{a} -\mathbf{b}.$$ 

Ezzel alkottunk egy háromszöget $$\mathbf{a}$$, $$\mathbf{b}$$ és $$\mathbf{c}$$ oldalakkal. A koszinusztételt felírva:

$$|\mathbf{c}|^{2}=|\mathbf{a}|^{2}+|\mathbf{b}|^{2}-2|\mathbf{a}||\mathbf{b}|\cos \theta .$$ 

A lemma alapján a hosszak négyzetének helyébe skaláris szorzást helyettesítve kapjuk, hogy 

$$\mathbf{c} \cdot \mathbf{c} = \mathbf{a} \cdot \mathbf{a} + \mathbf{b} \cdot \mathbf{b} -2|\mathbf{a}||\mathbf{b}|\cos \theta .$$ 

(1) De mivel $$\mathbf{c} \equiv \mathbf{a} - \mathbf{b}$$, azt is tudjuk, hogy 

$$\mathbf{c} \cdot \mathbf{c} = (\mathbf{a} - \mathbf{b}) \cdot (\mathbf{a} - \mathbf{b}),$$ 

ami a disztributív tulajdonság miatt 

$$\mathbf{c} \cdot \mathbf{c} = \mathbf{a} \cdot \mathbf{a} + \mathbf{b} \cdot \mathbf{b} - 2(\mathbf{a} \cdot \mathbf{b}).$$ 

(2) A két $$\mathbf{c} \cdot \mathbf{c}$$ egyenletet – (1) és (2) – egyenlővé téve 

$$\mathbf{a} \cdot \mathbf{a} + \mathbf{b} \cdot \mathbf{b} - 2(\mathbf{a} \cdot \mathbf{b}) = \mathbf{a} \cdot \mathbf{a} + \mathbf{b} \cdot \mathbf{b} - 2|\mathbf{a}||\mathbf{b}|\cos \theta .$$ 

Kivonunk mindkét oldalról $$\mathbf{a} \cdot \mathbf{a} + \mathbf{b} \cdot \mathbf{b}$$-t és osztunk $$-2$$-vel. Marad 

$$\mathbf{a} \cdot \mathbf{b} = |\mathbf{a}||\mathbf{b}|\cos \theta .$$ 

Q.E.D.

## Merőlegesség és merőleges vetítés

Két vektor, a $$\vec {a}$$ és $$\vec {b}$$ pontosan akkor merőleges, ha skalárszorzatuk nulla:

$$\vec {a} \perp \vec {b} \iff \vec {a} \cdot \vec {b} = 0.$$

$$\vec {b}$$ merőleges vetülete az $$\vec {a} \neq \vec {0}$$ által megadott irányra:

$$\vec {b}_{\vec {a}} = b_{a}{\frac {\vec {a}}{|\vec {a}|}}=\left({\frac {\vec {b} \cdot \vec {a}}{|{\vec {a}}|^{2}}}\right)\,\vec {a}.$$ 

A vetület az a vektor, melynek a végpontja a $$\vec {b}$$ vektor egyenesére az $$\vec {a}$$ vektor végpontjából bocsátott merőleges talppontja. A $$\vec {b} - \vec {b}_{\vec {a}}$$ vektor merőleges az $$\vec {a}$$ vektorra. Ha $$\vec {a}$$ egységvektor, akkor a képlet egyszerűbb:

$$\vec {b}_{\vec {a}}=b_{a}{\vec {a}}=({\vec {b}} \cdot {\vec {a}})\,{\vec {a}}.$$ 

## Kapcsolat a vektoriális szorzással

A vektoriális szorzás egy másik művelet, aminek eredménye szintén vektor. A vektoriális szorzat merőleges a tényezők által kifeszített síkra, és hossza megegyezik a tényezők által kifeszített paralelogramma területével. A kétféle szorzást a következő szabályok kapcsolják össze:

$$(\vec {a} \times \vec {b}) \cdot \vec {c} = \vec {a} \cdot (\vec {b} \times \vec {c}).$$ 

$$(\vec {a} \times \vec {b}) \cdot \vec {c} = -(\vec {b} \times \vec {a}) \cdot \vec {c}$$ 

$$(\vec {a} \times \vec {b}) \cdot \vec {a} = (\vec {a} \times \vec {b}) \cdot \vec {b} = 0$$ 

$$(\vec {a} \times \vec {b}) \cdot (\vec {a} \times \vec {b}) = (\vec {a} \cdot \vec {a})(\vec {b} \cdot \vec {b}) - (\vec {a} \cdot \vec {b})^{2}.$$ 

Az első két szabály írja le a vegyes szorzatot, ami az $$\vec {a},\vec {b},\vec {c}$$ vektorok által kifeszített paralelepipedon előjeles térfogatával egyezik meg.

## Alkalmazások

### A geometriában

A skaláris szorzással egyszerűbben bizonyíthatók tételek szögekről és távolságokról. Például a koszinusztétel:

$$c^{2} = a^{2} + b^{2} - 2ab\cos \gamma.$$ 

Bizonyítás: A bevezetett vektorok elhelyezkedése szerint 

$$\mathbf{c} = -\mathbf{b} + \mathbf{a}.$$ 

A hossz négyzetre emelésével:

$$|\mathbf{c}|^{2}=\mathbf{c} \cdot \mathbf{c} = (\mathbf{a} - \mathbf{b}) \cdot (\mathbf{a} - \mathbf{b}) = \mathbf{a} \cdot \mathbf{a} - 2\,\mathbf{a} \cdot \mathbf{b} + \mathbf{b} \cdot \mathbf{b} = |\mathbf{a}|^{2} + |\mathbf{b}|^{2} - 2\,\mathbf{a} \cdot \mathbf{b}$$ 

és így 

$$c^{2} = a^{2} + b^{2} - 2ab\cos \gamma.$$ 

### Az analitikus geometriában

A skaláris szorzással ábrázolható egy egyenes egy síkban, egy sík egy térben, vagy általánosabban, egy hipersík bármely dimenziós térben:

$$(\vec {x} - \vec {p}) \cdot \vec {n} = 0,$$

ahol $$\vec {p}$$ támaszvektor és $$\vec {n}$$ normálvektor. Az adott egyenes, sík, hipersík pontjai azok a pontok, amelyek megoldják ezt az egyenletet. Eltérően a paraméteres alaktól, itt nincsenek paraméterek.

### A lineáris algebrában

A skalárszorzás segítségével egy lineáris egyenletrendszer minden egyenlete hipersíknak tekinthető. Legyen a rendszerben $$m$$ egyenlet, a változók száma pedig $$n$$! Ekkor 

$$(\vec {a}_{i} \cdot \vec {x} = b_{i})$$ 

úgy, hogy 

$$\vec {a}_{i} = \begin{pmatrix}a_{i1}\\a_{i2}\\\vdots \\a_{in}\end{pmatrix}$$ 

és 

$$\vec {x} = \begin{pmatrix}x_{1}\\x_{2}\\\vdots \\x_{n}\end{pmatrix},$$ 

így a lineáris egyenletrendszer megoldáshalmaza hipersíkok metszeteként definiálható.

### Fizikai alkalmazások

A fizikában sok mennyiséget skaláris szorzattal definiálnak, mint például a $$W$$ munkát:

$$W = \vec {F} \cdot \vec {s} = |\vec {F}||\vec {s}| \cos \varphi = F_{s} \cdot s = F \cdot h$$

ahol az $$\vec {F}$$ erő és az $$\vec {s}$$ út vektormennyiségek. Itt $$F_{s}$$ az erőnek az út irányába mutató komponense, $$h$$ pedig az út erő irányú komponense. Példa: Egy $$F$$ tömegű járművet $$A$$ és $$B$$ ferde síkján át mozgatják. A $$W$$ munkát így számolhatjuk:

$$ W = \vec {F} \cdot \vec {s} = F \cdot h = F \cdot s \cdot \cos \varphi = 5\,\mathrm {N} \cdot 3\,\mathrm {m} \cdot \cos 63^{\circ} = 6{,}81\,\mathrm {J}.$$

## Általánosítás

A fenti tulajdonságokat tekintve a skalárszorzat általánosítható tetszőleges valós vagy komplex vektortérre. A skaláris szorzat egy függvény, ami két vektorhoz egy testelemet (skalárt) rendel, a megadott tulajdonságoknak megfelelően. Lehetséges, hogy több bilineáris forma is megfelel skaláris szorzatként. Komplex számtest fölött a definíciót módosítani kell, hogy a skaláris szorzat pozitív definit legyen, mivel általában nincs olyan komplex bilineáris forma, ami pozitív definit és szimmetrikus. Az általánosított esetben a jelölések is különböznek az alapesettől. A vektorterek elemein nem jelölik, hogy vektorok. 

Az $$x$$ és $$y$$ vektorok skaláris szorzatát nem szorzóponttal, hanem hegyes zárójellel jelzik: 

$$\langle x,y \rangle.$$ 

További jelölések: főleg a kvantummechanikában $$\langle x|y \rangle,$$ lásd Bra-Ket-jelölés; 

$$(x,y)$$ és 

$$(x|y)$$.

### Definíciók

Egy $$V$$ valós vektortéren egy skaláris szorzás egy 

$$\langle \cdot , \cdot \rangle : V \times V \to \mathbb{R},$$ 

szimmetrikus pozitív definit bilineáris alak, vagyis tetszőleges $$x,y,z \in V$$ és $$\lambda \in \mathbb {R}$$ esetén teljesülnek:

mindkét argumentumban lineáris:

$$\langle x+y,z \rangle = \langle x,z \rangle + \langle y,z \rangle$$ 

$$\langle x,y+z \rangle = \langle x,y \rangle + \langle x,z \rangle$$ 

$$\langle \lambda x,y \rangle = \lambda \langle x,y \rangle$$ 

$$\langle x,\lambda y \rangle = \lambda \langle x,y \rangle$$ 

szimmetrikus: $$\langle x,y \rangle = \langle y,x \rangle$$ 

pozitív definit:

$$\langle x,x \rangle \geq 0$$ 

$$\langle x,x \rangle = 0$$ pontosan akkor, ha $$x = 0$$.

Egy $$V$$ komplex vektortéren egy skaláris szorzás egy 

$$\langle \cdot , \cdot \rangle : V \times V \to \mathbb{R},$$ 

hermitikus sesquilinearis forma, vagyis tetszőleges $$x,y,z \in V$$ és $$\lambda \in \mathbb {C}$$ esetén teljesülnek:

sesquilinearis:

$$\langle x+y,z \rangle =\langle x,z \rangle + \langle y,z \rangle$$ 

$$\langle \lambda x,y \rangle = \bar{\lambda} \langle x,y \rangle$$ (első argumentumban féllineáris)

$$\langle x,y+z \rangle = \langle x,y \rangle + \langle x,z \rangle$$ 

$$\langle x,\lambda y \rangle = \lambda \langle x,y \rangle$$ (második argumentumban lineáris)

hermitikus: $$\langle x,y \rangle = \overline{\langle y,x \rangle}$$ 

pozitív definit:

$$\langle x,x \rangle \geq 0$$ (Az, hogy $$\langle x,x \rangle$$ valós, következik a második feltételből)

$$\langle x,x \rangle = 0$$ akkor és csak akkor, ha $$x = 0$$.

Egy skaláris szorzattal ellátott valós vagy komplex vektorteret skalárszorzatosa térnek vagy prehilbert-térnek neveznek. Skalárszorzattal ellátott véges valós vektortereket neveznek euklideszi vektortereknek; komplex esetben unitér terekről beszélnek. Így beszélnek euklideszi és unitér skalárszorzatokról is. Az euklideszi skalárszorzat kifejezést használják a fent bevezetett skalárszorzásra és a később leírt standard skalárszorzatra is $$\mathbb {R}^{n}$$-ben.

### Megjegyzések

Gyakran minden szimmetrikus bilineáris alakot, illetve hermitikus sesquilinearis formát skaláris szorzatnak neveznek; ezzel a szóhasználattal a fenti definíciók pozitív definit skalárszorzatokat írnak le. A fent leírt axiómarendszerek nem minimálisak. A valós esetben a szimmetria miatt az első argumentumban való linearitásból következik, hogy a másik argumentumban is lineáris. Hasonlóan, a komplex esetben az Hermite-tulajdonságból és az első argumentumban való semilinearitásból következik a másik argumentumban való linearitás, és fordítva. Komplex esetben a skaláris szorzatot időnként úgy definiálják, hogy az első argumentumban lineáris és a második argumentumban semilinearis. Ezt a verziót használják inkább a matematikában, különösen az analízisben; míg a fizikában főként a fenti definíciót részesítik előnyben. Lásd még: Bra- és Ket-vektorok. A két definíció abban különbözik, hogy másként hat a skalárszorzat a homogenitásra:

$$x,y \in V$$ és $$\lambda \in \mathbb{C}$$ 

$$\langle \lambda x,y \rangle = \lambda \langle x,y \rangle $$

és

$$\langle x,\lambda y \rangle = \bar{\lambda} \langle x,y \rangle.$$ 

Az additivitás mindkét verzióban ugyanaz. Ugyanúgy egyeznek a normák is. Egy prehilbert tér, ami teljes a skalárszorzat által indukált normára, Hilbert-tér. A komplex és a valós eset közötti különbség abból adódik, hogy egy komplex hermitikus sesquilinearis forma a valósban megfelel egy szimmetrikus bilineáris formának.

### Példák

### Standard skalárszorzat $$\mathbb{R}^{n}$$ és $$\mathbb{C}^{n}$$ terekben

Az euklideszi skalárszorzat Descartes-koordinátákban való ábrázolásából kiindulva definiáljuk a skalárszorzatot az $$\mathbb{R}^{n}$$ térben:

$$\langle x,y \rangle = \sum_{i=1}^{n} x_{i}y_{i} = x_{1}y_{1} + x_{2}y_{2} + \dots + x_{n}y_{n}.$$ 

ahol $$x,y \in \mathbb{R}^{n}$$. A fent definiált skalárszorzat az euklideszi térben megfelel az $$n = 3$$ speciális esetnek. A komplex $$\mathbb{C}^{n}$$ $$n$$ dimenziós vektortér esetén a standard skalárszorzat 

$$\langle x,y \rangle = \sum_{i=1}^{n} \bar{x}_{i}y_{i} = \bar{x}_{1}y_{1} + \bar{x}_{2}y_{2} + \dots + \bar{x}_{n}y_{n},$$ 

ahol $$x,y \in \mathbb{C}^{n}$$, és a felülvonás a komplex konjugálást jelenti. A matematikában gyakran az alternatív definíciót használják, ahol a második argumentumban konjugálnak:

$$\langle x,y \rangle = \sum_{i=1}^{n} x_{i} \bar{y}_{i} = x_{1} \bar{y}_{1} + x_{2} \bar{y}_{2} + \dots + x_{n} \bar{y}_{n}.$$ 

A standard skalárszorzat $$\mathbb{R}^{n}$$-ben, illetve $$\mathbb {C}^{n}$$-ben kifejezhető mátrixszorzásként, ahol a vektorokat $$n \times 1$$-es mátrixként értelmezzük. Valós esetben 

$$\langle x,y \rangle = x^{T}y = y^{T}x,$$ 

ahol $$x^{T}$$ az $$x$$ vektorból transzponált sorvektor. Komplex esetben (az első argumentumban konjugáló típus):

$$\langle x,y \rangle = x^{H}y,$$ 

ahol $$x^{H}$$ az $$x$$-hez adjungált sorvektor.

### Általánosított skalárszorzatok $$\mathbb{R}^{n}$$ és $$\mathbb{C}^{n}$$ terekben

Általánosabban, bármely szimmetrikus és pozitív definit $$A$$ mátrix esetén az 

$$\langle x,y \rangle_{A} = x^{T}Ay = \langle x,Ay \rangle$$  

mátrixszorzat szintén skaláris szorzat. Hasonlóan, komplex esetben bármely hermitikus pozitív definit $$A$$ mátrix esetén az 

$$\langle x,y \rangle_{A} = x^{H}A y = \langle x,Ay \rangle$$ 

mátrixszorzat is skaláris szorzat. A hegyes zárójelek a standard skalárszorzatot, az $$A$$ indexszel ellátott hegyes zárójelek az $$A$$ mátrix segítségével definiált skalárszorzatot jelölik. Az $$\mathbb{R}^{n}$$, illetve $$\mathbb{C}^{n}$$ terekben minden skalárszorzat ábrázolható ezen a módon.

### Skalárszorzatok függvényekhez

A valós értékű, $$[a,b]$$ intervallumon értelmezett folytonos függvények végtelen dimenziós vektortére esetén értelmezhető az $$L^{2}$$-skalárszorzat:

$$\langle f,g \rangle_{L^{2}} = \int_{a}^{b} f(x)g(x) \,\mathrm{d}x,$$

minden $$f,g \in C^{0}([a,b],\mathbb{R})$$ függvényre. A folytonosság követelménye gyengíthető, így az $$L^{2}$$-skalárszorzat lépcsőfüggvények esetén is jóldefiniált. Differenciálható függvények esetén definiálható a $$H^{1}$$-skalárszorzat is:

$$\langle f,g \rangle _{H^{1}} = \langle f,g \rangle _{L^{2}} + \langle f',g' \rangle _{L^{2}}$$ 

minden $$f,g $$  $$\in C^{1}([a,b],\mathbb{R})$$ esetén. A differenciálhatóság követelménye itt is gyengíthető, lásd Szoboljev-terek. Mindezek a skalárszorzatok kiterjeszthetők komplex értékű esetekre is:

$$\langle f,g \rangle_{L^{2}} = \int_{a}^{b} f(x)\overline{g(x)}\,\mathrm{d}x.$$

### Frobenius-skalárszorzat mátrixok esetén

A valós $$(m \times n)$$ mátrixok $$\mathbb{R}^{m \times n}$$ terén definiálható 

$$\langle A,B \rangle = \operatorname{trace}(A^{T}B) = \sum_{i=1}^{m}\sum_{j=1}^{n} a_{ij}b_{ij}$$ 

skalárszorzat, ahol $$A,B \in \mathbb{R}^{m \times n}$$. 

A komplex $$ (m \times n) $$-es mátrixok $$\mathbb{C}^{m \times n}$$ terében 

$$\langle A,B \rangle = \operatorname{trace}(A^{H}B) = \sum_{i=1}^{m}\sum_{j=1}^{n} \bar{a}_{ij}b_{ij}$$ 

szintén skalárszorzat, ahol $$A,B \in \mathbb{C}^{m \times n}$$. Ezeket a skalárszorzatokat Frobenius-skalárszorzatnak, és az általuk definiált normát Frobenius-normának nevezzük.

### Norma, szög és ortogonalitás

Egy euklideszi térben definiált vektor hosszának általános vektorterekben a skalárszorzat által indukált norma felel meg. Az indukált norma:

$$\|x\| = \sqrt{ \langle x,x \rangle }$$

ami megfelel az euklideszi térben a standard skalárszorzatból számítható skalárszorzatnak. A normaaxiómák által megkövetelt háromszög-egyenlőtlenség a Cauchy-Schwarz-egyenlőtlenségből következik:

$$\left| \langle x,y \rangle \right|^{2} \leq \langle x,x \rangle \cdot \langle y,y \rangle.$$

Ha $$x,y \neq 0,$$ akkor ez az egyenlőtlenség átalakítható úgy, mint:

$$\left|{\frac {\langle x,y \rangle }{{\sqrt {\langle x,x \rangle }}\cdot {\sqrt {\langle y,y \rangle }}}}\right| \leq 1.$$

Ebből valós vektorterekben kiszámítható a közrezárt szög koszinusza, amivel meghatározható a közrezárt szög is:

$$\varphi = \arccos \left({\frac {\langle x,y \rangle }{{\sqrt {\langle x,x \rangle }}\cdot {\sqrt {\langle y,y \rangle }}}} \right).$$

Az így kiszámított szög $0^{\circ}$ és $180^{\circ}$ közé esik, tehát $0$ és $$\pi$$ közé. Komplex vektorterek esetében többféle definíció is létezik. Általános vektorterekben, ha a skaláris szorzat nullával egyenlő, akkor a vektorok ortogonálisak (ez a merőlegesség általánosítása):

$$x \perp y \Longleftrightarrow \langle x,y \rangle = 0.$$

### Ábrázolás mátrixszal

Legyen $$V$$ egy $$n$$ dimenziós vektortér, $$B = (b_{1},\ldots,b_{n})$$ egy bázisa $$V$$-nek! Ekkor minden $$\langle \cdot , \cdot \rangle$$ skalárszorzat leírható egy $$n \times n$$-es mátrixszal, ami a skaláris szorzat Gram-mátrixa, melynek szokásos jelölése $$G$$. Ez írja le a bázisvektorok skalárszorzatait:

$$G = (g_{ij})_{i,j=1,\ldots,n}$$ 

ahol $g_{ij} = \langle b_{i},b_{j} \rangle $ minden $$i,j=1,\ldots,n$$ esetén. A skaláris szorzat kifejezhető a bázis segítségével: Ha az $$x,y \in V$$ vektorok a $$B$$ bázisban úgy vannak felírva, mint:

$$x = \sum_{i=1}^{n} x_{i}b_{i}$$ 

és 

$$y = \sum_{j=1}^{n} y_{j}b_{j},$$ 

így valós esetben

$$\langle x,y \rangle = \left\langle \sum \limits_{i=1}^{n}x_{i}b_{i},\sum \limits_{j=1}^{n}y_{j}b_{j}\right\rangle = \sum \limits_{i=1}^{n}\sum \limits_{j=1}^{n}x_{i}y_{j}\langle b_{i},b_{j} \rangle = \sum \limits_{i,j=1}^{n}x_{i}y_{j}g_{ij}.$$

Jelölje most $$x_{B},y_{B} \in \mathbb{R}^{n}$$ a koordinátavektorokat:

$$x_{B} = \begin{pmatrix}x_{1}\\\vdots \\x_{n}\end{pmatrix}$$ 

és 

$$y_{B} = \begin{pmatrix}y_{1}\\\vdots \\y_{n}\end{pmatrix},$$ 

így teljesül továbbá, hogy

$$\langle x,y \rangle = \sum_{i,j=1}^{n}x_{i}g_{ij}y_{j} = \begin{pmatrix}x_{1}&\dots &x_{n}\end{pmatrix} \begin{pmatrix}g_{11}&\dots &g_{1n}\\\vdots &\ddots &\vdots \\g_{n1}&\dots &g_{nn}\end{pmatrix} \begin{pmatrix}y_{1}\\\vdots \\y_{n}\end{pmatrix} = x_{B}^{T}Gy_{B},$$

ahol a mátrixszorzásból egy $$(1\times 1)$$-es mátrix adódik, azaz egy skalár. Itt $$x_{B}^{T}$$ az $$x_{B}$$ oszlopvektorból transzponált sorvektor. Komplex esetben hasonlóan:

$$\langle x,y \rangle = \sum_{i,j=1}^{n} \bar{x}_{i}g_{ij}y_{j} = \begin{pmatrix} \bar{x}_{1}&\dots &\bar{x}_{n}\end{pmatrix} \begin{pmatrix}g_{11}&\dots &g_{1n}\\\vdots &\ddots &\vdots \\g_{n1}&\dots &g_{nn}\end{pmatrix} \begin{pmatrix}y_{1}\\\vdots \\y_{n}\end{pmatrix} = x_{B}^{H}Gy_{B},$$

ahol a felülvonás a komplex konjugálást jelenti, és $$x_{B}^{H}$$ az $$x_{B}$$ oszlopvektorhoz adjungált sorvektor. Ha $$B$$ ortonormált bázis, azaz 

$$\langle b_{i},b_{i} \rangle = 1$$ 

minden $$i$$-re, és $$\langle b_{i},b_{j} \rangle = 0$$ 

minden $$i \neq j$$ esetén, akkor a $$G$$ Gram-mátrix az egységmátrix, és 

$$\langle x,y \rangle = \sum_{i=1}^{n}x_{i}y_{i}=x_{B}^{T}y_{B}$$ 

valós esetben,

$$\langle x,y \rangle = \sum_{i=1}^{n}{\overline {x}}_{i}y_{i}=x_{B}^{H}y_{B}$$ 

komplex esetben. Ortonormált bázis esetén az $$x$$ és $$y \in V$$ vektorok skalárszorzata megfelel az $$x_{B}$$ és $$y_{B} \in \mathbb{R}^{n}$$  illetve $$\mathbb {C}^{n}$$ koordinátavektorok standard skalárszorzatának.

## További általánosítás

A pozitív definit követelmény eltávolításával, de a szimmetria megtartásával pszeudo-skalárszorzatokhoz jutunk. Erre példa a speciális relativitáselméletben a Minkowski-vektortér, ami a gravitációelméletben érintőtérként is fellép.

![[Dot-product-3.1.svg]]
![[Dot-product-3.2.svg]]
![[Dot-product-3.3.svg]]
![[Dot-product-4.svg]]
![[Dot_Product.svg]]
![[Dot_product_cosine_rule.svg]]
![[Dot_product_distributive_law.svg]]
![[Inner-product-angle.svg]]
![[Skal%C3%A1rszorzat-munka.svg]]
