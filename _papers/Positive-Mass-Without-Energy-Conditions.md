---
title: Positive Mass in General Relativity Without Energy Conditions
authors: "<b>Níckolas de Aguiar Alves</b>, André G. S. Landulfo & Bruno Arderucio Costa"
abstract: 'A long-standing problem in physics is why observed masses are always positive. While energy conditions in quantum field theory can partly answer this problem, in this paper we find evidence that classical general relativity abhors negative masses, without the need for quantum theory or energy conditions. This is done by considering many different models of negative-mass "stars" and showing they are dynamically unstable. <i>A fortiori</i>, we show that any barotropic negative-mass star whose pressure is not a monotonically increasing function of the energy density must be dynamically unstable. Furthermore, we argue that all acceptable barotropic models of negative-mass stars must be in this class, and are thus unstable.'
journal: 
arxiv: '<a href="https://arxiv.org/abs/2408.00154" target="_blank">2408.00154 [gr-qc]</a>'
remark: "This is a simplified version of the work linked above, written with the goal of being an extended abstract or less formal account of the results. For further details, please check the links above. This account is written independently by Níckolas de Aguiar Alves only and may not fully reflect the point of view of other co-authors."
layout: papers
---

## Introduction

A long-standing problem in physics is: <span class="mark">why are masses positive?</span> This is a deep question in fundamental physics and one would at first expect that an answer should be available within quantum gravity at worst. Nevertheless, it would be interesting to find simpler solutions.
    
An answer to this question can be given, within some assumptions, in the realm of quantum field theory in curved spacetime. Namely, results due to \textcite{borde1987GeodesicFocusingEnergy,penrose1993PositiveMassTheorem} establish with some generality that isolated gravitating bodies have positive masses as long as their constituent matter satisfies some good properties. Namely, it is necessary that the constituent matter satisfies the achronal averaged null energy condition, which is a condition believed to be true for all quantum fields in all physically meaningful scenarios \parencite{wall2010ProvingAchronalAveraged,kontou2020EnergyConditionsGeneral}. Hence, \hl{once we tell general relativity that the matter is made of quantum fields, it follows that mass must be positive}. 
    
    While this is a very interesting and general result, one could wonder whether quantum field theory is really necessary to settle this question. \textcite{costa2022CanQuantumMechanics} have \hl{conjectured recently that general relativity alone should be able to discard from existence any negative-mass solutions}. This would be done, according to their conjecture, through the occurrence of singularities, which would deem the negative-mass configurations unphysical. 
    
    This conjecture, as it stands, is incorrect. It turns out \textcite{novikov2018StarsCreatingGravitational} \hl{had previously given examples of regular negative-mass stars in general relativity}. While they did not address whether these examples involved existing matter or whether they were stable, this gives clear evidence that general relativity admits equilibrium configurations with negative mass and no singularities. 
    
    This still leaves room for an improved version of the Costa--Matsas conjecture, though. \hl{While equilibrium configurations with negative mass are allowed by general relativity, it could still happen that these configurations are generically unstable}. This would be enough to discard negative masses based on a purely classical argument. 
    
    \textcite{aguiaralves2024GeneralRelativityAbhors} show precisely that. We consider generalizations of the negative-mass stars given by \textcite{novikov2018StarsCreatingGravitational} and show that they are all unstable. Furthermore, we argue that any thermodynamically acceptable negative-mass star must be unstable for similar reasons. 

\section{Methods}
    \subsection{Tolman--Oppenheimer--Volkoff Equation}
        For simplicity and to keep calculations manageable, we restrict our attention to stars that are
        \begin{enumerate}
            \item stationary, so they are in equilibrium;
            \item spherically symmetric, so the calculations are simple;
            \item isotropic, to avoid unnecessary complications;
            \item the star is barotropic, meaning the pressure at each point is uniquely determined by the energy density.
        \end{enumerate}
        The last assumption is not necessary at this stage, but it is used later to keep the calculations feasible. 

        Within this assumptions, \hl{the equations for hydrostatic equilibrium and for the geometry of spacetime are described by a coupled system of nonlinear ordinary differential equations}. The main equation, giving the radial dependence of the pressure, is known as the \hl{Tolman--Oppenheimer--Volkoff (TOV) equation} \parencite{tolman1934EffectInhomogeneityCosmological,tolman1934RelativityThermodynamicsCosmology,tolman1939StaticSolutionsEinstein,oppenheimer1939MassiveNeutronCores}. Since we are able to reduce the problem to a few ordinary differential equations, we can deal with all the calculations with relative ease (as compared to the typical situation in general relativity). 

        To actually solve the TOV system one needs to prescribe one extra equation. This typically takes the form of an \hl{equation of state} relating the pressure and the energy density of the star, which essentially gives the information of which material composes the star. In astrophysics, this is the preferred method to obtain a solution. One prescribes a model for what a star is made of, and then computes how the star gravitates. 

        When dealing with negative-mass stars, an alternative approach is also of interesting. One chooses the functional form the energy density should have as a function of the radius. This determines an \hl{energy density profile}. This profile is then taken as an ansatz on the TOV system and used to obtain the remaining variables. In this way, one has complete control over the energy (and mass) of the star, but abdicates of any saying on its composition.

    \subsection{Chandrasekhar Pulsation Equation}
        One of the main methods to study stellar stability is by adding small perturbations to the star and studying how these perturbations evolve. For example, one slightly displaces some fluid elements in the star. If they go back to the original positions, this indicates stability. If they drift farther and farther away, this indicates instability. Hence, \hl{the problem of determining stability is mapped into the problem of studying how minor changes to the structure of a star evolve with time}.

        This problem was addressed by \textcite{chandrasekhar1964DynamicalInstabilityApJ,chandrasekhar1964DynamicalInstabilityPRL}. One considers small perturbations of a star described by the TOV equations. These perturbations end up being described by an ordinary differential equation of Sturm--Liouville type, known as the \hl{Chandrasekhar pulsation equation}. This means the problem becomes solving a differential equation for an unknown function and for an unknown constant parameter. \hl{The possible values of this parameter are precisely the squares of the frequencies of oscillation of the star}. \hl{If one of this frequencies is imaginary, then the star is unstable}.

        There are then many techniques from Sturm--Liouville theory that one can employ to study whether one of the frequencies is imaginary. In the case of negative masses, one must manipulate the pulsation equation to get to a well-behaved form. This can be done in a straightforward manner.

\section{Results}
    Using these techniques, one can come up with many different density profiles and equations of state to describe negative mass stars. One can then use the Chandrasekhar pulsation equation to investigate stability. It turns out that all proposed models are unstable. 

    A common thermodynamic property among all the models we considered is that, at least somewhere inside the star, the pressure decreases when the density increases. This is an uncommon thermodynamical feature when dealing with positive masses. One can try to drop this assumption, but this leads to negative pressures in the presence of negative energy densities. In turn, one can show that a negative mass star with negative pressure must have at least one point in which the pressure decreases with the density. Therefore, the original examples are sufficiently general. \hl{In particular, we can show that if somewhere inside the star the pressure decreases when the density increases, then the star must be dynamically unstable}.

\section{Conclusions}
    The main lesson to be taken is that \hl{barotropic spherically symmetric stars in general relativity must be dynamically unstable}. This result does not depend in quantum theory in any way, and it is a completely classical argument for why there are no negative masses. 
