---
title: Nonperturbative Aspects of Quantum Field Theory in Curved Spacetime
date: 2023-04-28
authors: "<b>Níckolas de Aguiar Alves</b>"
abstract: "Quantum field theory in curved spacetime is perhaps the most reliable framework in which one can investigate quantum effects in the presence of strong gravitational fields. Nevertheless, it is often studied by means of perturbative treatments. In this thesis, we aim at using the functional renormalization group—a nonperturbative realization of the renormalization group—as a technique to describe nonperturbative quantum phenomena in curved spacetimes. The chosen system is an Unruh–DeWitt particle detector coupled to a scalar quantum field. We discuss how to formulate such a system in terms of an action and how one can compute its renormalization group flow in the case of an inertial detector in flat spacetime, for simplicity. We learn, however, that the results are divergent in the limit in which the detector's energy gap vanishes. Possible workarounds are discussed at the end. <br><br> This thesis also presents a review of quantum field theory in curved spacetimes by means of the algebraic approach, although it assumes no previous experience with functional analysis. Hence, it fills a pedagogical gap in the literature. Furthermore, we also review the functional renormalization group and derive the Wetterich equation assuming a general field content that might include both bosonic and fermionic fields. Such a derivation is also hardly found in pedagogical introductions available in the high energy physics literature."
citation: 'Aguiar Alves, Níckolas de (2023). "Nonperturbative Aspects of Quantum Field Theory in Curved Spacetime". MSc thesis. Santo André, Brazil: Federal University of ABC. xxiv, 152 pp. arXiv: <a href="https://arxiv.org/abs/2305.17453" target="_blank">2305.17453 [gr-qc]</a>.'
stage: msc
tags: QFTCS AQFT FRG
pubtype: mscthesis
---

> this page is under construction!

## Introduction

One of the hardest problems in fundamental physics is to understand the quantum nature of gravity. On the road to doing so, it has been useful to consider how quantum mechanics effects occur in the presence of strong gravitational fields. A good framework for this is that of [quantum field theory in curved spacetime]({% link _interests/QFTCS.md %}) (QFTCS). In this framework, one considers the behavior of quantum fields—the building blocks of the standard model of particle physics, for example—on top of a classical background spacetime. It therefore consists of an approximation in which gravity behaves classically, but matter is quantized. 

One interesting application of QFTCS is to the field of relativistic quantum information (RQI). One may ask oneself how quantum mechanics can be used to convey information between two observers, and in particular how the structure of spacetime affects the possibilities of communication. These questions are addressed by RQI. Within this paradigm, Landulfo ([2016](#landulfo2016)) has described a communication protocol in which two experimentalists couple a two-level quantum system (a qubit) to a quantum field and communicate by performing measurements on the qubits. Some important features of this model are the following.
1. It can be solved exactly (something extremely rare in quantum field theory) due to the particular choice of coupling;
2. the results obtained hold for a large class of spacetimes;
3. it is not necessary to choose an arbitrary notion of "particles" in formulating the model;
4. the quantum state of the field can belong to a large class of "vacuum-like" states;
5. both sender and receiver are allowed to have arbitrary trajectories through spacetime;
6. both sender and receiver interact with the quantum field within bounded regions of spacetime;
7. the protocol allows the transmission of classical information (bits with 0 or 1 values);
8. the protocol explicitly forbids faster-than-light communication.

All of these are great advantages, but the model still has a couple of drawbacks. For instance, one cannot transmit quantum information (qubit states) without the aid of extra entanglement between the parts and one cannot harvest entanglement from the quantum fields. Moreover, one cannot use the qubits as particle detectors. This is inconvenient because particle detector models are very useful in studying both QFTCS and RQI and even date back to the original derivation of the Unruh effect (Unruh [1976](#unruh1976)).

To improve on these aspects, one needs to change the coupling of the model to introduce a "gap" in the qubit. Namely, Landulfo's original model assumes a two-level system in which both levels have the same energy. This leads to all of the good features of the model (in particular the fact that it is exactly solvable), but it also leads to the drawbacks. Adding an energy gap (so that the two levels have different energies) improves the drawbacks but at the cost of the exact solution.

Most work in RQI is perturbative, so it would be interesting to obtain nonperturbative information about this behavior. One possible way of doing this is to study the model perturbatively, but account for nonperturbative corrections by exploiting the [functional renormalization group]({% link _interests/FRG.md %}) running of the theory. While this is still an approximate solution, it allows one to obtain nonperturbative information, hence allowing the investigation of a regime often overlooked. 


## References for this Summary
* <a name="landulfo2016"></a>Landulfo, André G. S. (2016). “Nonperturbative Approach to Relativistic Quantum Communication Channels.” [_Physical Review D_ **93**: 104019](https://doi.org/10.1103/PhysRevD.93.104019). arXiv: [1603.06641 [gr-qc]](https://arxiv.org/abs/1603.06641).
* <a name="unruh1976"></a>Unruh, William G. (1976). “Notes on Black-Hole Evaporation.” [_Physical Review D_ **14** (1976): pp. 870–92](https://doi.org/10.1103/PhysRevD.14.870).

