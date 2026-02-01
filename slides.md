## Yang-Lee Edge singularities, Lee-Yang Zeroes, Lattice results

---

 <!-- .slide: data-transition="convex" -->

## First HIC at CERN, 15 years ago

<img src="img/robspics/ConfTitle.png" width="60%">
 <img src="img/robspics/TheFirstHeavyIonCollisionsAtTheLHC-HIC10.png" width="60%">

---

 <!-- .slide: data-transition="convex" -->

## My talk

<img src="img/robspics/mytalk10.png" width="90%">

---

 <!-- .slide: data-transition="convex" -->

## Rob's talk

<img src="img/robspics/robstalk1.png" width="60%">

---

 <!-- .slide: data-transition="convex" -->

## Rob's talk

<img src="img/robspics/robstalk2.png" width="60%">

---

 <!-- .slide: data-transition="convex" -->

## Rob's talk

<img src="img/robspics/robstalk1.png" width="50%">

<div class="medmath">

"... after _that_ talk, what I'm about to say shouldn't sound crazy. I mean, you just sat through a talk about extending the phase diagram
into the whole complex chemical potential plane. I just want to take $\mu$ purely imaginary to mimic $A_0$.
That's not crazy, right? Yeah? I'm practically doing normal physics... "

</div>

---

 <!-- .slide: data-transition="convex" -->

## In hindsight

Sixteen years ago I didn't know how to take this — compliment?! or insult!?

<div class="columns">
  <div class="column">

Since then, I've spent Christmases and New Years with Rob and his family, stayed at his house numerous times, bought a car from him, written about 23 papers together, and had plenty of arguments—often with expletives. And whenever life got hard, Rob was the first to call and invite me to stay. Through it all, I learned: Rob deeply cares about people. He is compassionate and kind to his core.

Today I would take this as a compliment.

  </div>
  <div class="column">

  <img src="img/robspics/wed.jpg" width="50%">

   </div>
</div>

---

 <!-- .slide: data-transition="convex" -->

## Rob's actual BD

<img src="img/robspics/ROBSBD.jpg" width="70%">

---

 <!-- .slide: data-transition="convex" -->

## YLE and CP

**Three dimensional Ising model for illustration:**

<div class="columns">
  <div class="column">

    <img src="img/IsingYLE.png" width="100%">

  </div>
  <div class="column">

<div class="medmath">

- Every CP has related YLEs
- When two YLEs pinch real axis $\leadsto$ critical point

Above $T_c$:

    <img src="img/extra/PhaseDiagram.png" width="50%">

  </div>
  </div>
</div>

---

 <!-- .slide: data-transition="convex" -->

## Second-order phase transition: Landau model

- To set up the stage, introduce notation and relevant concepts, best to consider Landau model

$$ F = \int d^{d} x \left( \frac{1}{2} {\color{red} t} \phi^2 + \frac{1}{4} \phi^4 - {\color{blue} h} \phi \right) $$

E.g.:

- near chiral limit: ${\color{red} t} \propto T-T_c + \kappa \mu^2$, ${\color{blue} h}\propto m_{u,d}$
- near CP: ${\color{red}t},{\color{blue}h} \propto \alpha_{t,h}(T-T_c) + \beta_{t,h} (\mu-\mu_c)$

---

 <!-- .slide: data-transition="convex" -->

## Equation of motion amd position of YLE

- Minimizing the free energy

$$ {t} \phi + \phi^3 - {h} = 0 $$

<div class="columns">
  <div class="column">

- Order parameter is massless when

$$ {t} + 3 \phi^2 = 0 $$

- These leads to

$$ h_c = \pm {\color{orange} i } \frac{2}{3 \sqrt{3}} t^{3/2}, \qquad \phi_c = \pm {\color{orange} i} \frac{1}{\sqrt{3}} t^{1/2} $$

 </div>

  <div class="column">
    <img src="img/extra/PhaseDiagram.png" width="50%">

  </div>
</div>
---

 <!-- .slide: data-transition="convex" -->

## Near the Edge

- What is the nature of the singularity?!
- Expansion of the Landau free energy in the vicinity of the singular point:
  $$\phi = \phi_c + \varphi, \\quad h = h_c + \delta h $$

