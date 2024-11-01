**Domaine:**
Le domaine de définition d'une fonction est l'ensemble des réels qui ont une image réelle par ***f***

**Déterminer le [[domaine]] d'une fonction:**
*si:*
$\huge \frac {A}{B}$       donc:  C.E  $B \neq 0$  => par exemple dans $\huge \frac {1}{x}$, $x$ ne peut etre égale a 0.

*si:*
$\large  \sqrt[n]{A}$     donc:  $\text{C.E}$  $\large  A \geq 0$ => par exemple dans $\large  \sqrt{2}$, 2 doit etre plus grand ou égale a 0.
	! car si le exposant est impar tous les réels sont possibles.

- [[exemples]]

**La fonction *Valeur entiere*:**

*défénition:*
 x => $E(x)$ = le plus grand entier inférieur ou égal a $x$

*graphiquement:*
![[Pasted image 20241031172743.png]]
**Fonction valeur entiere de $x$** 
- si on est a 2 on va a l'entier égale **donc** 2 
- si on est a 2,5 on va a l'entier inférieur **donc** 2
- si on est a -1,8 on va a l'entier inférieur **donc** -2



**La fonction signe**:

$$\large R \to R : x \mapsto \text{sign}(x) = \begin{cases} 1 & \text{if } x > 0 \\ 0 & \text{if } x = 0 \\ -1 & \text{if } x < 0 \end{cases}$$

- si  c'est plus grand que 0, c'est égale a 1
- plus petit est egale a -1
- égale est égale a 0


**Inverse d'une fonction**

$$\large i : x \mapsto i(x) = \frac{1}{f(x)}$$
pas compris deso

**Somme et différence de fonctions** 

$$f+g$$
- Son graphique s'obtient a partir des graphoqies des fonctions $f$ et $g$, en additionnant les ordonnées des points de meme abscisse.
- le domaine de $f$ + $g$ est $l'intersection$ des domaines de $f$ et de $g$.

$$f-g$$
- le domaine de $f$ - $g$ est $l'intersection$ des domaines de $f$ et de $g$.
- Son graphique s'obtient a partir des graphoqies des fonctions $f$ et $g$, en soustrayant les ordonnées des points de meme abscisse.

[[exemples]]

**fonction homographique** 
- On appelle fonction homographique toute fonction:$f : \mathbb{R} \to \mathbb{R}, \quad x \mapsto \frac{ax + b}{cx + d}$ ou a, b, c et d sont des réels, c étant non nul, le numérateur n'est pas un multiple du dénominateur.


   $\huge A.H = y = \frac {a}{c}$                                                      $\huge A.V = x = \frac {-d}{c}$           


**élements infinis** 

-  **propriétés**

$$\large
\begin{align*}
& +\infty + (+\infty) = +\infty \\
& -\infty + (-\infty) = -\infty \\

& +\infty \times (+\infty) = +\infty \\
& +\infty \times (-\infty) = -\infty \\
& -\infty \times (+\infty) = -\infty \\
& -\infty \times (-\infty) = +\infty \\

& \text{Pour tout } r \in \mathbb{R}_0^+: \\
& r \cdot (+\infty) = +\infty \\
& r \cdot (-\infty) = -\infty \\
& \text{Pour tout } r \in \mathbb{R}_0^-: \\
& r \cdot (+\infty) = +\infty \\
& r \cdot (-\infty) = -\infty \\
& \text{Pour tout } r \in \mathbb{R}: \\
& r + (+\infty) = +\infty \\
& r + (-\infty) = -\infty 
\end{align*}
$$
- **Cas interdits** 
	$$\large \begin{align*} & +\infty + (-\infty) \text{ = indéterminé (F.I)} \\ & +-\infty / +-\infty \text{ = indéterminé (F.I)} \\ & 0 \cdot (+-\infty) \text{ = indéterminé (F.I)} \\ & \frac{0}{0} \text{ = indéterminé (F.I)} \end{align*} $$

**intervalles ouverts et points adhérents**
Soit $a \in \mathbb{R}$

- **point adhérent**
  a est un point adhérent de A signifie que tout intervalle ouvert comprenant a, comprend au moins un élément de A.
	*! Un point adhérent de A est soit un point d'accumulation, soit un point isolé*
