# f37

Dado um [Grupo](/page%201.md#f11) $G$ definimos uma **Conjugação** como:

$h^g = g \cdot h \cdot g^{-1}$

Dizemos que nesse caso, $h \in G$ está sendo conjungado por $g \in G$.

# f38

Podemos **Conjugar um [Grupo](/page%201.md#f11)** [Conjugando](#f37) todos os seus elementos:

$H^g = \{ h^g \mid h \in H \}$

# f39

Dizemos que, dado um [Grupo](/page%201.md#f11) $G$ e seu [Subgrupo](/page%203.md#27) $N$, dizemos que $N$ é **Normal** se:

$N^g \subset N$

# f40

Denotamos um [Subgrupo Normal](#f39) $N \le G$ como:

$N \vartriangleleft G$

# f41

Podemos provar que:

$n \in N$

$N \subset G \to n \in G \to g^{-1} \cdot n \cdot g \in N^{g^{-1}} \to g^{-1} \cdot n \cdot g = m \in N$

Assim:

$m^g = g \cdot g^{-1} \cdot n \cdot g \cdot g^{-1} = e \cdot n \cdot e = n \in N^g$

Concluimos que:

$\forall n \in N (n \in N^g)$

Ou seja:

$N \subset N^g$

Mas devido ao [fato 40](#f40), temos então que:

$N = N^g$

Assim **Subgrupos Normais são Invariantes a Conjugação**.

# f42

Podemos fazer [Conjuntos Quocientes](/page%203.md#f35) apartir de [Subgrupo Normais](#f39) e estes conjuntos tem propriedades especiais:

$N \vartriangleleft G$

$\bar x, \bar y \in \frac{G}{N}$

Podemos provar que a operação $\bar x \cdot \bar y$ é consistente. Se isso realmente for provado, estaremos provando que este conjunto na verdade é um **Grupo Quociente**, ou seja $\frac{G}{N}$ é um grupo. Para isso é necessário provar que:

$x \cdot y = z \iff \bar x \cdot \bar y = \bar z$

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%203.md)

## [Topo](#f37)

## [Próxima página](/page%205.md)