$$F = F_c - \underbrace{(t \phi_c + \phi_c^3 - h_c)}\_{=0} \varphi + \frac{1}{2} \underbrace{(t + 3\phi_c^2)}\_{=0} \varphi^2 +  \phi_c \varphi^3 - \delta h  \varphi + \mathcal{O}(\varphi^4)$$
$$\approx F_c + \phi_c\\:  {\color{orange}\varphi^3} - \delta h\\: \varphi $$

---

 <!-- .slide: data-transition="convex" -->

## Near the Edge

$$F \approx F_c + \phi_c\\:  {\color{orange}\varphi^3}  - \delta h\\: \varphi $$

- This is $\phi^3$ theory with the imaginary coupling ($\phi_c$ is purely imaginary)

- How does the order parameter depends on $\delta h$ near the edge:

$$ \frac{\partial F }{\partial \varphi} = 3 \phi_c \varphi^2 - \delta h = 0 \quad \leadsto \varphi = \sqrt{\frac{1}{3\phi_c}} (\delta h)^{\color{magenta}\sigma} \quad \text{with } {\color{magenta}\sigma} = \frac{1}{2}$$

- Edge exponent $\sigma$ depends is superuniversal: depends only on number of dimensions

---

 <!-- .slide: data-transition="convex" -->

## Edge exponent beyond mean field

- $\varepsilon$ expansion near $d_c=6$ up to sixth loop order: $\sigma = 0.078(8)$ (2025)
- Functional RG: $\sigma = 0.0742(56)$ (2017)
- Truncated Conformal Bootstrap: $\sigma = 0.085(1)$ (2015) </br> systematics is not under control due to non-unitarity
- Truncated Conformal Bootstrap: $\sigma = 0.062$ (2018)
- Fuzzy Sphere: $\sigma = 0.077(6)$ (2025)

**$\sigma$ is not yet known to the same precision as critical exponents of other classical universality classes**

---

 <!-- .slide: data-transition="convex" -->

## Universal magnetic EoS

- For a given universality class, one can define the universal magnetic EoS

<div class="columns">
  <div class="column">

- In Landau model,
  $t \phi +  \phi^3 = h$
- Ansatz for the solution $\phi = h^{1/3} {\color{Emerald}f_G}$ </br>
  ${ \color{red}{\frac{t}{ h^{2/3}}} } {\color{Emerald}f_G}  + {\color{Emerald}f_G}^3 = 1$
- ${\color{Emerald} \text{Magnetic equation of state}}$
  $${\color{Emerald} f_G} ( {\color{red}{z}}  + {\color{Emerald}f_G}^2) = 1, \quad {\color{red}{ z  =  {\frac{t}{ h^{\frac1{\beta \delta}} }} } }, \text{with } \beta = 1/2, \delta=3 $$

</div>
  <div class="column">
<img  src="img/fg.png" width="98%">

</div>

</div>

---

 <!-- .slide: data-transition="convex" -->

## Universal location of YLE

- Singularity of ${\color{Emerald} f_G}$ defined by $ {\color{Emerald} f_G} ( {\color{red}{z}} + {\color{Emerald}f_G}^2) = 1$
- The location $z_c = |z_c| e^{\pm \frac{i \pi}{2 \beta \delta}}$, in Landau model $z_c = \frac{3}{2^{2/3}} e^{\pm i\pi/3} $

<div class="columns">
<div class="column">

**Beyond mean field:**

- $\varepsilon$-expansion
- lattice
- conformal bootstrap
- all of them fail

</div>
<div class="column">

<div class="medmath">
 $\varepsilon$-expansion:

- Underlying theory is $\phi^4$ with $d_c=4$; near YLE $\phi^3$, $d_c=6$

- Only _leading correction_ is under perturbative control; </br>
  expansion in $\varepsilon \ne$ expansion in loops

$$
|z_c| \approx  |z_c^{\rm MF}| \left[1 +  \frac{ 27 \ln \left(\frac{3}{2}\right) -  (N-1)  \ln 2}{9
(N+8)}\epsilon \right] + \epsilon^2 \log \epsilon \times  ( \text{all loops} )
$$

 </div>
 </div>
</div>

---

## FRG

- No sign problem
- Non-perturbative
- Working near second-order critical point $\leadsto$ justified truncation scheme
- Validated by computing critical exponents and amplitude ratios

 <div class="columns">
<div class="column">

| $N=1, d=3$ | $\nu$       | $\eta$        |
| ---------- | ----------- | ------------- |
| FRG        | 0.63012(16) | 0.0361(11)    |
| CB         | 0.629971(4) | 0.0362978(20) |

