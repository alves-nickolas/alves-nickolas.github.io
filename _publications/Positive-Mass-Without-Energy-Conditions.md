---
title: Positive Mass in General Relativity Without Energy Conditions
date: 2024-08-01
authors: 
 - <strong>Níckolas de Aguiar Alves</strong>
 - <a href="https://orcid.org/0000-0002-3717-4966" target="_blank">André G. S. Landulfo</a>
 - <a href="https://barderucio.wordpress.com/" target="_blank">Bruno Arderucio Costa</a>
abstract: 'A long-standing problem in physics is why observed masses are always positive. While energy conditions in quantum field theory can partly answer this problem, in this paper we find evidence that classical general relativity abhors negative masses, without the need for quantum theory or energy conditions. This is done by considering many different models of negative-mass "stars" and showing they are dynamically unstable. <i>A fortiori</i>, we show that any barotropic negative-mass star must be dynamically unstable.'
citation: 'Aguiar Alves, Níckolas de, André G. S. Landulfo, and Bruno Arderucio Costa. “Positive Mass in General Relativity Without Energy Conditions,” 2024. Forthcoming. arXiv: <a href="https://arxiv.org/abs/2408.00154" target="_blank">2408.00154 [gr-qc]</a>.'
stage: phd
tags: EnergyConditions GR
pubtype: paper
arxiv: "2408.00154"
permalink: /abs/2408.00154/
---

## Introduction

A long-standing problem in physics is: why are masses positive? This is a deep question in fundamental physics and one would at first expect that an answer should be available within quantum gravity at worst. Nevertheless, it would be interesting to find simpler solutions.

