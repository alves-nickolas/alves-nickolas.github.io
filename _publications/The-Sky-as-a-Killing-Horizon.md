---
title: The Sky as a Killing Horizon
date: 2025-04-16
authors: 
 - <strong>Níckolas de Aguiar Alves</strong>
 - <a href="https://orcid.org/0000-0002-3717-4966" target="_blank">André G. S. Landulfo</a>
abstract: 'Symmetries are ubiquitous in modern physics. They not only allow for a more simplified description of physical systems but also, from a more fundamental perspective, can be seen as determining a theory itself. In the present paper, we propose a new definition of asymptotic symmetries that unifies and generalizes the usual notions of symmetry considered in asymptotically flat spacetimes and expanding universes with cosmological horizons. This is done by considering BMS-like symmetries for "asymptotic (conformal) Killing horizons", or A(C)KHs, here defined as null hypersurfaces that are tangent to a vector field satisfying the (conformal) Killing equation in a limiting sense. The construction is theory-agnostic and extremely general, for it makes no use of the Einstein equations and can be applied to a wide range of scenarios with different dimensions or hypersurface cross sections. While we reproduce the results by Dappiaggi, Moretti, and Pinamonti in the case of asymptotic Killing horizons, the conformal generalization does not yield only the BMS group, but a larger group. The enlargement is due to the presence of "superdilations". We speculate on many implications and possible continuations of this work, including the exploration of gravitational memory effects beyond general relativity, understanding antipodal matching conditions at spatial infinity in terms of bifurcate horizons, and the absence of superrotations in de Sitter spacetime and Killing horizons.'
citation: 'Aguiar Alves, Níckolas de, and André G. S. Landulfo. 2025. “The Sky as a Killing Horizon.” arXiv: <a href="https://arxiv.org/abs/2504.12514" target="_blank">2504.12514 [gr-qc]</a>.'
stage: phd
tags: IRStructure GR QFTCS
pubtype: paper
arxiv: "2504.12514"
permalink: /abs/2504.12514/
---

## Introduction

Symmetry is a guiding principle throughout physics. In a sense, one could say the study of physics is the pursuit for what are the underlying symmetries of the universe. Recently, a lot of attention has been given to the so-called asymptotic symmetries—the symmetries that emerge in spacetime as one asymptotically approaches a limiting surface. 

Of particular notice are the Bondi–Metzner–Sachs[^1] [^2] [^3] and Dappiaggi–Moretti–Pinamonti [^4] groups. These groups characterize the asymptotic symmetries at null infinity in asymptotically flat spacetimes and at the cosmological horizon in expanding universes ("asymptotically de Sitter spacetimes"), respectively. 

However, it is curious that the two groups are very similar, but also very different. We would like to understand why. If have success in extending the groups to larger versions that encompass both at the same time, then we will be able to employ techniques that are common in one setup to the other.

## Methods

Our main mathematical tool will be the notion of a Carollian structure, introduced by Duval *et. al.* [^5] [^6] [^7]. This is a generalization of the idea of a pseudo-Riemmanian manifold to the case in which the metric has a degenerate direction. Instead of asking for a pair $(M,g_{ab})$, we instead ask for a triple $(N,h_{ab},n^a)$, where $n^a$ is a vector along the degenerate (null) direction.

Instead of working with arbitrary null hypersurfaces, we prefer to define the notion of asymptotic (conformal) Killing horizons. These are null hypersurfaces tangent to a vector field that asymptotically satisfies the (conformal) Killing equation in the limit one approaches the surface. These surfaces are meant to inherit properties of genuine Killing horizons, but without restricting too much the ambient spacetime. 

A(C)KHs are special when considered as a type of null hypersurface. For instance, all of their spatial cross setions are confomorphic (for ACKHs) or isometric (for AKHs). This considerably constraint their geometry.
## Results