<div class="cite"> G. De Polsi, I. Balog, M. Tissier, N. Wschebor, 2001.07525   </div>
<div class="cite"> G. De Polsi, G. Hernández-Chifflet, N. Wschebor, 2109.14731   </div>

 </div>
<div class="column">
  <img  src="img/FRG_8_4.png" width="75%">

<div class="cite"> F. Rennecke and V. S, Annals Phys. 444 (2022) 169010 </div>

 </div>

---

## Universal location of YLE

<div class="medmath">

- Ising model for various number of dimensions

| d                                 | 1   | 2          | 3 (FRG)  | 4           |
| --------------------------------- | --- | ---------- | -------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma} $ | 1   | 1.32504(2) | 1.621(4) | $3/2^{2/3}$ |

<div class="cite">
F. Rennecke and V. S, Annals Phys. 444 (2022) 169010 <br>
$d=2$: H.-L. Xu and A. Zamolodchikov, JHEP 08 (2022) 057, 2304.07886
</div>

- $O(N)$ in three dimensions (FRG)

| N                                 | 1           | 2           | 3           | 4           |
| --------------------------------- | ----------- | ----------- | ----------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma} $ | 1.621(4)(1) | 1.612(9)(0) | 1.604(7)(0) | 1.597(3)(0) |

 <div class="cite">
G. Johnson, F. Rennecke, and V. S, Phys.Rev.D 107 (2023) 11,
116013 <br>
A. Connelly, G. Johnson, F. Rennecke, and V. S, Phys.Rev.Lett. 125 19, 191602
(2020) <br>
</div>

</div>

---

 <!-- .slide: data-transition="convex" -->

## What can we do with it?

---

 <!-- .slide: data-transition="convex" -->

## Mapping to radius of convergence; crossover line

Near chiral transition

 <div class="medmath">

\begin{align} z &= z_0 \left( \underbrace{\frac{m_l}{m_s}}\_{h}\right)^{-\frac{1}{\beta\delta}}
\times \left[\underbrace{ \frac{T-T_c}{T_c} + \kappa^B_2 \left( \frac{\mu}{T_c} \right)^2 +
\kappa^B_4 \left( \frac{\mu}{T_c} \right)^4 + \dots}\_t \right] = z_c \end{align}

</div>

<div style="align:center;">
<img src="img/R.png"  width="45%">
<img src="img/T_muB_elliptic_compare_Ns_1panel.png"  width="39.5%">
</div>

<div class="cite">
Left fig.: S. Mukherjee, V.S., 1909.04639; Right fig.: D.A. Clarke et al, 2601.04782
</div>

---

 <!-- .slide: data-transition="convex" -->

## Critical end point

- Every critical point has associated Yang-Lee edge singularitie.
- Does existence of YLEs imply an existence of a finite $T$ critical point?
- Unfortunate no... Canonical example: one-dimensional Ising model:

 <div class="columns">
  <div class="column">
  <span class="fragment fade-in" data-fragment-index="1">
  Phase diagram
         <img src="img/extra/1dIsingYLE.png" width="81%">
  </span>
  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="2">
  $\chi_2$

  <img src="img/extra/1dIsingc2.png" width="91%">
  </span>

  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="3">
  $\chi_4$

  <img src="img/extra/1dIsingc4.png" width="100%">
  </span>

  </div>
 </div>

---

 <!-- .slide: data-transition="convex" -->

## YLE $\to$ CP

Thus:

 <div class="columns">
  <div class="column">

- Locate and trace YLE as a function of $T$
- Find when/if they approach real values of thermodynamic parameters (e.g. $\mu$)
- Pretty ambitious program given that we do not have
  <br> 1. direct access to complex chemical
  <br> 2. low uncertainty low $T$ lattice data

 <div class="warning-box">
⚠️ Double extrapolation
</div>
</div>

<div class="column">
  <img src="img/DoubleExtra.png" width=80% >

</div>
</div>

---

 <!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T_c<T<T_{RW}$

<img src="img/YLEs.png" width=50% >

<div class="cite">
M. Stephanov, hep-lat/0603014
</div>

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_c$

<img src="img/YLEtoTc.png" width=50% >

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_{RW}$

<img src="img/YLEtoRW.png" width=50% >

- Roberge-Weiss critical point is at purely imaginary chemical potential
- Direct access in lattice QCD; provides a check on methods

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: chiral critical point

