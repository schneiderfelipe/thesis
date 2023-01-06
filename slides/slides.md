---
monaco: true
colorSchema: "light"
---

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

<!--
Presentation introduction starts.

Audience welcome with a table of contents.
-->

<!-- prettier-ignore-start -->

---
layout: section
---

<!-- prettier-ignore-end -->

# Research problem

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

## Elucidating mechanisms has great potential in **rational design**

<br />

<v-clicks>

- Chemical biology and medicinal chemistry (e.g., activating proteins and prodrugs)
- Atmospheric chemistry (e.g., climate change mitigation)
- Green chemistry (e.g., leaner industrial processes)

</v-clicks>

<!--
Motivation.

What are we solving?

Help experimentalists.
-->

<!--
Why are we doing this?
-->

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

<!--
What's our target?

Objectives.
-->

## Can we _quantitatively_ elucidate <br /> chemical reaction mechanisms <br /> using computational chemistry _only_?

<!--
- Faster route to reaction development
- Faster and cheaper
-->

<!-- Presentation introduction ends. -->

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Results

<v-clicks>

- _ACS Catalysis_ **2019**, 9 (5), 3792--3799. [10.1021/acscatal.9b00210](https://doi.org/10.1021/acscatal.9b00210).

  - Theoretical-experimental investigation

- _Journal of the American Chemical Society_ **2020**, 142 (24), 10869--10880. [10.1021/jacs.0c01622](https://doi.org/10.1021/jacs.0c01622).

  - Theoretical-experimental investigation

- _Journal of Computational Chemistry_ **2022**, 44 (3), 209--217. [10.1002/jcc.26861](https://doi.org/10.1002/jcc.26861).
  - Software developed (**overreact**)
  - Two reactions presented

</v-clicks>

<!--
List of papers,
products.
-->

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

# Mechanism of <br /> $\ce{Pd(II)}$--Mediated Uncaging Reactions of Propargylic Substrates[^paper1]

<br />

<span v-click=2>

- ORCA 4.0.1.2: RIJCOSX--PBE0--D3(BJ)/ma--def2--TZVP(-f)/SMD(water)

- DLPNO--CCSD(T)--gCP/ma--def2-TZVP(-f)

- $G_{1 \text{M}} = G_{1 \text{atm}} + R T \ln{V}$ at 298.15 K and 1 atm

</span>

<!--
$R T \ln{V} = 2.1984 \text{kcal/mol}$
-->

[^paper1]: _ACS Catal._ **2019**, 9 (5), 3792--3799. [10.1021/acscatal.9b00210](https://doi.org/10.1021/acscatal.9b00210).

::right::

<span v-click=1>

<Transform :scale=0.8>

![](/paper1-proposal.jpeg)

</Transform>

</span>

<span v-click=3>

<Transform :scale=0.9>

![](/paper1-reaction.jpeg)

</Transform>

</span>

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

### $\ce{Pt}$--Triggered Bond--Cleavage of Pentynoyl Amide and $\ce{N}$--Propargyl Handles for Drug--Activation[^paper2]

<br />

<span v-click=1>

<Transform :scale=0.65>

- ORCA 4.2.1
  - rev--PBE0--D4--gCP/def2--TZVP
  - DLPNO--CCSD(T)--gCP/def2--TZVP/SMD(water)
- Crest/GFN2--xTB (xtb 6.3.0)
- NEB/GFN2-xTB (ORCA 4.2.1, xtb 6.3.0)
- Metadynamic simulation ($\ce{Pt(II)}\cdots$triple bond for $\ce{X} = \ce{C}$)
- Thermodynamics at 298.15 K and 1 M
<!-- $G_{1 \text{M}} = G_{1 \text{atm}} + R T \ln{V}$ at 298.15 K and 1 atm -->
- Wigner tunneling transmission coefficients <br /> ($\kappa = 1 + \frac{1}{24} \left( \frac{h |\nu|}{R T} \right)^2$)

<!--
$R T \ln{V} = 2.1984 \text{kcal/mol}$
-->

</Transform>

[^paper2]: _J. Am. Chem. Soc._ **2020**, 142 (24), 10869--10880. [10.1021/jacs.0c01622](https://doi.org/10.1021/jacs.0c01622).

</span>

<span class="absolute bottom-60px right-28.5rem max-w-15rem">

![](/paper2-toc.jpeg)

</span>

::right::

<span v-click=1 class="float-right">

<Youtube id="k5ptn50Zjkc" width=400 height=400 />

</span>

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

### $\ce{Pt}$--Triggered Bond--Cleavage of Pentynoyl Amide and $\ce{N}$--Propargyl Handles for Drug--Activation[^paper2]

<br />

<Transform :scale=0.65>

- ORCA 4.2.1
  - rev--PBE0--D4--gCP/def2--TZVP
  - DLPNO--CCSD(T)--gCP/def2--TZVP/SMD(water)
- Crest/GFN2--xTB (xtb 6.3.0)
- NEB/GFN2-xTB (ORCA 4.2.1, xtb 6.3.0)
- Metadynamic simulation ($\ce{Pt(II)}\cdots$triple bond for $\ce{X} = \ce{C}$)
- Thermodynamics at 298.15 K and 1 M
<!-- $G_{1 \text{M}} = G_{1 \text{atm}} + R T \ln{V}$ at 298.15 K and 1 atm -->

<!--
$R T \ln{V} = 2.1984 \text{kcal/mol}$
-->

</Transform>

[^paper2]: _J. Am. Chem. Soc._ **2020**, 142 (24), 10869--10880. [10.1021/jacs.0c01622](https://doi.org/10.1021/jacs.0c01622).

<span class="absolute bottom-60px right-28.5rem max-w-15rem">

![](/paper2-toc.jpeg)

</span>

::right::

<span class="float-right">

![](/paper2-reaction.png)

<span class="float-right">

<v-clicks>

- $\ce{X} = \ce{O}$ (blue)
- $\ce{X} = \ce{CH2}$ (black)

</v-clicks>

</span>

</span>

<!-- prettier-ignore-start -->

---
layout: two-cols
clicks: 4
---

<!-- prettier-ignore-end -->

<span v-click=3>

# **Overreact**, <br /> an _in silico_ lab[^paper3]

Automative quantum chemical microkinetic simulations for complex chemical reactions

</span>

<HickelReaction />

<small v-click=1>

- ORCA 4.2.1: M062X--D3(0)/6--311++G(d,p)/SMD(water)

</small>

<span v-click=2>

<HickelInput />

</span>

::right::

<span v-click=3>

<Transform :scale=0.9125>

<OverreactLogo />

</Transform>

</span>

<Transform :scale=0.9>

<span v-click=4>

|                            | k (M$^{-1}$s$^{-1}$) |
| -------------------------: | -------------------: |
| Hickel and Sehested (exp.) |    $9.7 \times 10^7$ |
|    Men'kin _et al._ (exp.) |    $7.0 \times 10^7$ |
|       Neta _et al._ (exp.) |    $9.0 \times 10^7$ |
|           **Ours (calc.)** |    $1.1 \times 10^8$ |
|      Dzib _et al._ (calc.) |    $2.3 \times 10^7$ |

</span>

</Transform>

<!--
Hickel reaction
-->

[^paper3]: _J. Comput. Chem._ **2022**, 44 (3), 209--217. [10.1002/jcc.26861](https://doi.org/10.1002/jcc.26861).

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

# **Overreact**, an _in silico_ lab

Automative quantum chemical microkinetic simulations for complex chemical reactions

<HickelReaction />

<small>

- ORCA 4.2.1: M062X--D3(0)/6--311++G(d,p)/SMD(water)

</small>

<HickelInput />

::right::

<OverreactLogo />

<span class="float-right max-w-25rem">

![](/hickel-compare.png)

</span>

<!--
Hickel reaction
-->

<!-- prettier-ignore-start -->

---
layout: center
---

<!-- prettier-ignore-end -->

<OverreactDiagram />

<span class="absolute right-20px bottom-20px">

<OverreactLogo />

</span>

---

<Transform :scale=0.675>

![](/tanaka.png)

</Transform>

<div class="absolute right-20px bottom-60px max-w-20rem text-sm">

$$
\ce{CH4 + Cl^{.} -> CH3 + HCl}
$$

<br />
<br />
<br />

<v-clicks>

- $9.29 \times 10^{−14}$ cm$^3$molecule$^{−1}$s$^{−1}$ (calc., **ours**)

- $2.20 \times 10^{−14}$ cm$^3$molecule$^{−1}$s$^{−1}$[^tanaka] (calc.)

- $1.03 \times 10^{−13}$ cm$^3$molecule$^{−1}$s$^{−1}$ (exp.)

- $\kappa = 3.64$

- $r^2 = 0.9984$ in 181 -- 300 K

- 250, 100, and 25 nM for $\ce{CH4}$, $\ce{Cl^{.}}$, and $\ce{HCl}$.

[^tanaka]: _J. Atmos. Chem._ **1996**, 23 (1), 37–49. [10.1007/bf00058703](https://doi.org/10.1007/bf00058703).

</v-clicks>

</div>

<!--
Confidence interval is 95%.
-->

---

<v-clicks>

<span class="absolute top-20px left-40px max-w-20rem">

![](/Perez-Soto2020-scheme1.png)

</span>

<span class="absolute bottom-20px left-40px max-w-20rem">

![](/Perez-Soto2020.png)

<small>

_Organic Letters_ **2020**, 22 (8), 2873–2877. [10.1021/acs.orglett.0c00367](https://doi.org/10.1021/acs.orglett.0c00367).

</small>

</span>

<span class="absolute top-60px right-40px max-w-30rem">

![](/Perez-Soto2020-reaction.png)

</span>

</v-clicks>

---

<span class="absolute top-20px left-40px max-w-20rem">

![](/Perez-Soto2020-scheme1.png)

</span>

<span class="absolute bottom-20px left-40px max-w-20rem">

![](/Perez-Soto2020.png)

<small>

_Organic Letters_ **2020**, 22 (8), 2873–2877. [10.1021/acs.orglett.0c00367](https://doi.org/10.1021/acs.orglett.0c00367).

</small>

</span>

<span class="absolute top-20px right-40px w-35rem">

<PerezSotoInput />

<v-clicks>

```shell
overreact model.k "Benzaldehyde(dcm): 0.06" "NButylamine(dcm) : 0.06" \
  "Water(dcm): 0.001" --bias=3.2 --plot=active --max-time 5000
```

</v-clicks>

</span>

---

<span class="absolute top-20px left-40px max-w-20rem">

![](/Perez-Soto2020-scheme1.png)

</span>

<span class="absolute bottom-20px left-40px max-w-20rem">

![](/Perez-Soto2020.png)

<small>

_Organic Letters_ **2020**, 22 (8), 2873–2877. [10.1021/acs.orglett.0c00367](https://doi.org/10.1021/acs.orglett.0c00367).

</small>

</span>

<span class="absolute top-20px right-160px w-20rem">

![](/Perez-Soto2020-output.png)

</span>

---

<span class="absolute top-20px left-40px max-w-20rem">

![](/Perez-Soto2020-scheme1.png)

</span>

<span class="absolute bottom-20px left-40px max-w-20rem">

![](/Perez-Soto2020.png)

<small>

_Organic Letters_ **2020**, 22 (8), 2873–2877. [10.1021/acs.orglett.0c00367](https://doi.org/10.1021/acs.orglett.0c00367).

</small>

</span>

<span class="absolute top-80px right-40px max-w-30rem">

![](/Perez-Soto2020-compare.png)

<v-clicks>

- RMSD = 4.97 mM (**total error**)

</v-clicks>

</span>

<!-- prettier-ignore-start -->

---
layout: center
---

<!-- prettier-ignore-end -->

![](/kirby-reaction.png)

<span class="absolute bottom-20px left-30px max-w-30rem">

<small>

Kirby _et al._ _J.C.S., Perkin II_ **1974**, No. 12, 1487. [10.1039/p29740001487](https://doi.org/10.1039/p29740001487).

</small>

</span>

<span class="absolute bottom-20px right-40px max-w-30rem">

<v-clicks>

- **low pH only**

</v-clicks>

</span>

---

![](/maleamic-reaction.png)

<span class="absolute bottom-20px left-30px max-w-30rem">

<small>

Kirby _et al._ _J.C.S., Perkin II_ **1974**, No. 12, 1487. [10.1039/p29740001487](https://doi.org/10.1039/p29740001487).

</small>

</span>

<span class="absolute bottom-20px right-40px max-w-30rem">

<v-clicks>

- Gaussian 09rC.01: $\omega$B97XD/6--311++G\*\*/SMD(water)

</v-clicks>

</span>

<!--
I‡ around 28.8 kcal mol-1 without water (kappa = 960), reduces to 13.6 kcal mol-1 with a single water (1.08).

Through C and rest-state J.
-->

<!-- prettier-ignore-start -->

---
layout: two-cols
---

<!-- prettier-ignore-end -->

<Transform :scale=0.85>

![](/kirby-ph.png)

</Transform>

<span class="absolute bottom-20px left-30px max-w-30rem">

<small>

Kirby _et al._ _J.C.S., Perkin II_ **1974**, No. 12, 1487. [10.1039/p29740001487](https://doi.org/10.1039/p29740001487).

</small>

</span>

::right::

<span class="float-right max-w-20rem">

![](/kirby-ph-compare-A.png)

![](/kirby-ph-compare-B.png)

</span>

<span class="absolute top-20px right-24rem max-w-30rem">

<v-clicks>

- _pseudo_-first order ($\ce{H2O}$ 55.6 M)

- **(B)**: pH 2

</v-clicks>

</span>

<!-- prettier-ignore-start -->

---
layout: cover
---

<!-- prettier-ignore-end -->

# Conclusions

<!-- prettier-ignore-start -->

---
layout: center
---

<!-- prettier-ignore-end -->

# Conclusions

<v-clicks>

- Four relatively complex reactions

- Insight to the experimentalist

- Feasable to reproduce experiment in a _semi_- or fully-quantitative way

</v-clicks>

<!-- Presentation conclusion starts. -->

<!-- prettier-ignore-start -->

---
layout: center
---

<!-- prettier-ignore-end -->

# Future work

<v-clicks>

- Automatic _discovery_ of chemical reaction mechanisms

- More effects

  - Translation entropy in solution

- More experiments reproduced
  - Kinetic isotope effects (KIE)
  - Spectroscopies along the reaction in time

</v-clicks>

<!-- prettier-ignore-start -->

---
layout: section
---

<!-- prettier-ignore-end -->

# Obrigado!

<span class="absolute bottom-4rem right-25rem">

<OverreactLogo />

</span>

[schneiderfelipe.github.io](https://schneiderfelipe.github.io/)
<br />
<schneider.felipe.5@gmail.com>
<br />
<Thanks />

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

**[geem-lab.github.io/overreact-guide](https://geem-lab.github.io/overreact-guide/)**

<!-- Presentation conclusion ends. -->
