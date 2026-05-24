---
title: "A semicontinuous relaxation of Saito's criterion and freeness as angular minimization"
collection: publications
category: preprints
permalink: /publication/2026-04-A semicontinuous relaxation of Saito's criterion and freeness as angular minimization
excerpt: '' 
date: 2026-04-03
venue: #
slidesurl: # 
paperurl: 'https://arxiv.org/abs/2604.02995'
citation: # 
---
[arXiv:2604.02995](https://arxiv.org/abs/2604.02995)

We introduce a nonnegative functional \\(\mathfrak{S}\\) on the space of line arrangements in \\(\mathbb{P}^2\\) that vanishes precisely on free arrangements, obtained as a semicontinuous relaxation of Saito's criterion. Given an arrangement \\(\mathcal{A}\\) of \\(n\\) lines with candidate exponents \\((d_1, d_2)\\), we parameterize the spaces of logarithmic derivations of degrees \\(d_1\\) and \\(d_2\\) via the null spaces of the associated derivation matrices and express the Saito determinant as a bilinear map into the space of degree-\\(n\\) polynomials. The functional admits a natural geometric interpretation: it measures the squared sine of the angle between the image of this bilinear map and the direction of the defining polynomial \\(Q(\mathcal{A})\\) in coefficient space, providing a computable measure of how far an arrangement is from admitting a free basis of logarithmic derivations of the expected degrees. We prove that \\(\mathfrak{S}\\) is upper semicontinuous on natural strata, and use this to give a functional reformulation of Terao's conjecture.

Beyond its theoretical interest, \\(\mathfrak{S}\\) provides a viable computational handle on the landscape of free arrangements. We illustrate this through two complementary roles: as a smooth reward signal driving a reinforcement learning search for moderate \\(n\\), and as a fast pre-filter accelerating an algebraic extension procedure for larger \\(n\\). For \\(n \leq 13\\), the reinforcement learning system discovers hundreds of verified free arrangements spanning all admissible exponent types. For \\(n \geq 14\\), where the reinforcement learning reward signal becomes insufficient, the hybrid extension procedure -- combined with classical supersolvable constructions -- produces at least one verified free arrangement for every admissible exponent pair \\((d_1, d_2)\\) with \\(n \leq 20\\).