Lattice input:

 <div class="columns">
  <div class="column">

- Taylor series coeff. + conformal Pade

<img src="img/BasarYLE.png" height=300em >
</div>
  <div class="column">

- Im $\mu$ + Pade

<img src="img/LatticeYLElocation.png" height=300em >
</div>
</div>

<div class="cite">
G. Basar, 2312.06952 <br>
D. Clarke et. al., 2405.10196
</div>

---

<!-- .slide: data-transition="convex" -->

## Details: extrapolation to lower $T$

 <div class="columns">
  <div class="column">

- At measured $T$, Im $\mu\_{YLE} \ne 0 $

- Extrapolated using the universal scaling of YLE:

<div class="medmath">

1. $t/h^{1/\beta \delta} = z_c = $ universal number

2. and linear mapping
   $$t = \alpha_t(T - T_{CEP}) + \beta_t(\mu_B - \mu_{CEP})$$
   $$h = \alpha_h(T - T_{CEP}) + \beta_h(\mu_B - \mu_{CEP})$$

</div>
 </div>
<div class="column">
<img src="img/LatticeYLElocation.png" height=300em >

 </div>
 </div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: estimate for critical point

 <img src="img/LatticeQCDPD.png" height=400em >

- Somewhat consistent with $16^3\times 8$ study by Adam et al, arXiv: 2507.13254:

"84% probability the CP either lies below T = 103 MeV or does not exist"

- Consistent with Basar, 2312.06952: $T \approx 100$ MeV, $\mu_c \approx 580$ MeV

<div class="cite">
     Clarke et al, 2405.10196
 </div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: systematics

 <img src="img/DoubleExtra.png" height=450em >

 <div class="warning-box">
⚠️ Double extrapolation
</div>

---

<!-- .slide: data-transition="convex" -->

## YLE trajectory: LQCD vs DSE

<span class="fragment">
 <img src="img/qcdtraj.png"  width="40%">
</span>
<span class="fragment">
<img src="img/YLEtraj.jpg"  width="44.5%">
</span>

<div class="cite">
Lattice:  Clarke et al, 2405.10196
</br>
DSE: Z.-Y. Wan, Y. Lu, F. Gao, and Y.-X. Liu, 2504.12964
 </div>

Quantitatively the YLE trajectories are very different

---

<!-- .slide: data-transition="convex" -->

## Conclusions

- Encouraging results

**Several sources of systematical uncertainty:**

- Double extrapolation

- Linear mapping to $(t, h) \to (T, \mu)$

- Applying $t/h^{1/\beta \delta} = z_c$ in a wide range of temperatures 120 MeV $\le T \le $ 166.6 MeV with $T_c \approx 100$ MeV

- The last two points apply to the Roberge-Weiss critical point too (166.6 MeV $\le T \le $ 201.4 MeV); the extracted $T_{RW} \approx 211$ MeV coincides with
  direct lattice simulations

- Continuum limit

**YLE trajectory in DSE is qualitatively different from LQCD**

---

<!-- .slide: data-transition="convex" -->

## Why complex $\mu$?

- Complex $T$ also probes the same singularities
- While complex $T$ plane does not have periodicity issues
- Fermi dist. function singularity is at purely imaginary $T$; far from the region of interest

 <img src="img/QMM_ReT_mu.png" height=400em >
 <img src="img/QMM_ImT_mu.png" height=400em >

---

<!-- .slide: data-transition="convex" -->

## From Lattice QCD

 <img src="img/Lattice_finiteNt_ReT.png" height=350em >
 <img src="img/Lattice_finiteNt_ImT.png" height=350em >

<div class="medmath">

Input:

- $\chi_2 (T, \mu=0)$ for various $N_\tau$
- Statistical error estimate: 20 Jackknife samples
- Systematic error estimate: various Pad\'e orders

</div>

<div class="cite">
 Data from: S. Borsanyi et al. 2102.06660 \& private communications with S. Borsanyi
</div>

---

<!-- .slide: data-transition="convex" -->

# Backup

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: estimate for critical point

 <img src="img/LatticeQCDPD.png" height=500em >

<div class="cite">
     Clarke et al, 2405.10196
 </div>

---

 <!-- .slide: data-transition="convex" -->

## Lattice: numerics

 <div class="columns">
  <div class="column">

