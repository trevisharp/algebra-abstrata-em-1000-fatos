# f21

Seja $G$ um [Grupo](/page%201.md#f11) e $g \in G$ um elemento qualquer, supondo que:

$O(g) = k \iff g^k = e $

Dizemos que O(g) é a <u>Ordem do Elemento</u> g.

# f22

Seja $G$ um [Grupo Finito](/page%201.md#f20) e $g \in G$ um elemento qualquer. Como $G$ é finito, existe algum $k$ tal que $g^k = g^n$, visto que é impossível que nenhuma da infinitas possibilidades para $k$ e $n$ coincidam dada a finidade do [Grupo](/page%201.md#f11). Assim

$g^k = g^n$

$g^k \cdot g^{-n} = g^n \cdot g^{-n}$

Tomando $k > n$:

$g^{k-n} = e \to O(g) = k - n$

Assim, <u>Em um Grupo Finito, todos os elementos tem ordem finita</u>. Isso significa que ao operá-los consigo mesmos, em algum momento, teremos o elemento nulo.

# f23

Seja $G$ um [Grupo Finito](/page%201.md#f20) e $g \in G$, é notável que:

$O(g) = k \to g^k = e$

$(g^k)^{-1} = e^{-1}$

$(g^{-1})^k = e$

$O(g^{-1}) = k$

$O(g) = O(g^{-1})$

# f24

Seja $G$ um [Grupo Finito](/page%201.md#f20) e $g, h \in G$, é notável que:

$O(g \cdot h) = k \to (g \cdot h)^k = e$

$g^k \cdot h^k = e \to g^k = h^{-k} \to e = g^{-k} \cdot h^{-k}$

Assim, pela propriedade [f17](/page%201.md#f17)

$e = (g^{-1} \cdot h^{-1})^{k} \to e = (h \cdot g)^{-k}$

Logo:

$O((h \cdot g)^{-1}) = O((h \cdot g)) = k$ (Usando [23](#f23))

Concluindo, temos que:

$O(h \cdot g) = O(g \cdot h)$

# f25

Seja $G$ um [Grupo Finito](/page%201.md#f20) e $g \in G$, caso:

$G = \{ g^0 = e, g^1, g^2, g^3, ... \}$

Dizemos que $G$ é um <u>Grupo Ciclico</u>, denotado por:

$G = \langle g \rangle$

# f26

Evidentemente, um [Grupo Ciclico](#f26) G é [Abeliano](/page%201.md#f14), pois:

$\forall x = g^k, y = g^n \in G (x \cdot y = g^{k + n} = g^{n + k} = y \cdot x)$

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%201.md)

## [Topo](#f21)