An answer to this question can be given, within some assumptions, in the realm of quantum field theory in curved spacetime. Namely, results due to Borde ([1987](#borde1987)) and Penrose, Sorkin, and Woolgar ([1993](#penrose1993)) establish with some generality that isolated gravitating bodies have positive masses as long as their constituent matter satisfies some good properties. In more detail, the constituent matter must satisfy the achronal averaged null energy condition, which is a condition believed to be true for all quantum fields in all physically meaningful scenarios (Kontou and Sanders [2020](#kontou2020); Wall [2010](#wall2010)). Hence, once we tell general relativity that matter is made of quantum fields, it follows that mass must be positive. 
    
While this is a very interesting and general result, one could wonder whether quantum field theory is really necessary to settle this question. Costa and Matsas ([2022](#costa2022)) have conjectured recently that general relativity alone should be able to discard from existence any negative-mass solutions. While the original conjecture was not detailed enough on what could forbid the existence of these solutions, it is clear now that merely imposing equilibrium and the absence of singularities (for example) is not sufficient. It turns out Novikov, Bisnovatyi-Kogan, and Novikov ([2018](#novikov2018)) had previously given examples of regular negative-mass stars in general relativity. While they did not address whether these examples involved existing matter or whether they were stable, this gives clear evidence that general relativity admits equilibrium configurations with negative mass and no singularities. 
    
However, this still leaves room for a different interpretation of the Costa–Matsas conjecture. While equilibrium configurations with negative mass are allowed by general relativity, it could still happen that these configurations are generically unstable. This would be enough to discard negative masses based on a purely classical argument. 
    
In this work, we show precisely that. We consider generalizations of the negative-mass stars given by Novikov, Bisnovatyi-Kogan, and Novikov ([2018](#novikov2018)) and show that they are all unstable. Furthermore, we argue that any barotropic negative-mass star must be unstable for similar reasons. 

## Methods
### Tolman--Oppenheimer--Volkoff Equation
For simplicity and to keep calculations manageable, we restrict our attention to stars that are
1. spherically symmetric,
2. described by a perfect fluid,
3. (nearly) stationary,
4. finite,
5. and barotropic.

Spherical symmetry enforces the metric to have the form
\\[\mathrm{d}s^2 = - e^{2\phi(t,r)}\mathrm{d}t^2 + e^{2\psi(t,r)}\mathrm{d}r^2 + r^2 \mathrm{d}\Omega^2,\\]
which in turn implies the Einstein tensor has the form
\\[G^\mu{}_\nu = 8 \pi T^{\mu}{}_{\nu} = 8 \pi \begin{pmatrix}-\rho &&& \\ & P_{\parallel} && \\ && P_{\perp} & \\ &&& P_{\perp}\end{pmatrix}.\\]

The last assumption is not necessary at this stage, but it is used later to keep the calculations feasible. 

Within these assumptions, the equations for hydrostatic equilibrium and for the geometry of spacetime are described by a coupled system of nonlinear ordinary differential equations. The main equation, giving the radial dependence of the pressure, is known as the Tolman--Oppenheimer--Volkoff (TOV) equation (Oppenheimer and Volkoff [1939](#oppenheimer1939); Tolman [1934a](#tolman1934a),[b](#tolman1934b), [1939]((#tolman1939))). Since we are able to reduce the problem to a few ordinary differential equations, we can deal with all the calculations with relative ease (as compared to the typical situation in general relativity). 

To actually solve the TOV system one needs to prescribe one extra equation. This typically takes the form of an equation of state relating the pressure and the energy density of the star, which essentially gives the information of which material composes the star. In astrophysics, this is the preferred method to obtain a solution. One prescribes a model for what a star is made of, and then computes how the star gravitates. 

When dealing with negative-mass stars, an alternative approach is also of interest. One chooses the functional form the energy density should have as a function of the radius. This determines an energy density profile. This profile is then taken as an ansatz on the TOV system and used to obtain the remaining variables. In this way, one has complete control over the energy (and mass) of the star, but abdicates of any saying on its composition.

### Chandrasekhar Pulsation Equation
One of the main methods to study stellar stability is by adding small perturbations to the star and studying how these perturbations evolve. For example, one slightly displaces some fluid elements in the star. If they go back to their original positions, this indicates stability. If they drift farther and farther away, this indicates instability. Hence, the problem of determining stability is mapped into the problem of studying how minor changes to the structure of a star evolve with time.

This problem was addressed by Chandrasekhar ([1964a](#chandrasekhar1964a),[b](#chandrasekhar1964b)). One considers small perturbations of a star described by the TOV equations. These perturbations end up being described by an ordinary differential equation of Sturm--Liouville type, known as the Chandrasekhar pulsation equation. This means the problem becomes solving a differential equation for an unknown function and for an unknown constant parameter. The possible values of this parameter are precisely the squares of the frequencies of oscillation of the star. If one of these frequencies is imaginary, then the star is unstable.

There are then many techniques from Sturm--Liouville theory that one can employ to study whether one of the frequencies is imaginary. In the case of negative masses, one must manipulate the pulsation equation to get to a well-behaved form. This can be done in a straightforward manner. Nevertheless, depending on the particular model we are working with, we may need to assume the equation of state for the star to be barotropic in order to perform the calculations.

## Results
Using these techniques, one can come up with many different density profiles and equations of state to describe negative mass stars. One can then use the Chandrasekhar pulsation equation to investigate stability. It turns out that all proposed models are unstable. 

A common thermodynamic property among all the models we considered is that, at least somewhere inside the star, the pressure decreases when the density increases. This is an uncommon thermodynamical feature when dealing with positive masses. One can try to drop this assumption, but this leads to negative pressures in the presence of negative energy densities. In turn, one can show that a negative mass star with negative pressure must have at least one point in which the pressure decreases with the density. Therefore, the original examples are sufficiently general. In particular, we can show that if somewhere inside the star the pressure decreases when the density increases, then the star must be dynamically unstable. Notice this means all barotropic negative-mass stars must be unstable.

## Conclusions
The main lesson to be taken is that negative-mass barotropic spherically symmetric stars in general relativity must be dynamically unstable. This result does not depend on quantum theory in any way, and it is a completely classical argument for why there are no negative masses. 

## References for this Summary
* <a name="borde1987"></a>Borde, A. (1987). “Geodesic Focusing, Energy Conditions and Singularities”. [_Classical and Quantum Gravity_ **4**, pp. 343–356](https://doi.org/10.1088/0264-9381/4/2/015).
* <a name="chandrasekhar1964a"></a>Chandrasekhar, S. (1964a). “Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity”. [_Physical Review Letters_ **12**, pp. 114–116](https://doi.org/10.1103/PhysRevLett.12.114). Erratum “Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity”. [_Physical Review Letters_ **12** (1964), pp. 437–438](https://doi.org/10.1103/PhysRevLett.12.437.2).
* <a name="chandrasekhar1964b"></a>Chandrasekhar, S. (1964b). “The Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity”. [_The Astrophysical Journal_ **140**, pp. 417–433](https://doi.org/10.1086/147938). Erratum: “Erratum: The Dynamical Instability of Gaseous Masses Approaching the Schwarzschild Limit in General Relativity”. [_The Astrophysical Journal_ **140** (1964), p. 1342](https://doi.org/10.1086/148040).
* <a name="costa2022"></a>Costa, B. A. and G. E. A. Matsas (2022). “Can Quantum Mechanics Breed Negative Masses?” [_Physical Review D_ **105**, 085016](https://doi.org/10.1103/PhysRevD.105.085016). arXiv: [2112.08881 [gr-qc]](https://arxiv.org/abs/2112.08881).
* <a name="kontou2020"></a>Kontou, E.-A. and K. Sanders (2020). “Energy Conditions in General Relativity and Quantum Field Theory”. [_Classical and Quantum Gravity_ **37**, 193001](https://doi.org/10.1088/1361-6382/ab8fcf). arXiv: [2003.01815 [gr-qc]](https://arxiv.org/abs/2003.01815).
* <a name="novikov2018"></a>Novikov, I. D., G. S. Bisnovatyi-Kogan, and D. I. Novikov (2018). “Stars Creating a Gravitational Repulsion”. [_Physical Review D_ **98**, 063528](https://doi.org/10.1103/PhysRevD.98.063528). arXiv: [1807.06468 [gr-qc]](https://arxiv.org/abs/1807.06468).
* <a name="oppenheimer1939"></a>Oppenheimer, J. R. and G. M. Volkoff (1939). “On Massive Neutron Cores”. [_Physical Review_ **55**, pp. 374–381](https://doi.org/10.1103/PhysRev.55.374).
* <a name="penrose1993"></a>Penrose, R., R. D. Sorkin, and E. Woolgar (1993). A Positive Mass Theorem Based on the Focusing and Retardation of Null Geodesics. arXiv: [gr-qc/9301015](https://arxiv.org/abs/gr-qc/9301015).
* <a name="tolman1934a"></a>Tolman, R. C. (1934a). Relativity, Thermodynamics and Cosmology. The International Series of Monographs on Physics. Oxford: Oxford University Press.
* <a name="tolman1934b"></a>Tolman, R. C. (1934b). “Effect of Inhomogeneity on Cosmological Models”. [_Proceedings of the National Academy of Sciences_ **20**, pp. 169–176](https://doi.org/10.1073/pnas.20.3.169).
* <a name="tolman1939"></a>Tolman, R. C. (1939). “Static Solutions of Einstein’s Field Equations for Spheres of Fluid”. [_Physical Review_ **55**, pp. 364–373](https://doi.org/10.1103/PhysRev.55.364).
* <a name="wall2010"></a>Wall, A. C. (2010). “Proving the Achronal Averaged Null Energy Condition from the Generalized Second Law”. [_Physical Review D_ **81**, 024038](https://doi.org/10.1103/PhysRevD.81.024038). arXiv: [0910.5751 [gr-qc]](https://arxiv.org/abs/0910.5751).
