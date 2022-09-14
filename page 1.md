# f1

Seja uma função $f : A^2 \to A$ e o conjunto $B \subset A$, o par $(B, f)$ é uma estrutura com **Totalidade** se:

$\forall a, b \in B ( f(a,b) \in B)$

# f2

Uma estrutura com [Totalidade](#f1) é um **Magma**.

# f3

E f é dita a **operação** da estrutura, geralmente denotada como:

$a \cdot b = c \iff f(a, b) = c$

# f4

Caso a estrutura $G$ possua a seguinte propriedade:

$(a \cdot b) \cdot c = a \cdot (b \cdot c)$

Dizemos que ela tem **Associatividade**.

# f5

Um [Magma](#f2) com [Associatividade](#f4) é um **Semi-grupo**.

# f6

Caso uma estrutura $G$  possua a seguinte propriedade:

$\exists e \in G (\forall a \in G (e \cdot a = a \cdot e = a))$

Dizemos que ela tem **Neutralidade**.

# f7

Quando uma estrutura possuir [Neutralidade](#f6), os elementos que $e$ da expressão:

$\exists e \in G (\forall a \in G (e \cdot a = a \cdot e = a))$

São chamados de **Elementos Neutros**.

# f8

Um [Semi-grupo](#f5) com [Neutralidade](#f6) é um **Monóide**.

# f9

Caso uma estrutura $G$  possua a seguinte propriedade:

$\forall g \in G (\exists h, e \in G (e~é~elemento~neutro~de~G ~\&~ g \cdot h = e))$

Dizemos que ela tem **Inversabilidade**.

# f10

Caso uma estrutura $G$ possuir [Inversabilidade](#f9), então para cada elemento $x \in G$ denotamos o **Elemento Inverso** deste $x$ como $x^{-1}$.

# f11

Um [Monóide](#f8) com [Inversabilidade](#f9) é um **Grupo**.

# f12

A **Notação de Potência** será utilizada quando queremos escrever:

$x \cdot x \cdot x \cdot x ... = x^n$

Ela significa uma repetição de vezes da mesma operação. Fica claro que:

$x^n \cdot x^k = x^{n + k}$

E também temos o fato de que:

$x^{-n} = (x^{-1})^n$

Note que:

$x^{-n} \cdot x^n = e$

Com $e$ sendo o elemento neutro. Assim respeitamos a propriedade de exponenciação assim como na multiplicação:

$x^{n} \cdot x^{-k} = x^{n - k}$

# f13

Caso uma estrutura $G$  possua a seguinte propriedade:

$\forall g, h \in G (g \cdot h = h \cdot g)$

Dizemos que ela tem **Comutatividade**.

# f14

Um [Grupo](#f11) com [Comutatividade](#f13) é um **Grupo Abeliano**.

# f15

Dado um [Grupo](#f11) $G$ qualquer, podemos supor a existência de 2 [Elementos Neutros](#f7) $e_1$ e $e_2$, teremos que, dado um $x \in G$ qualquer:

$x \cdot e_1 = x = x \cdot e_2$

Podemos operar a esquerda com o [Elemento Inverso](#f10) de $x$:

$x^{-1} \cdot x \cdot e_1 = x = x^{-1} \cdot x \cdot e_2$

Porém, como $G$ é um [Grupo](#f11), temos a propriedade de [Inversabilidade](#f9), logo:

$x^{-1} \cdot x = e$

Onde $e$ é um [Elemento Neutro](#f7) qualquer. Assim, nossa expressão original fica:

$e \cdot e_1 = e \cdot e_2$

Graças a [Neutralidade](#f6) temos que:

$e \cdot e_1 = e_1$

E,

$e \cdot e_2 = e_2$

Assim,

$e_1 = e_2$

Desta forma provamos que nossa hipótese de termos dois elementos neutros estava errada. Isso significa que temos a **Unicidade do elemento Neutro**. Em todo [Grupo](#f11) existe um e apenas um [Elemento Neutro](#f7). Desta forma, usaremos apenas a letra $e$ que sempre significará este único elemento.

# f16

Dado um [Grupo](#f11) $G$ qualquer, podemos supor a existência de 2 [Elementos Inversos](#f10) $y_1$ e $y_2$ para um mesmo $x \in G$, contudo:

$x \cdot y_1 = e = x \cdot y_2$

$x^{-1} \cdot x \cdot y_1 = x^{-1} \cdot x \cdot y_2$

$e \cdot y_1 = e \cdot y_2$

$y_1 = y_2$

Provando assim que para cada $x$ qualquer em $G$ existe um e apenas um [Elemento Inverso](#f10). Assim temos a **Unicidade do elemento Inverso**.

# f17

Dado um [Grupo](#f11) $G$, caso quisessemos calcular a expressão $(x \cdot y)^{-1}$ com $x, y \in G$, poderiamos nos surpreender que o resultado não é  $x^{-1} \cdot y^{-1}$. Como demonstrado a seguir, usando o princípio de realizar a mesma operação (multiplicar algum elemento a direita ou esquerda):

$(x \cdot y)^{-1} = z$

$(x \cdot y)^{-1} \cdot (x \cdot y) = z \cdot x \cdot y$

$e = z \cdot x \cdot y$

$e \cdot y^{-1} = z \cdot x \cdot y \cdot y^{-1}$

$e \cdot y^{-1} = z \cdot x \cdot e$

$y^{-1} = z \cdot x$

$y^{-1} \cdot x^{-1} = z \cdot x \cdot x^{-1}$

$y^{-1} \cdot x^{-1} = z \cdot e$

$y^{-1} \cdot x^{-1} = z$

$(x \cdot y)^{-1} = y^{-1} \cdot x^{-1}$

---
---
---

## [Menu](/readme.md)

## [Topo](#f1)

## [Próxima página](/page%202.md)