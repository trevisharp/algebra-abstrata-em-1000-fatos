# f27

Seja $G$ um [Grupo](/page%201.md#f11) e $H$ um subconjunto de $G$ se, e somente se, $H$ for um grupo, $H$ é **Subgrupo** de G.

# f28

**Denotamos um Subgrupo** H de G da seguinte maneira:

$H \le G$

# f29

Supondo $G$ um [Grupo](/page%201.md#f11) e $H \subset G$ não-vazio de tal forma que:

$\forall g, h \in H (g \cdot h^{-1} \in H)$

Então, podemos perceber que $H$ possui algumas propriedades. Vamos várias vezes supor a existência de um elemento $h \in H$, visto que ele é não-vazio.

$h \in H \to h \cdot h^{-1} = e \in H$ ([Neutralidade](/page%201.md#f6))

$h, e \in H \to e \cdot h^{-1} = h^{-1} \in H$ ([Inversabilidade](/page%201.md#f9))

$g, h \in H \to g, h^{-1} \in H \to g \cdot (h^{-1})^{-1} = g \cdot h in H$ ([Totalidade](/page%201.md#f1))

Como:

$\forall g, h, f \in H (g \cdot (h \cdot f) = (g \cdot h) \cdot f$

Tendo assim ([Associatividade](/page%201.md#f4)), temos que $H$ é [Subgrupo](#f27) de $G$, pois $H$ é um [Grupo](/page%201.md#f11). Ou simplismente:

$H \subset G \land H \ne \emptyset \land \forall g, h \in H (g \cdot h^{-1} \in H) \to H \le G$

# f30

Notavelmente, $g \in G, \langle g \rangle \le G$ visto que:

$\forall g^k, g^n \in \langle g \rangle (g^{k-n} \in \langle g \rangle)$

# f31

Sejam dois [Grupo](/page%201.md#f11) $G$ e $H$ definimos outro grupo $I = G \cap H$ temos que $I$ possui:

$e \in G \land e \in H \to e \in I$ ([Neutralidade](/page%201.md#f6))

$g \in I \to g \in G \land g \in H \to g^{-1} \in G \land g^{-1} \in H \to g^{-1} \in I$ ([Inversabilidade](/page%201.md#f9))

$g, h \in I \to g, h \in G \land g, h \in H \to gh \in G \land g \cdot h \in H \to $ ([Totalidade](/page%201.md#f1))

Assim se $G \cap H \ne \emptyset$, $G \cap H$ é um [Grupo](/page%201.md#f11). Especialmente, **A intersecção de dois [Subgrupo](#f27) é um [Subgrupo](#f27)**.




---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%202.md)

## [Topo](#f27)

## [Próxima página](/page%204.md)