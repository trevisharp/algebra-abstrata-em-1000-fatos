# f71

Sejam os [Grupos](/page%201.md#f11) $H_1, H_2 \le G$, definimos um **Produto de Grupos** como:

$H_1  H_2 = \lbrace h_1 \cdot h_2 \mid h_1 \in H_1, h_2 \in H_2 \rbrace$

# f72

Vamos supor que:

$H_1, H_2 \le G \land H_1  H_2 = H_2  H_1$

Então podemos provar que **O Produto de Subgrupos que Comutam é também um Subgrupo**. Para isso basta que:

$\forall h_1 \cdot h_2 \in H_1 H_2, h_1' \cdot h_2' \in H_1 H_2 (h_1 \cdot h_2 \cdot (h_1' \cdot h_2')^{-1} \in H_1 H_2)$

Contudo:

$x = h_1 \cdot h_2 \cdot (h_1' \cdot h_2')^{-1} = h_1 \cdot h_2 \cdot h_2'^{-1} \cdot h_1'^{-1}$

$x = h_1 \cdot h_2''^{-1} \cdot h_1'^{-1} = h_1 \cdot (h_1' \cdot h_2'')^{-1}$

Porém como $H_1  H_2 = H_2  H_1$ então:

$\exists h_2'''^ \cdot h_1'' = h_1' \cdot h_2''$

Assim:

$x = h_1 \cdot h_1'' \cdot h_2'''$

$x = h_1''' \cdot h_2''' \in H_1 H_2 $

Logo, pelo [fato 29](/page%203.md#f29):

$H_1 H_2 \le G$

# f73

Sabemos pelo [fato 31](/page%203.md#31) que $H, F \le G \to H \cap F \le G$, porém, fica claro também que:

$H \cap F \le H$

E,

$H \cap F \le F$

Assim, podemos decompor qualquer um desses [Subgrupos](/page%203.md#27) da seguinte forma:

$I = H \cap F$

$H = I h_1 \cup I h_2 \cup I h_3 \cup ... \cup I h_n$

Podemos então aplicar o [Produto de Grupos](#f71) da seguinte forma:

$F H = F I h_1 \cup F I h_2 \cup F I h_3 \cup ... \cup F I h_n$

Contudo:

$I \subset F \to F I = F$

Assim:

$F H = F h_1 \cup F h_2 \cup F h_3 \cup ... \cup F h_n$

Note agora é possível que alguns elementos sejam compartilhados nos termos $F h_i$, assim não podemos escrever:

$|F H| = |F h_1| + |F h_2| + |F h_3| + ... + |F h_n|$

Precisamos considerar os elementos repetidos. Ou seja, elementos tais quais:

$f_1 \cdot h_i = f_2 \cdot h_j$

$x = f_1 \cdot f_2^{-1} = h_j \cdot h_i^{-1}$

Notavelmente:

$x \in I$

$|F H| = \frac{|F||H|}{|F \cap H|}$

# f74



---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%206.md)

## [Topo](#f71)

## [Próxima página](/page%208.md)
