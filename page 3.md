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

$g, h \in H \to g, h^{-1} \in H \to g \cdot (h^{-1})^{-1} = g \cdot h \in H$ ([Totalidade](/page%201.md#f1))

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

# f32

Um [Grupo](/page%201.md#f11) $G$ pode ser reparticionado através de um [Subgrupo](#f27) $H$ definindo a seguinte **relação**:

$x \sim_H y \iff x \cdot y^{-1} \in H$

A semelhança com o [fato 29](#f29) é proposital, ela faz com que os elemntos de $H$ sempre se relacionem, além disso esse tipo de expressão, como pudemos ver, nos trás várias relações interessantes.
Sobre a relação podemos observar propriedades importantes:

1. Reflexividade: $x \cdot x^{-1} = e \in H \to x \sim_H x$
2. Simetria: $x \sim_H y \to x \cdot y^{-1} \in H \to (x \cdot y^{-1})^{-1} = y \cdot x^{-1} \in H \to y \sim_H x$
3. Transitividade: $x \sim_H y \land y \sim_H z \to x \cdot y^{-1} \in H \land y \cdot z^{-1} \in H \to x \cdot y^{-1} \cdot y \cdot z^{-1} = x \cdot z^{-1} \in H \to x \sim_H z$

Assim, está relação é uma relação de equivalência.

# f33

A relação do [fato 32](#f32) por ser uma relação de equivalência, dividimos um [Grupo](/page%201.md#f11) $G$ por seu [Subgrupo](#f27) $H$ em classes de equivalência ao qual chamaremos de **Classes Laterais**:

$\bar g = \{ x \in G \mid x \sim_H g \}$

Podemos manipular esse conjunto da seguinte forma:

$\bar g = \{ x \in G \mid h = x \cdot g^{-1} \in H \}$

Porém como:

$h = x \cdot g^{-1} \to h \cdot g = x$

Então:

$\bar g = \{ h \cdot g \mid h \in H \}$

Note que isso só é possível pois:

$\forall h \in H \exists x \in G (h = x \cdot g^{-1})$

Assim, podemos escrever uma Classe lateral a direita:

$H g = \{ h \cdot g \mid h \in H \}$

# f34

Da mesma forma que temos classes laterais direitas, podemos ter **Classes Laterais Esquerdas** realizando o mesmo processo com a seguinte relação de equivalência, análoga a do [fato 32](#f32):

$x \sim_H y \iff x^{-1} \cdot y \in H$

Assim definindo:

$g H = \{ g \cdot h \mid h \in H \}$

# f35

O conjunto de todas as [Classes Laterais](#f33) a [Esquerda](#f34) é conhecido como **Conjunto Quociente**:

$\frac{G}{H} = \{ g H \mid g \in G \}$

# f36

O tamanho de cada [Classe Lateral](#f33), então será:

$|g H| = |\{g \cdot h \mid h \in H\}|$

Para calcular isso, começamos supondo que existe dois elementos $h_1, h_2 \in H$ tal que:

$h_1 \ne h_2 \land g \cdot h_1 = g \cdot h_2$

Contudo:

$g^{-1} \cdot g \cdot h_1 = g^{-1} \cdot g \cdot h_2$

$h_1 = h_2$

Assim, por absurdo, não existem 2 $h$ que levem ao mesmo element em $g H$, desta forma:

$|g H| = |\{ g \cdot h_1 \} \cup \{ g \cdot h_2 \} \cup ... \cup \{ g \cdot h_{O(H)} \}|$

E como sabemos que os elementos $g \cdot h_i$ são todos diferentes, podemos escrever:

$|g H| = |\{ g h_1 \}| + |\{ g h_2 \}| + ... + |\{ g h_{O(H)} \}|$

$|g H| = O(H) = |H|$

Podemos provar de forma análoga para classes a direita também. Assim:

$|g H| = |H g| = |H|$

Note que não necessariamente g H = H g.

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%202.md)

## [Topo](#f27)

## [Próxima página](/page%204.md)