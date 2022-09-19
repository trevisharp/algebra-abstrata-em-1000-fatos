# f55

Sejam dois [Grupos](/page%201.md#f11) $G$ e $G'$ e uma função $\phi : G \to G'$ tal que:

$\forall g, h \in G ( \phi(g \cdot h) = \phi(g) \cdot \phi(h) )$

Ou seja, uma função que preserva a estrutura dos grupos, chamamos está função de **Homomorfismo de Grupos**. Note que as operações $\cdot$ dentro e fora de $\phi$ são operações diferentes, um do grupo $G$ e o outro do grupo $G'$.

# f56

Caso um [Homomorfismo](#f55) seja Injetivo, chamamos ele de **Monomorfismo**.

# f57

Caso um [Homomorfismo](#f55) seja Sobrejetivo, chamamos ele de **Epimorfismo**.

# f58

Caso um [Homomorfismo](#f55) seja um [Monomorfismo](#f56) e um  [Epimorfismo](#f57), ou seja, Bijetivo, então ele é um **Isomorfismo**.

# f59

Caso um [Homomorfismo](#f55) seja de um [Grupo](/page%201.md#11) para ele mesmo, então chamamos ele de **Endomorfismo**.

# f60

Caso um [Homomorfismo](#f55) seja um [Isomorfismo](#f58) e um  [Endomorfismo](#f59) então ele é um **Automorfismo**.

# f61

Seja um $\phi : G \to G'$ então temos a seguinte propriedade:

$\phi(g) = \phi(g \cdot e) =\phi(g) \cdot \phi(e) $

Logo:

$g' = g' \cdot \phi(e) $

E então **$\phi(e) = e'$ é o neutro do grupo $G'$**.

# f62

Seja um $\phi : G \to G'$ então temos a seguinte propriedade:

$e' = \phi(e) = \phi(g \cdot g^{-1}) = \phi(g) \cdot \phi(g^{-1})$

$\phi(g)^{-1} = \phi(g)^{-1} \cdot \phi(g) \cdot \phi(g^{-1})$

$\phi(g)^{-1} = e' \cdot \phi(g^{-1})$

Assim:

$\phi(g)^{-1} = \phi(g^{-1})$

# f63

Chamamos de **Núcleo ou Kernel** de um [Homomorfismo](#f55) o seguinte conjunto:

$\ker(\phi) = \{ g \in G : \phi(g) = e' \}$

# f64

Chamamos de **Imagem** de um [Homomorfismo](#f55) o seguinte conjunto:

$\image(\phi) = \phi(G) = \{ \phi(g) : g \in G \}$

# f65

Seja um $\phi : G \to G'$ então é notável que:

$\phi(h^g) = \phi(g \cdot h \cdot g^{-1}) = \phi(g) \cdot \phi(h) \cdot \phi(g^{-1}) = \phi(g) \cdot \phi(h) \cdot \phi(g)^{-1} = \phi(h)^{\phi(g)}$

# f66

Seja um $\phi : G \to G'$ e $j, k \in \ker(\phi)$, temos que:

$\phi(j \cdot k^{-1}) = \phi(j) \cdot \phi(k)^{-1} = e \cdot e^{-1} = e$

Assim:

$j \cdot k^{-1} \in \ker(\phi)$

E pelo [fato 29](/page%203.md#29) temos que **O Núcleo de um Homomorfismo é um Subgrupo do seu Grupo de Domínio**.

# f67

Seja um $\phi : G \to G'$ e $k \in \ker(\phi)$, é notável que:

$\phi(k^g) = \phi(g) \cdot \phi(k) \cdot \phi(g)^{-1} = \phi(g) \cdot e \cdot \phi(g)^{-1}$

$\phi(g) \cdot e \cdot \phi(g)^{-1}= \phi(g) \cdot \phi(g)^{-1} = e'$

Assim:

$k^g \in \ker(\phi)$

Portanto:

$x \in \ker(\phi)^g \to x \in \ker(\phi)$

$\ker(\phi)^g \subset \ker(\phi)$

E pelo [fato 39](/page%204.md#f39) temos que o **Núcleo de um Homomorfismo é um Subgrupo Normal do seu Grupo de Domínio**.

# f68

Seja um $\phi : G \to G'$ e $g'=\phi(g), h'=\phi(h) \in \image(\phi)$, temos que:

$\phi(g \cdot h^{-1}) = \phi(g) \cdot \phi(h)^{-1} \to g' \cdot h'^{-1} \in \image(\phi)$

E pelo [fato 39](/page%204.md#f39) temos que a **Imagem de um Homomorfismo é um Subgrupo do seu Grupo de Contradomínio**.

# f69

Pelo [fato 67](#f67) adjunto do [fato 42](/page%204.md#42) temos que **$\frac{G}{\ker(\phi)}$ é um [Grupo](/page%201.md#f11)**.

# f70

Então podemos provar o **Primeiro Teorema do Isomorfismo**.

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%205.md)

## [Topo](#f55)

## [Próxima página](/page%207.md)