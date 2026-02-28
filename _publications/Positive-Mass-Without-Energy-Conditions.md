---
title: Positive mass in general relativity without energy conditions
type: article
date: 2025-02-11
author: 
 - nick
 - agsl
 - bac
abstract: 'A long-standing problem in physics is why observed masses are always positive. While energy conditions in quantum field theory can partly answer this problem, in this paper we find evidence that classical general relativity abhors negative masses, without the need for quantum theory or energy conditions. This is done by considering many different models of negative-mass "stars" and showing they are dynamically unstable. <i>A fortiori</i>, we show that any barotropic negative-mass star must be dynamically unstable.'
journal: Physical Review D
volume: '111'
number: '4'
pages: '044027'
doi: '10.1103/PhysRevD.111.044027'
arxiv: "2408.00154"
arxivclass: gr-qc
inspire: '2813778'
stage: phd
tags: 
    - EnergyConditions 
    - GR
permalink: /abs/2408.00154/
---

## Introduction

A long-standing problem in physics is: why are masses positive? This is a deep question in fundamental physics and one would at first expect that an answer should be available within quantum gravity at worst. Nevertheless, it would be interesting to find simpler solutions.

An answer to this question can be given, within some assumptions, in the realm of quantum field theory in curved spacetime. Namely, results due to Borde[^1] and Penrose, Sorkin, and Woolgar[^2] establish with some generality that isolated gravitating bodies have positive masses as long as their constituent matter satisfies some good properties. In more detail, the constituent matter must satisfy the achronal averaged null energy condition, which is a condition believed to be true for all quantum fields in all physically meaningful scenarios[^3][^4]. Hence, once we tell general relativity that matter is made of quantum fields, it follows that mass must be positive.

While this is a very interesting and general result, one could wonder whether quantum field theory is really necessary to settle this question. Costa and Matsas[^5] have conjectured recently that general relativity alone should be able to discard from existence any negative-mass solutions. While the original conjecture was not detailed enough on what could forbid the existence of these solutions, it is clear now that merely imposing equilibrium and the absence of singularities (for example) is not sufficient. It turns out Novikov *et al.*[^6] had previously given examples of regular negative-mass stars in general relativity. While they did not address whether these examples involved existing matter or whether they were stable, this gives clear evidence that general relativity admits equilibrium configurations with negative mass and no singularities.

However, this still leaves room for a different interpretation of the Costa–Matsas conjecture. While equilibrium configurations with negative mass are allowed by general relativity, it could still happen that these configurations are generically unstable. This would be enough to discard negative masses based on a purely classical argument.

In this work, we show precisely that. We consider generalizations of the negative-mass stars given by Novikov *et al.*[^6] and show that they are all unstable. Furthermore, we argue that any barotropic negative-mass star must be unstable for similar reasons.

## Methods

### Tolman–Oppenheimer–Volkoff Equation

For simplicity and to keep calculations manageable, we restrict our attention to stars that are

1. spherically symmetric,
2. described by a perfect fluid,
3. (nearly) stationary,
4. finite,
5. and barotropic.

Spherical symmetry enforces the metric to have the form

$$\mathrm{d}s^2 = - e^{2\phi(t,r)}\mathrm{d}t^2 + e^{2\psi(t,r)}\mathrm{d}r^2 + r^2 \mathrm{d}\Omega^2,$$

which in turn implies the Einstein tensor has the form

$$G^\mu{}_\nu = 8 \pi T^{\mu}{}_{\nu} = 8 \pi \begin{pmatrix}-\rho &&& \\ & P_{\parallel} && \\ && P_{\perp} & \\ &&& P_{\perp}\end{pmatrix}.$$

Requiring the star to be described by a perfect fluid means imposing $P_{\parallel} = P_{\perp} \equiv P$, and thus the matter content is completely characterized by two functions: the energy density $\rho$ and the (isotropic) pressure $P$.

Next we require the solution to be (nearly) stationary. Stationarity means $\phi$, $\psi$, $\rho$, and $P$ depend only on $r$, not on $t$. "Nearly" stationary means the solution may depend on time, but this dependence is very small and can be treated within linearized perturbation theory.

Finiteness means the star has a boundary. This is required because we want to describe a negative-mass object with finite extensions. An infinitely large object would be interesting for cosmology, but not for our purposes of understanding the absence of objects with negative mass.

Finally, the assumption that the star is barotropic means the isotropic pressure $P$ is given in terms of the energy density $\rho$ by a (differentiable) equation of state $P = P(\rho)$. While it is not strictly necessary at this stage, it is used later to keep the calculations feasible.

Within these assumptions, the equations for hydrostatic equilibrium and for the geometry of spacetime are described by a coupled system of nonlinear ordinary differential equations. The main equation, giving the radial dependence of the pressure, is known as the Tolman--Oppenheimer--Volkoff (TOV) equation[^7] [^8] [^9] [^10]. Since we are able to reduce the problem to a few ordinary differential equations, we can deal with all the calculations with relative ease (as compared to the typical situation in general relativity).

To actually solve the TOV system one needs to prescribe an equation describing the material of the star. This typically takes the form of an equation of state relating the pressure and the energy density of the star. In astrophysics, this is the preferred method to obtain a solution. One prescribes a model for what a star is made of, and then computes how the star gravitates.

When dealing with negative-mass stars, an alternative approach is also of interest. One chooses the functional form the energy density should have as a function of the radius. This determines an energy density profile. This profile is then taken as an ansatz on the TOV system and used to obtain the remaining variables. In this way, one has complete control over the energy (and mass) of the star, but abdicates of any saying on its composition. One can then check whether the star is barotropic by plotting the energy density and the pressure against each other and analyzing whether the result yields a well-defined function.

