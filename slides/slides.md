# Contribuções quantitativas <br /> para a elucidação de <br /> mecanismos de reação

[Me. Felipe S. S. Schneider](https://schneiderfelipe.github.io/)
<br /><br />
Supervisor: Prof. Dr. Giovanni F. Caramori
<br />
Co--supervisor: Prof. Faruk J. N. Aguilera (_in memoriam_)

<div class="text-sm mt-8">
  06 / 01 / 2023
</div>

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Welcome

- Research problem
- Results and discussion
- Conclusions

TODO.

<!--
Presentation introduction starts.

Audience welcome with a table of contents.
-->

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Research problem

- Elucidating mechanisms has great potential
- Elucidating mechanisms is hard
- Errors
- There is a way out

<!--
Motivation.

What are we solving?
-->

---

# Research reason

- Potential
- Things the experiment can't solve
- Reason behind why some things work

<!--
Why are we doing this?
-->

---

# Research question

Can we predict reactions from first principles?

<!--
What's our target?

Objectives.
-->

---

# Idea

Key project idea.

## Contribution

Key relevant contribution.

---

# Effectiveness

What works expected in _our approach_?

# Efficiency

What makes _our approach_ faster and/or cheaper?

# Attractiveness

What makes _our approach_ more interesting?

<!-- Presentation introduction ends. -->

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Results and discussion

- _ACS Catalysis_ **2019**, 9 (5), 3792--3799. [10.1021/acscatal.9b00210](https://doi.org/10.1021/acscatal.9b00210).
- _Journal of the American Chemical Society_ **2020**, 142 (24), 10869--10880. [10.1021/jacs.0c01622](https://doi.org/10.1021/jacs.0c01622).
- _Journal of Computational Chemistry_ **2022**, 44 (3), 209--217. [10.1002/jcc.26861](https://doi.org/10.1002/jcc.26861).

<!--
List of papers,
products.
-->

---

# Mechanism of $\ce{Pd(II)}$--Mediated Uncaging Reactions of Propargylic Substrates

## Method

- <span v-click=1>ORCA 4.0.1.2</span>
- <span v-click=4>RIJCOSX</span>--<span v-click=2>PBE0--D3(BJ)</span>/<span v-click=3>ma--def2--TZVP(-f)</span>/<span v-click=5>SMD(water)</span>
- <span v-click=6>Small imaginary frequencies ($<34 i \text{ cm}^{-1}$)</span>
- <span v-click=8>DLPNO--CCSD(T)</span>--<span v-click=9>gCP</span>/<span v-click=7>ma--def2-TZVP(-f)</span>
- <span v-click=10>$G_{1 \text{M}} = G_{1 \text{atm}} + R T \ln{V}$ at 298.15 K and 1 atm</span>

<!--
$R T \ln{V} = 2.1984 \text{kcal/mol}$
-->

<!-- prettier-ignore-start -->

---
clicks: 9
---

<!-- prettier-ignore-end -->

# $\ce{Pt}$--Triggered Bond--Cleavage of Pentynoyl Amide and $\ce{N}$--Propargyl Handles for Drug--Activation

## Method

- <span v-click=1>rev--PBE0--D4</span>--<span v-click=3>gCP</span>/<span v-click=1>def2--TZVP</span>
- <span v-click=2>DLPNO--CCSD(T)</span>--<span v-click=3>gCP</span>/<span v-click=2>def2--TZVP</span>/<span v-click=2>SMD(water)</span>
- <span v-click=4>ORCA 4.2.1</span>
- <span v-click=5>Crest/GFN2--xTB (xtb 6.3.0)</span>
- <span v-click=6>NEB/GFN2-xTB (ORCA 4.2.1, xtb 6.3.0)</span>
- <span v-click=7>Metadynamic simulation ($\ce{Pt(II)}\cdots$triple bond for $\ce{X} = \ce{C}$, movie)</span>
- <span v-click=8>Thermodynamics at 298.15 K and 1 M</span>
<!-- $G_{1 \text{M}} = G_{1 \text{atm}} + R T \ln{V}$ at 298.15 K and 1 atm -->
- <span v-click=9>Wigner tunneling transmission coefficients ($\kappa = 1 + \frac{1}{24} \left( \frac{h |\nu|}{R T} \right)^2$)</span>
<!-- - Small imaginary frequencies ($<34 i \text{ cm}^{-1}$) -->

<!--
$R T \ln{V} = 2.1984 \text{kcal/mol}$
-->

---

# **Overreact**, an _in silico_ lab

Automative quantum chemical microkinetic simulations for complex chemical reactions

$$
\ce{NH3(w) + ^{.}OH(w) ->[H3N\cdots{}^{.}OH(w)] ^{.}NH2(w) + H2O(w)}
$$

```kotlin {monaco}
$scheme
 NH3(w) + OH·(w) -> NH3·OH#(w) -> NH2·(w) + H2O(w)

$compounds
 NH3(w):     NH3.out
 OH·(w):     OH_rad.out
 NH2·(w):    NH2_rad.out
 H2O(w):     H2O.out
 NH3·OH#(w): NH3_OH_ts.out
```

<!--
::: warning
_here be dragons_
:::
-->

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

<Transform :scale=0.8>

$$
\ce{NH3(w) + ^{.}OH(w) ->[H3N\cdots{}^{.}OH(w)] ^{.}NH2(w) + H2O(w)}
$$

</Transform>

- M062X--D3(0)/6--311++G(d,p)/SMD(water)
- ORCA 4.2.1

::right::

|                                | k (M$^{-1}$s$^{-1}$) |
| -----------------------------: | -------------------: |
| Hickel and Sehested[^1] (exp.) |    $9.7 \times 10^7$ |
|        Men'kin _et al._ (exp.) |    $7.0 \times 10^7$ |
|           Neta _et al._ (exp.) |    $9.0 \times 10^7$ |
|               **Ours (calc.)** |    $1.1 \times 10^8$ |
|           Dib _et al._ (calc.) |    $2.3 \times 10^7$ |

[^1]: Hickel

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Conclusions

---

# Question reminder

## Topic overview reminder

<!-- Presentation conclusion starts. -->

---

More slides requiring results and discussion.

TODO.

<!-- prettier-ignore-start -->

---
layout: section
---

<!-- prettier-ignore-end -->

# Obrigado!

[schneiderfelipe.github.io](https://schneiderfelipe.github.io/)
<br />
<schneider.felipe.5@gmail.com>
<br />
<Thanks />

<!-- Presentation conclusion ends. -->
