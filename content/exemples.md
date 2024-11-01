**Domaines**
1)  $$\sqrt \frac {3x-1}{x^2+7x-8}$$
- calculer $x^2+7x-8$ car  $\huge \frac {A}{B}$
- calculer $3x-1$ car $\large  \sqrt[n]{A}$ 
- donc:  $\large  3x-1  \geq 0$
- donc: ${x^2+7x-8} \neq 0$
- Dom*f* = $]-8;\frac{1}{3}]U]1;+\infty[$
2) $$\frac {\sqrt{3x-1}}{\sqrt{x^2+7x-8}}$$
- car $\large  \sqrt[n]{A}$ 
- calculer $x^2+7x-8 \geq 0$ 
- calculer  $\large  3x-1  \geq 0$
- dresser un tableau de signe 
- Dom*f* = $]1;+\infty[$
1)  $$\sqrt[3] \frac {3x-1}{x^2+7x-8}$$
-  car n est impair ($\large  \sqrt[n]{A}$)  tous les réels sont possibles ducoup on doit juste calculer ${x^2+7x-8} \neq 0$
- Dom*f* = $\mathbb{R}$\{-8;1}

**somme et différence de fonctions**

*soit les fonctions $f(x) = x$ et $g(x) = \frac {1}{x}$*

expressions analytique de:

$$ (f + g)(x) = \frac{x^2+1}{x}$$
$$ (f - g)(x) = \frac{x^2-1}{x}$$
$\large Dom f = \mathbb{R}$           $\large Dom f + g = \mathbb{R}_o$              $\large Dom f + g = \mathbb{R}_o$                   $\large Dom g = \mathbb{R}_o$

**Intervalles ouverts**

A = ensemble de points adhérents 
B = ensemble de points d'accumulation 
I = ensemble de points isolés

- $]2,4[$           $A=B=[2,4]$  $I = \cancel{0}$  
- $]1,3[U$**{5}**   $A=[1,3]U$**{5}**  $B = [1,3]$ I = **{5}** *car* 5 est isolé du coup ils ne sont pas accumulés
- $]-2,0[U]2,3[$  $A = B =[-2,0]U[2,4]$  $I = \cancel{0}$  *car* il n'y a pas un point isolé
- $\mathbb{R}$\{1,4}     A = B = $\mathbb{R}$ car il n'y a aucun point isolé et ils sont tjr entourés
- $\mathbb{R}$\[1,2]   A = B = $\mathbb{R}$\[1,2]  $I = \cancel{0}$  

**défénitions limites**

![[Pasted image 20241101195849.png]]
- on voit que on a $$\huge \lim_{x \to a{}} f(x)=b$$
 - donc: 
$$\large \lim_{x \to a} f = b \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } 0 < |x - a| < \delta \implies |f(x) - b| < \varepsilon $$

- on remplace 
			- $a$ avec la valeur qui tend vers $x$, dans ce cas $3$.
			- $b$ avec la valeur qui est égale a la limite de $f(x)$ dans ce cas $1$ 
			- $f(x)$ avec la fonction

- donc: c'est vrai que si delta est plus petit ou égale de $\frac {1}{2}$ épsilone

![[Pasted image 20241101204322.png]]


- logique pour savoir le sens du signe pour (par exemple) ces 3 expressions:
	*on voit que ce qui changes est cette partie*
$\large \lim_{x \to +\infty} f(x)= +\infty$           =>   $\large x > \delta  \implies f(x) > \varepsilon$

$\huge \lim_{x \to +\infty} f(x)= -\infty$   =>   $\large x > \delta  \implies f(x) < \varepsilon$

$\huge \lim_{x \to -\infty} f(x)= -\infty$   =>   $\large x < \delta  \implies f(x) < \varepsilon$

Le sens du signe dépend du signe de départ, si c'est $+\infty$ pour le infi en dessous de la limite, le $x$  sera plus grand que detla, et si c'est $-\infty$ le $x$ sera plus petit que detla.
Si le infini apres le égale est négatif la fonction sera  plus petite que épsilone et vice-versa.
cela marche pour toutes les formules contenant $x$ avec delta et $f(x)$ avec epsilone.
*comme dans*
$$\huge \lim_{x \to a{}} f(x)= -\infty$$
$$\large \lim_{x \to a} f = -\infty \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tel que } 0 < |x - a| < \delta \implies f(x) < \varepsilon $$
ou l'infini apres l'egale est négatif, et ducoup la fonction est plsu petit que le l'épsilone $f(x) < \varepsilon$

 - on remarque aussi que a chaque début de formule il y a $\forall \varepsilon > 0, \exists \delta > 0$ 
- pour savoir le signe j'ai remarqué que 
	 pour le $\varepsilon$ il faut regarder ce que il y a apres le égale et si c'est positif c'est plus grand que 0 et vice-versa.
	 pour le $\delta$ il faut regarder le chiffre en dessous de la limite et si c'est positif delta est plus grand que 0 et vice-versa.

**Discontinuité**

![[Pasted image 20241101182146.png]]

$$\huge \lim_{x \to 2^{-}} f(x) = 4$$
$$\huge \lim_{x \to 2^{+}} f(x) \approx 1.14$$
donc:
$$\huge \lim_{x \to 2} f(x) \text{ n'existe pas}$$

![[Pasted image 20241101182155.png]]

$$\huge \lim_{x \to 3^{-}} f(x) = 9$$ $$\huge \lim_{x \to 3^{+}} f(x) = 9$$*donc:*
$$\huge \lim_{x \to 3{}} f(x) = 9$$
![[Pasted image 20241101182418.png]]

$$\huge \lim_{x \to 2^{-}} f(x) = -\infty $$ $$\huge \lim_{x \to 2^{+}} f(x) = +\infty$$
*donc:*

$$\huge \lim_{x \to 2{}} f(x) = \text{ n'existe pas}$$
