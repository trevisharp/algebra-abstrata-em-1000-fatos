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

$\exists r \in \bar r (\forall g \in \bar g (\forall h \in \bar h (g \cdot h = r)))$

Podemos provar isso por absurdo supondo:

$r \in \bar r, s \in \bar s$

$g_1, g_2 \in \bar g$

$h_1, h_2 \in \bar h$

$g_1 \cdot h_1 = r$

$g_2 \cdot h_2 = s$

Porém, como $N$ é [normal](#f39):

$h_1 \cdot h_2^{-1} \in N$

$(h_1 \cdot h_2^{-1})^{g_1} = g_1 \cdot h_1 \cdot h_2^{-1} \cdot g_1^{-1} = r \cdot h_2^{-1} \cdot g_1^{-1} \in N$

E como $N$ é um [grupo](/page%201.md#f11):

$g_1 \cdot g_2^{-1} \in N$

$r \cdot h_2^{-1} \cdot g_1^{-1} \cdot g_1 \cdot g_2^{-1} \in N$

$r \cdot h_2^{-1} \cdot e \cdot g_2^{-1} \in N$

$r \cdot h_2^{-1} \cdot g_2^{-1} \in N$

$r \cdot (g_2 \cdot h_2)^{-1} \in N$

$r \cdot s^{-1} \in N \to r \sim_H s \to \bar s = \bar r$

Assim a operação é consistente e **se $N \vartriangleleft G$ então $\frac{G}{N}$ é um grupo**.

# f43

O conjunto dos **números inteiros dotado da operações de soma $(\mathbb{Z}, +)$ é um [Grupo](/page%201.md#11)**, pois, dado $a, b, c \in \mathbb{Z}$:

1. $a + b \in \mathbb{Z}$ ([Totalidade](/page%201.md#f1))
2. $a + 0 = 0 + a = a, 0 \in \mathbb{Z}$ ([Neutralidade](/page%201.md#f6))
3. $(a + b) + c = a + (b + c)$ ([Associatividade](/page%201.md#f4))
4. $a - a  = 0$ ([Inversabilidade](/page%201.md#f9))

# f44

Notavelmente, **se um grupo é [Abeliano](/page%201.md#14) todo [Subgrupo](/page%203.md#27) é [Normal](#f39)**, pois:

$g \cdot n \cdot g^{-1} = g \cdot g^{-1} \cdot n = n \in N$

# f45

Podemos encontrar um [Subgrupo](/page%203.md#27) para o [grupo do fato 43](#f42) como um subgrupo [Ciclico](/page%202.md#f25). Denotamos este subgrupo como $n \mathbb{Z} = \langle n \rangle$. Pelo [fato 44](#f44), ele é [Normal](#39).

# f46

Uma **álgebra em módulo pode ser definida com o conjunto quociente**, ou seja, $\frac{\mathbb{Z}}{n \mathbb{Z}}$. Sabemos pelo [fato 45](#f45) que este é também um [Grupo](/page%201.md#11). Apenas um exemplo:

$\frac{\mathbb{Z}}{5 \mathbb{Z}} = \{ \bar 0, \bar 1, \bar 2, \bar 3, \bar 4 \}$

Para fazer qualquer operação fazemos o módulo por 5:

$\bar 2 + \bar 4 = \bar 6 = \bar 1$

Fora do contexto de grupos, costumamos representar da seguinte forma:

$2 + 4 \equiv 1 \mod 5$

# f47

Outra estrutura interessante são o conjunto dos inteiros com a operação de multiplicação ($\mathbb{Z}$, $\times$), porém não teríamos a propriedade de [Inversabilidade](/page%201.md#f9) visto que, por exemplo, 5 não tem seu inverso ($\frac{1}{5} \notin \mathbb{Z}$). Porém, temos associatividade, neutro ($n = 1$) e totalidade. Assim temos um [Monóide](/page%201.md#f8).

Contudo em uma álgebra de módulo temos uma situação um pouco diferente. Seja então a estrutura $(\frac{\mathbb{Z}}{n \mathbb{Z}}, \times)$, precisamos encontrar as condições para que tenhamos [Inversabilidade](/page%201.md#f9).

$a, b = a^{-1} \in \frac{\mathbb{Z}}{n \mathbb{Z}}$

Onde:

$a b - kn = 1$

---
---
---

## [Menu](/readme.md)

## [Página anterior](/page%203.md)

## [Topo](#f37)

## [Próxima página](/page%205.md)