- HISQ action, $N_f$ = 2 + 1 flavours
- $36^3 \times 6$ lattices
- Observable: $\chi^B_{1,2}(T, \mu_B)$
- 5 temperatures: $T = 120.0, 136.1, 157.5, 166.6$ MeV
- 10 imaginary chemical potentials between 0 and $i\pi$

</div>
  <div class="column">

 <img src="img/DataLattice.png" height=500em >

 </div>
 </div>

 <div class="cite">
     From  the presentation by Zambello at
     <a href="https://indico.ectstar.eu/event/243/contributions/5891/attachments/3964/5790/ecstar25_zambello.pdf">ECT* 2025</a>
</div>

---

 <!-- .slide: data-transition="convex" -->

## Details: sliding window

 <div class="columns">
  <div class="column">

- Approximate $\chi_{1,2}^B(T, \mu_B)$ with a rational function

- Calculate zeros of the numerator and denominator

- Remove near cancelling pairs, keep poles in the first quadrant closest to the center of the interval

- Bootstrap over the data

- Iterate over 55 intervals of varying length (from $\pi$ to $2\pi$) and center

- Perform scaling fits on randomly chosen intervals and collect the results for further analysis ($10^5$ fits)

</div>
  <div class="column">

 <img src="img/Sliding.png" height=500em >

 </div>
 </div>

 <div class="cite">
     From  the presentation by Zambello at
     <a href="https://indico.ectstar.eu/event/243/contributions/5891/attachments/3964/5790/ecstar25_zambello.pdf">ECT* 2025</a>
</div>

---

 <!-- .slide: data-transition="convex" -->

 <div class="columns">

  <div class="column">
  Phase diagram
         <img src="img/extra/PhaseDiagramImh14.png" width="80.6%">
  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="2">
 $\chi_2$

     <img src="img/extra/c2plotMFline1.4.png" width="100%">
     <img src="img/extra/c2plotMF14.png" width="100%">

  </span>

  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="3">
 $\chi_4$

     <img src="img/extra/c4plotMFline1.4.png" width="100%">
     <img src="img/extra/c4plotMF14.png" width="100%">

  </span>

  </div>
 </div>

---

 <!-- .slide: data-transition="convex" -->

 <div class="columns">

  <div class="column">
  Phase diagram
         <img src="img/extra/PhaseDiagramImh11.png" width="80.6%">
  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="2">
 $\chi_2$

     <img src="img/extra/c2plotMFline1.1.png" width="100%">
     <img src="img/extra/c2plotMF11.png" width="100%">

  </span>

  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="3">
 $\chi_4$

     <img src="img/extra/c4plotMFline1.1.png" width="100%">
     <img src="img/extra/c4plotMF11.png" width="100%">

  </span>

  </div>
 </div>

---

 <!-- .slide: data-transition="convex" -->

- Every CP has YLEs. Is the reverse true?
- Does existence of YLEs imply an existence of a finite $T$ critical point?
- Unfortunate no... Canonical example: one-dimensional Ising model

 <div class="columns">
  <div class="column">
  <span class="fragment fade-in" data-fragment-index="1">
  Phase diagram
         <img src="img/extra/1dIsingYLE.png" width="81%">
  </span>
  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="2">
  $\chi_2$

  <img src="img/extra/1dIsingc2.png" width="91%">
  </span>

  </div>

  <div class="column">
  <span class="fragment fade-in" data-fragment-index="3">
  $\chi_4$

  <img src="img/extra/1dIsingc4.png" width="100%">
  </span>

  </div>
 </div>

---

## Universal location of YLE

For each universality class:

- universal magnetic equation of state
- **universal location of YLE singularity**
- mapping to QCD requires non-universal parameters

| d                                | 1   | 2          | 3        | 4           |
| -------------------------------- | --- | ---------- | -------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma}$ | 1   | 1.32504(2) | 1.621(4) | $3/2^{2/3}$ |

---

<!-- .slide: data-transition="convex" -->

## Back to QCD phase diagram

<img src="img/phase.png" width="45%">
<img src="img/RWMODEL.png" width="37%">

---

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T_c<T<T_{RW}$

<img src="img/YLEs.png" width=50% >

<div class="cite">
M. Stephanov, hep-lat/0603014
</div>

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_c$

<img src="img/YLEtoTc.png" width=50% >

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_{RW}$

<img src="img/YLEtoRW.png" width=50% >

---

## Naive mapping

<!-- .slide: data-transition="convex" -->

Near chiral transition

 <div class="medmath">

