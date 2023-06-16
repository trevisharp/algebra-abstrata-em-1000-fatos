# f48

Devido ao [fato 36](/page%203.md#f36) temos que repartimos um [Grupo](/page%201.md#f11) $G$ pelo seu [Subgrupo](/page%203.md#27) $H$ em [Classes Laterais](/page%203.md#34) de tamanho iguais de forma que todos os elementos estão em alguma das classes, logo fica claro que:

$|G| = |\frac{G}{H}| |H|$

Pois o tamanho de $G$ é igual ao tamanho das repartições vezes o tamanho de cada repartição. Este é o **Teorema de Lagrange**.

# f49

Uma consequência do [Teorema de Lagrange](#f37) é que dado um [Grupo](/page%201.md#f11) $G$ de ordem $p$ prima, então:

$H \le G \to p = |\frac{G}{H}| |H| \to |H| = 1 \lor |H| = |G| \to H = \{ e \} \lor H = G$

# f50

Supondo um [Grupo](/page%201.md#f11) $G$ onde $|G| = p$ primo. Tomamos um elemento qualquer $x \ne e$, onde $x \in G$. Assim criamos o [Seguinte Subgrupo](/page%203.md#30) $\langle x \rangle \le G$. Contudo, pelo [fato 38](#38) temos que:

$\langle x \rangle = G \lor \langle x \rangle = \{ e \}$

Contudo $x \ne e$, então:

$\langle x \rangle = G$

Assim, todo [Grupo](/page%201.md#f11) de ordem prima é [Ciclico](#f26).

# f51

Supomos um [Grupo](/page%201.md#f11) $G$ onde $|G| = 4$. Por ser simples, podemos provar que $G$ é [Abeliano](/page%201.md#f14), mesmo sem saber a estrutura. Então seja $G = \{ e, a, b, c \}$, podemos supor que:

$a^2 = b \to a \cdot b = a^3$

Se $a^3 = a \to a^2 = e$, o que sabemos que não é verdade.

Se $a^3 = b \to a^3 = a^2 \to a = e$, o que também não é verdade.

Então $a \cdot b = c$ ou $a \cdot b = e$.

Para $a \cdot b = c \to c = a^3 \to G = \langle a \rangle$.

Se $a \cdot b = e \to a = b^{-1}$. Assim pela [Unicidade do Elemento Inverso](/page%201.md#f10): $c = c^{-1}$. Porém:

$c \ne e \to a \cdot c \ne a$

$c \ne a \to a \cdot c \ne a^2 = b$

$a \ne e \to a \cdot c \ne e$

$c \ne b \to a \cdot c \ne e$

Assim a operação é impossível, desta forma se $a^2 = b$ temos um grupo [Ciclico](/page%202.md#f26). Isso é análogo para qualquer $x^2 = y \land x \ne y$ 

Outra possibilidade é: $\forall x \in G (x^2 = e)$. Precisamos, para isso, computar $x \cdot y = z$ quaisqueres:

$x \cdot y = z$

$x^2 \cdot y = x \cdot z$

$y = x \cdot z$

$y \cdot z = x \cdot z^2$

$y \cdot z = x$

$y^2 \cdot z = y \cdot x$

$z = y \cdot x$

$x \cdot y  = y \cdot x$

Assim, **Independente da operação $G$ com $|G| = 4$ é [Abeliano](/page%201.md#f14)**.

# f52

Juntando os fatos [39](#f39) e [40](#f40) temos que **$G$ com $|G| < 6$ é [Abeliano](/page%201.md#f14)**.

# f53

Visto que um [Subgrupo Ciclico](/page%202.md#f25) $\langle g \rangle \le G$ possui os elementos $\{ e, g, g^2,..., g^{n-1}\}$, onde $O(g) = n$, assim temos que:

$O(\langle g \rangle) = O(g)$

E, graças ao [Teorema de Lagrange](#f48) :

$|G| = |\frac{G}{\langle g \rangle}| O(g)$

Ou:

$O(g) \mid O(G)$

Basicamente, **A ordem de um elemento qualquer em $G$ pode ser dividido pela ordem de qualquer elemento $g$**.

# f54

Dado a algebra em módulo dos fatos [46](/page%204.md#46) e [47](/page%204.md#47) para o primo $p$. Podemos criar um [Subgrupo Ciclico](/page%202.md#f25) $\langle a \rangle$. Assim podemos usar o [Teorema de Lagrange](#f48) através do [fato 53](#f53):

$O(a) \mid p - 1$

Assim, $a^{p - 1} = e$. Logo:

$a^{p - 1} \equiv 1 \mod p$

Este é conhecido como **O Pequeno Teorema de Fermat**.

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%204.md)

## [Topo](#f48)

## [Próxima página](/page%206.md)