### Chandrasekhar Pulsation Equation

One of the main methods to study stellar stability is by adding small perturbations to the star and studying how these perturbations evolve. For example, one slightly displaces some fluid elements in the star. If they go back to their original positions, this indicates stability. If they drift farther and farther away, this indicates instability. Hence, the problem of determining stability is mapped into the problem of studying how minor changes to the structure of a star evolve with time.

This problem was addressed by Chandrasekhar[^11] [^12]. One considers small perturbations of a star described by the TOV equations. These perturbations end up being described by an ordinary differential equation of Sturm–Liouville type, known as the Chandrasekhar pulsation equation. This means the problem becomes solving a differential equation for an unknown function and for an unknown constant parameter. The possible values of this parameter are precisely the squares of the frequencies of oscillation of the star. If one of these frequencies is imaginary, then the star is unstable.

There are then many techniques from Sturm–Liouville theory that one can employ to study whether one of the frequencies is imaginary. In the case of negative masses, one must manipulate the pulsation equation to get to a well-behaved form. This can be done in a straightforward manner. Nevertheless, depending on the particular model we are working with, we may need to assume the equation of state for the star to be barotropic in order to perform the calculations.

## Results

Using these techniques, one can come up with many different density profiles and equations of state to describe negative mass stars. One can then use the Chandrasekhar pulsation equation to investigate stability. It turns out that all proposed models are unstable.

A common thermodynamic property among all the models we considered is that, at least somewhere inside the star, the pressure decreases when the density increases. This is an uncommon thermodynamical feature when dealing with positive masses. One can try to drop this assumption, but this leads to negative pressures in the presence of negative energy densities. In turn, one can show that a negative mass star with negative pressure must have at least one point in which the pressure decreases with the density. Therefore, the original examples are sufficiently general. In particular, we can show that if somewhere inside the star the pressure decreases when the density increases, then the star must be dynamically unstable. Notice this means all barotropic negative-mass stars must be unstable.

## Conclusions

The main lesson to be taken is that negative-mass barotropic spherically symmetric stars in general relativity must be dynamically unstable. This result does not depend on quantum theory in any way, and it is a completely classical argument for why there are no negative masses.

## References for this Short Summary

[^1]: Borde, A. 1987. “Geodesic Focusing, Energy Conditions and Singularities.” [*Classical and Quantum Gravity* **4**: 343–56](https://doi.org/10.1088/0264-9381/4/2/015).
[^2]: Penrose, Roger, R. D. Sorkin, and E. Woolgar. 1993. “A Positive Mass Theorem Based on the Focusing and Retardation of Null Geodesics.” arXiv: [gr-qc/9301015](https://arxiv.org/abs/gr-qc/9301015).
[^3]: Kontou, Eleni-Alexandra, and Ko Sanders. 2020. “Energy Conditions in General Relativity and Quantum Field Theory.” [*Classical and Quantum Gravity* **37**: 193001](https://doi.org/10.1088/1361-6382/ab8fcf). arXiv: [2003.01815 [gr-qc]](https://arxiv.org/abs/2003.01815).
[^4]: Wall, A. C. 2010. “Proving the Achronal Averaged Null Energy Condition from the Generalized Second Law”. [*Physical Review D* **81**: 024038](https://doi.org/10.1103/PhysRevD.81.024038). arXiv: [0910.5751 [gr-qc]](https://arxiv.org/abs/0910.5751).
[^5]: Costa, Bruno Arderucio, and George E. A. Matsas. 2022. “Can Quantum Mechanics Breed Negative Masses?” [*Physical Review D* **105**: 085016](https://doi.org/10.1103/PhysRevD.105.085016). arXiv: [2112.08881 [gr-qc]](https://arxiv.org/abs/2112.08881).
[^6]: Novikov, Igor D., G. S. Bisnovatyi-Kogan, and Dmitry I. Novikov. 2018. “Stars Creating a Gravitational Repulsion”. [*Physical Review D* **98**: 063528](https://doi.org/10.1103/PhysRevD.98.063528). arXiv: [1807.06468 [gr-qc]](https://arxiv.org/abs/1807.06468).
[^7]: Oppenheimer, J. Robert, and G. M. Volkoff. 1939. “On Massive Neutron Cores”. [*Physical Review* **55**: pp. 374–381](https://doi.org/10.1103/PhysRev.55.374).
[^8]: Tolman, Richard C. 1934. *Relativity, Thermodynamics and Cosmology*. The International Series of Monographs on Physics. Oxford: Oxford University Press.
[^9]: Tolman, Richard C. 1934. “Effect of Inhomogeneity on Cosmological Models.” [*Proceedings of the National Academy of Sciences* **20**: pp. 169–76](https://doi.org/10.1073/pnas.20.3.169).
[^10]: Tolman, Richard C. 1939. “Static Solutions of Einstein’s Field Equations for Spheres of Fluid.” [*Physical Review* **55**: pp. 364–73](https://doi.org/10.1103/PhysRev.55.364).
[^11]: Chandrasekhar, Subrahmanyan. 1964. “Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity.”[*Physical Review Letters* **12**: 114–16](https://doi.org/10.1103/PhysRevLett.12.114). Erratum: [*Physical Review Letters* **12**: 437–38](https://doi.org/10.1103/PhysRevLett.12.437.2).
[^12]: Chandrasekhar, Subrahmanyan. 1964. “The Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity.” [*The Astrophysical Journal* **140**: 417–33](https://doi.org/10.1086/147938). Erratum: [*The Astrophysical Journal* **140**: 1342](https://doi.org/10.1086/148040).