After studying the conformal Carroll groups naturally induced by the A(C)KH structure, we find the groups 
$$G_{\text{ACKH}} = \text{Conf}(\Sigma) \ltimes \left(\mathcal{C}^{\infty}(\Sigma) \ltimes \mathcal{C}^{\infty}(\Sigma) \right)$$
and 
$$G_{\text{AKH}} = \text{Isom}(\Sigma) \ltimes \left(\mathcal{C}^{\infty}(\Sigma) \ltimes \mathcal{C}^{\infty}(\Sigma) \right),$$
where $\text{Isom}(\Sigma)$ is the isometry group for $\Sigma$, while $\text{Conf}(\Sigma)$ is the associated conformal group. In both cases, $\Sigma$ stands for the spatial cross section of the horizon. 

For $\Sigma = \mathbb{S}^2$, as one usually considers in four-dimensional applications, we get 
$$G_{\text{ACKH}} = \text{SO}^+(3,1) \ltimes \left(\mathcal{C}^{\infty}(\mathbb{S}^2) \ltimes \mathcal{C}^{\infty}(\mathbb{S}^2) \right)$$
and 
$$G_{\text{AKH}} = \text{SO}(3) \ltimes \left(\mathcal{C}^{\infty}(\mathbb{S}^2) \ltimes \mathcal{C}^{\infty}(\mathbb{S}^2) \right),$$
$G_{\text{AKH}}$ is then merely the DMP group, but $G_{\text{ACKH}}$ extends the BMS group by an infinite family of "superdilations".

## Conclusions

Viewing the sky as a Killing horizon can lead to interesting new perspectives. For example, superdilations arising at the symmetry group at infinity may hint at memory effects hidden in modified theories of gravity. One could use symmetries to search for these theories, and then test the subsequent predictions with gravitational wave observatories. 

Other possible outlooks are the investigations of bifurcate horizons, which could appear at lightcones and at spacetimes that are asymptotically flat at spatial infinity. Lastly, our analysis disfavors the possibility of exploiting superrotations as a path to a dS/CFT correspondence in the cosmological horizon.

[^1]: Bondi, Hermann, M. G. J. Van der Burg, and A. W. K. Metzner. 1962. “Gravitational Waves in General Relativity, VII. Waves from Axi-Symmetric Isolated System.” [_Proceedings of the Royal Society of London. Series A. Mathematical and Physical Sciences_ 269 (1336): 21–52](https://doi.org/10.1098/rspa.1962.0161).
[^2]: Sachs, R. K. 1962. “Asymptotic Symmetries in Gravitational Theory.” [_Physical Review_ 128 (6): 2851–64](https://doi.org/10.1103/PhysRev.128.2851).
[^3]: Sachs, R. K. 1962. “Gravitational Waves in General Relativity VIII. Waves in Asymptotically Flat Space-Time.” [_Proceedings of the Royal Society of London. Series A. Mathematical and Physical Sciences_ 270 (1340): 103–26](https://doi.org/10.1098/rspa.1962.0206).
[^4]: Dappiaggi, Claudio, Valter Moretti, and Nicola Pinamonti. 2009. “Cosmological Horizons and Reconstruction of Quantum Field Theories.” [_Communications in Mathematical Physics_ 285 (3): 1129–63](https://doi.org/10.1007/s00220-008-0653-8).
[^5]: Duval, C., G. W. Gibbons, P. A. Horvathy, and P. M. Zhang. 2014. “Carroll versus Newton and Galilei: Two Dual Non-Einsteinian Concepts of Time.” [_Classical and Quantum Gravity_ 31 (8)](https://doi.org/10.1088/0264-9381/31/8/085016).
[^6]: Duval, C., G. W. Gibbons, and P. A. Horvathy. 2014. “Conformal Carroll Groups and BMS Symmetry.” [_Classical and Quantum Gravity_ 31 (9)](https://doi.org/10.1088/0264-9381/31/9/092001).
[^7]: Duval, C., G. W. Gibbons, and P. A. Horvathy. 2014. “Conformal Carroll Groups.” [_Journal of Physics A: Mathematical and Theoretical_ 47 (33)](https://doi.org/10.1088/1751-8113/47/33/335204).