\begin{align} z &= z_0 \left( \frac{m_l}{m_s}\right)^{-\frac{1}{\beta\delta}}
\times \left[ \frac{T-T_c}{T_c} + \kappa^B_2 \left( \frac{\mu}{T_c} \right)^2 +
\kappa^B_4 \left( \frac{\mu}{T_c} \right)^4 + \dots \right] \,. \label{eq:z}
\end{align}

</div>

<img src="img/R.png"  width="40%">

<div class="cite">
S. Mukherjee, V.S., 1909.04639
</div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: RW critical point

Lattice QCD and indirect methods to locate YLE:

input from Im $\mu$ \& analytic continuation

<img src="img/RW_YLE.png" height=280em >

$$
  z = z_c \to \text{Re} \mu_{YLE} \propto (T_{RW}-T)^{\beta \delta} \quad \leadsto T_{RW} = 211.1 \pm 3.1 \text{MeV}.
$$

<div class="cite">
 C. Schmidt et al,     2209.04345
</div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: chiral critical point

Lattice input from Taylor series coeff. at $\mu=0$ or Im $\mu$ \& analytic
continuation

<img src="img/BasarYLE.png" height=300em >
<img src="img/LatticeYLElocation.png" height=300em >

<div class="cite">
G. Basar, 2312.06952 <br>
D. Clarke et. al., 2405.10196
</div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: estimate for critical point

 <div class=smallmath>
$$ T_c \approx 110 \text{ MeV} , \mu_c \approx 650 \text{ MeV}$$
</div>

 <img src="img/LatticeQCDPD.png" height=300em >

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: systematics

 <img src="img/DoubleExtra.png" height=300em >

 <div class="warning-box">
⚠️ Double extrapolation
</div>

---

<!-- .slide: data-transition="convex" -->

## Interval dependence

<span class="fragment">

<img src="img/intervaldep.png" height=300em >

</span>

<span class="fragment">

- Are there exact results?

</span>

<span class="fragment">

- Interpolating from imaginary line vs Taylor series: "radius of convergence" is
  due to the singularity closest to the line vs closest to the expansion point

 </span>

---

<!-- .slide: data-transition="convex" -->

## Second LYZ

- Any hope to perform finite volume analysis?

---

<!-- .slide: data-transition="convex" -->

## Re $\mu_{YLE}$ and the relation to the crossover line

 <img src="img/IsingYLE.png"  width="50%">

Lattice analyses of LYZ gives the parametrization for Re $\mu_{YLE}$ and Im
$\mu_{YLE}$ near the point where the latter quantity vanishes. Does the line
$\mu = Re \mu_{YLE} (T)$ follow the "crossover" line?

---

<!-- .slide: data-transition="convex" -->

## Re $\mu_{YLE}$ and the relation to the crossover line

 <img src="img/Pade_dep.png"  width="30%">

- Current QCD calculations use Pade[3,3], Pade[4,4], Pade[5,5]

- If the shape of the curve depends on the position of the singularity, it may
  fake the YLE trajectory

---

<!-- .slide: data-transition="convex" -->

## Scaling for strange neutral eos?

<img src="img/scaling.png"  width="50%">

- What is the origin?
- Very large values of $z$...

---

<!-- .slide: data-transition="convex" -->

<!-- .slide: data-transition="convex" -->

## Scaling: Model

<img src="img/scale1.png"  width="90%">

- Why not the pion mass...
- Very large values of $z$...

_Braun and Klein_

---

<!-- .slide: data-transition="convex" -->

## Scaling: Model

<img src="img/scale2.png"  width="90%">

- Why not the pion mass...
- Very large values of $z$...

_Braun and Klein_

---

<!-- .slide: data-transition="convex" -->

## Scaling: Model

<img src="img/scale3.png"  width="90%">

- Why not the pion mass...

_Braun and Klein_

---

<!-- .slide: data-transition="convex" -->

## Scaling: LQCD

<img src="img/scale.jpg"  width="50%">

- The scaling is not perfect
- Quite significant deviation rate at small masses
- Why not to use the conventional normalization...

---

<!-- .slide: data-transition="convex" -->

## YLE trajectory... DSE, LQCD, what about FRG?

<img src="img/YLEtraj.jpg"  width="44.5%">
<img src="img/qcdtraj.png"  width="40%">

---

<!-- .slide: data-transition="convex" -->

## Lifshitz point; corresponding YLE?

<img src="img/moat.jpg"  width="50%">
