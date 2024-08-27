---
dg-publish: true
---
$$
\begin{array}{|l|l|}
\hline
\text{Mértani sorozat} & a_n = a_1 \cdot q^{n-1} \\
\hline
\text{Mértani közép} & \left|a_n = \sqrt{a_{n-1} a_{n+1}}\right| \\
\hline
\text{Mértani sorozat összege} & s_n = a_1 \frac{q^n - 1}{q - 1} \text{, ha } q \neq 1 \\
\hline
\text{Az első n pozitív egész szám négyzetének összege} & 1 + q + q^2 + \ldots = \sum_{k=0}^{\infty} q^k = \frac{1}{1-q} \text{, ha } |q| < 1 \\
\hline
\end{array}
$$

[[Mértani sor összegképlete]]
[[Az első n pozitív egész szám négyzetének összege]]

Egy sorozat mértani, ha a szomszédos tagok hányadosa állandó. Ez a hányados a **kvóciens** ($q$). A mértani sorozat általános alakja:

$$
a_n = a_1 \cdot q^{n-1}
$$

ahol:
- $a_n$ a sorozat $n$-edik tagja,
- $a_1$ az első tag,
- $q$ a kvóciens,
- $n$ a tag sorszáma.


Ahogy a számtani sorozatok különbsége, úgy a mértani sorozatok hányadosa állandó:

$\frac{a_{i + 1}}{a_{i}} = q$ 

valamely $q$ hányadossal. Az általános képzési szabály:

$a_{i} = a_{0} \cdot q^{i}$ 

Például 

$q = 2$ 

és 

$a_{0} = 1$ 

esetén a kettő hatványai:

$a_{i} = 2^{i}$ ,

melynek első néhány eleme $1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024$. Ezek a számok fontosak a tízesből kettes számrendszerbe és a kettes számrendszerből tízesbe való átváltáskor. Ha 

$|q| < 1$ 

akkor a mértani sorozat nullához tart. Például az $1; 0.1; 0.01; \ldots$ sorozat a 

$q = 0.1$ 

hányadossal:

$a_{i} = \left(\frac{1}{10}\right)^{i}$

Ha 

$q = 1$ 

akkor a sorozat konstans. Ha 

$q = -1$ 

akkor az első elemből és ellentettjéből álló ciklikus sorozat jön létre, például:

$a_{i} = (-1)^{i}$ 

az alap alternáló sorozat: $1, -1, 1, -1, \ldots$ . A mindennapi alkalmazásra példa a temperált hangolás, ahol is a félhangközök mértani sorozatot alkotnak.