- **point d'accumulation** 
  a est un point d'accumulation de A signifie que tout intervalle ouvert comprenant a, comprend un élément de A autre que a.
- **point isolé** 
  a est un point isolé de A signifie qu'il existe un intervalle ouvert centré en a dont l'intersection avec A est {a}.

compliqué d'expliquer avec ses  propres mots voir [[exemples]]

**défénitions limites**
- voir graphes du cours pour un exemple graphique si imconprehension

$$\huge \lim_{x \to a{}} f(x)=b$$
$$\large \lim_{x \to a} f = b \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } 0 < |x - a| < \delta \implies |f(x) - b| < \varepsilon $$
- voir [[exemples]] pour plus d'éxplications

$$\huge \lim_{x \to a{}} f(x)= +\infty$$
$$\large \lim_{x \to a} f = +\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } 0 < |x - a| < \delta \implies f(x) > \varepsilon $$
	! le signe du epsilone et $+\infty$ changent et $f(x)$
	
$$\huge \lim_{x \to a{}} f(x)= -\infty$$
$$\large \lim_{x \to a} f = -\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } 0 < |x - a| < \delta \implies f(x) < \varepsilon $$

- **dans ces deux cas la droite = $a$ = $x$, est un asymptote verticale au GF**

$$\huge \lim_{x \to +\infty} f(x)= b$$
$$\large \lim_{x \to +\infty} f = b \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } x > \delta  \implies |f(x)-b| < \varepsilon $$
- meme que la premiere sauf que on remplace $a$ par $+\infty$, que $|x-a|$ devient $x$ et le signe change
$$\huge \lim_{x \to -\infty} f(x)= b$$
$$\large \lim_{x \to -\infty} f = b \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } x < \delta  \implies |f(x)-b| < \varepsilon $$

-**dans ces deux cas la droite = $b$ = $y$, est un asymptote horizontale au GF**

$$\huge \lim_{x \to +\infty} f(x)= +\infty$$
$$\large \lim_{x \to +\infty} f = +\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } x > \delta  \implies f(x) > \varepsilon $$

$$\huge \lim_{x \to +\infty} f(x)= -\infty$$
$$\large \lim_{x \to +\infty} f = -\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } x > \delta  \implies f(x) < \varepsilon $$
$$\huge \lim_{x \to -\infty} f(x)= -\infty$$
$$\large \lim_{x \to -\infty} f = -\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } x < \delta  \implies f(x) < \varepsilon $$
- explication logique dans [[exemples]]


**déterminer graphiquement une limite**


![[Pasted image 20241101180156.png]]

- quand la limite tend vers $2^-$ de la fonction $f(x)$ :
$$\huge \lim_{x \to 2^{-}} f(x)$$
on voit que si on part de $x=1$ et que on se raproche on voit que on approche de 5.
donc:
$$\huge \lim_{x \to 2^{-}} f(x)=5$$

- quand la limite tend vers $2^+$ de la fonction $f(x)$ :
$$\huge \lim_{x \to 2^{+}} f(x)$$
 on voit que si on part des valeurs supérieurs a d2  et que on se raproche on voit que on approche de 1.
donc:
$$\huge \lim_{x \to 2^{+}} f(x)=1$$

*on peut donc en déduire que*:

$$\huge \lim_{x \to 2^{+}} f(x) \neq \huge \lim_{x \to 2^{-}} f(x)$$
  **auterment dit la limite quand x tend vers 2 n'existe pas.**


Par contre, si on applique la meme chose pour $x$ qui tend vers $4$ on peut voir que 

$$\huge \lim_{x \to 4^{-}} f(x)=-5$$
*et que*
$$\huge \lim_{x \to 4^{+}} f(x)=-5$$
donc:$$\huge \lim_{x \to 4{}} f(x)=-5$$
voir plus d'exemples dnas [[exmples]].

[[limitées]]:

Soit *I* un intervalle et soit f une contion définie au moins sur I. On dit que:

*f* est ==majorée== sur I lorsqu'il existe un réel M tel que: $f(x) \le M$ pour tout $x \in I$

*f* est ==minorée== sur I lorsqu'il existe un réel M tel que: $M \ge f(x)$ pour tout $x \in I$

*f* est ==borné== sur I lorsque elle est les deux

