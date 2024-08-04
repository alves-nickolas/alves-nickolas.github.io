---
title: Algebraic Quantum Field Theory
tag: AQFT
priority: 2
---

Many of the traditional techniques used in quantum field theory in flat spacetime become problematic when working in curved spacetime. The absence of a general notion of time implies it is impossible to find a preferred vacuum state in spacetimes without a time translation symmetry, which makes both the canonical and the path integral approach troublesome to deal with. Instead, a sophisticated approach that can be used to formulate QFTCS is the algebraic approach, which deals directly with the algebraic structure of the theory’s observables.

Allow me to be more specific. When canonically quantizing a field, the typical description is based on a Fock space, which is often thought of as the space of all states in the theory. This space is constructed as the space of all possible states with any non-negative integer number of particles, with each particle being in any "one-particle" state. A way to describe this Fock space is to start from the vacuum (the state with zero particles) and work your way up by using creation operators to get to more populated states. This is a very simple way of quantizing a quantum field and is particularly pedagogical when discussing free fields. 

A second popular approach is the path integral approach. This approach describes the quantum effects of a field theory through an integral over the space of all possible field configurations. The philosophy is that when computing the probability of some process happening in the quantum theory you should sum over all possible "paths", or histories, the system can go through in between the initial and final states. In practice, this technique allows you to write the vacuum expectation value of any operator in terms of an integral on the space of field configurations. While rather technical, this is a powerful method to understand the properties of quantum fields. Furthermore, in flat spacetime, it is equivalent to the canonical approach. 

A key point in both of these methods is that they rely on a preferred state. The canonical approach has the vacuum as the preferred state because all other states are described in terms of it, while the path integral approach implicitly assumes a preferred state because the integral gives the expectation values in this implicit state. In flat spacetime, this is not an issue, since one does have a preferred state: the so-called Minkowski (or Poincaré) vacuum, which is the state in which inertial observers see no particles. 

In curved spacetime, the situation is more subtle. Not every spacetime admits a preferred vacuum state, and that is intimately related to the symmetries in the spacetime. Hence, the canonical approach and the path integral approach become highly dependent on a choice of state that is obscured in their formalism. Even worse, the path integral approach implicitly assumes that the spacetime and the state are time-translation invariant and analytic because the path integral is defined as an analytic continuation from imaginary to real time. In a general spacetime with no symmetries (such as our actual and physical spacetime), the hypotheses that enter these methods are not available. 

The algebraic approach to quantum field theory allows a formulation of the theory in these general cases. Instead of working with a Fock space or a path integral, one defines the theory as a collection of "observables" and the possible states given this collection of observables. The collection of observables is assumed to have some algebraic structure (usually a *-algebra or something stronger). This leads to a rigorous mathematical theory of quantum field theory which does not depend on the existence of symmetries or analyticity properties of the underlying spacetime.

## Further Reading
The following references discuss quantum field theory (often in curved spacetimes) with a tendency toward the algebraic approach.
