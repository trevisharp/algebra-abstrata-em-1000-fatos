# f18

Se $G$ é um [Grupo](#f11), dizemos que o tamanho do conjunto de $G$, ou seja $O(G) = |G|$ é a **Ordem do Grupo**.

# f19

Se a [Ordem de um Grupo](#f18) é finita, dizemos que o [Grupo](#f11) é um **Grupo Finito**.

# f20

Se a [Ordem de um Grupo](#f18) é infinita, dizemos que o [Grupo](#f11) é um **Grupo Ininito**.

# f21

Seja $G$ um [Grupo](/page%201.md#f11) e $g \in G$ um elemento qualquer, supondo que:

$O(g) = k \iff g^k = e $

Dizemos que O(g) é a **Ordem do Elemento** g.

# f22

Seja $G$ um [Grupo Finito](#f20) e $g \in G$ um elemento qualquer. Como $G$ é finito, existe algum $k$ tal que $g^k = g^n$, visto que é impossível que nenhuma da infinitas possibilidades para $k$ e $n$ coincidam dada a finidade do [Grupo](/page%201.md#f11). Assim

$g^k = g^n$

$g^k \cdot g^{-n} = g^n \cdot g^{-n}$

Tomando $k > n$:

$g^{k-n} = e \to O(g) = k - n$

Assim, **Em um Grupo Finito, todos os elementos tem ordem finita**. Isso significa que ao operá-los consigo mesmos, em algum momento, teremos o elemento nulo.

# f23

Seja $G$ um [Grupo Finito](#f20) e $g \in G$, é notável que:

$O(g) = k \to g^k = e$

$(g^k)^{-1} = e^{-1}$

$(g^{-1})^k = e$

$O(g^{-1}) = k$

$O(g) = O(g^{-1})$

# f24

Seja $G$ um [Grupo Finito](#f20) e $g, h \in G$, é notável que:

$O(g \cdot h) = k \to (g \cdot h)^k = e$

$g^k \cdot h^k = e \to g^k = h^{-k} \to e = g^{-k} \cdot h^{-k}$

Assim, pela propriedade [f17](/page%201.md#f17)

$e = (g^{-1} \cdot h^{-1})^{k} \to e = (h \cdot g)^{-k}$

Logo:

$O((h \cdot g)^{-1}) = O((h \cdot g)) = k$ (Usando [23](#f23))

Concluindo, temos que:

$O(h \cdot g) = O(g \cdot h)$

# f25

Seja $G$ um [Grupo Finito](#f20) e $g \in G$, caso:

$G = \{ g^0 = e, g^1, g^2, g^3, ... \}$

Dizemos que $G$ é um **Grupo Ciclico**, denotado por:

$G = \langle g \rangle$

# f26

Evidentemente, um [Grupo Ciclico](#f26) G é [Abeliano](/page%201.md#f14), pois:

$\forall x = g^k, y = g^n \in G (x \cdot y = g^{k + n} = g^{n + k} = y \cdot x)$

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%201.md)

## [Topo](#f18)

## [Próxima página](/page%203.md)