---
dg-publish: true
---
### Vektoriális szorzat

A vektoriális szorzat egy kizárólag három és hét dimenzióban értelmezhető belső szorzat. Eredete a skaláris szorzathoz hasonlóan fizikai: elsősorban a forgatónyomaték kezelésében bukkan fel, de később több más területen is kényelmesnek bizonyult a használata. A definíciója is ennek megfelelően elsősorban technikai jellegű. Legyen ${\vec {a}}$ és ${\vec {b}}$ két vektor. Ekkor hozzájuk rendelhető egy harmadik ${\vec {c}}$ vektor a következő szabályok szerint:

\[
{\vec {c}}=0,
\]
ha ${\vec {a}}||{\vec {b}}$;

\[
{\vec {c}} \text{ maximális, ha a vektorok merőlegesek egymásra};
\]

a szorzat egyenesen arányos a ${\vec {a}}$ és ${\vec {b}}$ hosszával. A három vektor úgy helyezkedik el egymáshoz képest, mint a koordináta-rendszer x, y és z tengelyei. Az első két feltételt a vektorok által bezárt szög szinusza is kielégíti, így a harmadik feltétellel együtt a skaláris szorzathoz hasonlóan a 

\[
{\vec {a}}\times {\vec {b}}=a\cdot b\cdot \sin \phi 
\]

képletet írhatjuk fel. Ebben nincsen benne a szorzatvektor iránya, úgyhogy azt továbbra is külön fel kell írnunk. A vektoriális szorzat nem asszociatív, de ez nem meglepő. Még kevésbé meglepő, hogy nem kommutatív, viszont antikommutatív, azaz 

\[
{\vec {a}}\times {\vec {b}}=-{\vec {b}}\times {\vec {a}}.
\]

A vektorok összeadására nézve disztributív. A tér merőleges bázisvektorai esetén érvényes összefüggések:

\[
{\vec {e}}_{1}\times {\vec {e}}_{2}={\vec {e}}_{3},
\]
\[
{\vec {e}}_{2}\times {\vec {e}}_{3}={\vec {e}}_{1},
\]
\[
{\vec {e}}_{3}\times {\vec {e}}_{1}={\vec {e}}_{2},
\]

ezeket a koordinátás alak kiszámításakor használjuk ki. A fenti tulajdonságok alapján levezethető a vektorok szorzatára vonatkozó számítási módszer: Ha 

\[
{\vec {a}}\times {\vec {b}}={\vec {c}},
\]

akkor

\[
{\vec {c}}_{1}={\vec {a}}_{2}{\vec {b}}_{3}-{\vec {a}}_{3}{\vec {b}}_{2}
\]

\[
{\vec {c}}_{2}={\vec {a}}_{3}{\vec {b}}_{1}-{\vec {a}}_{1}{\vec {b}}_{3}
\]

\[
{\vec {c}}_{3}={\vec {a}}_{1}{\vec {b}}_{2}-{\vec {a}}_{2}{\vec {b}}_{1}.
\]

Például az 

\[
{\vec {a}}=(2,5,-2)
\]
és 
\[
{\vec {b}}=(3,-4,-1)
\]

vektorok vektoriális szorzata:

\[
{\vec {c}}_{1}=5\cdot (-1)-(-2)\cdot (-4)=-5-8=-13,
\]

\[
{\vec {c}}_{2}=(-2)\cdot 3-2\cdot (-1)=-6+2=-4,
\]

\[
{\vec {c}}_{3}=2\cdot (-4)-5\cdot 3=-8-15=-23.
\]

Skaláris szorzással ellenőrizhetjük, hogy e vektor mindkettő tényezőre merőleges.