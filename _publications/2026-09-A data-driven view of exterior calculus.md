---
title: "A data-driven view of exterior calculus"
collection: publications
category: manuscripts
permalink: /publication/2026-09-A data-driven view of exterior calculus
redirect_from:
  - /publication/2026-10-Data Numbers and Geometry
excerpt: '' 
date: 2026-09-10
venue: 'AI in Mathematics and Theoretical Physics, Vol. 4, No. 1'
slidesurl: # 
paperurl: 'https://doi.org/10.1142/S3082883X26400011'
citation: # 
---
[AI in Mathematics and Theoretical Physics, Vol. 4, No. 1](https://doi.org/10.1142/S3082883X26400011)

Classical computational tools for differential forms assume symbolic expressions, mesh discretizations, or smoothness close to \\(C^1\\). In data-driven settings one often has only oracle access: the ability to evaluate a form at arbitrary points and tangent vectors, with no closed-form expression and no mesh.

Building on a flux-based reformulation of the exterior derivative, recently developed by the author with Fadel and Sá Earp, in which the exterior derivative is recovered as a limit of normalized boundary integrals over shrinking blocks, we describe a mesh-free, symbol-free numerical scheme for exterior differentiation, valid under regularity assumptions weaker than \\(C^1\\).

We demonstrate the method in \\(\mathbb{R}^2\\), \\(\mathbb{R}^3\\) and on the sphere \\(S^2\\), verifying Stokes' theorem, the identity \\(d\circ d=0\\), and Gauss--Bonnet purely from pointwise samples, and detecting de Rham cohomology (closed-but-not-exact forms) from data. Companion Jupyter notebooks accompany the paper.

This paper is based on a tutorial delivered at DANGER: Data, Numbers, and Geometry (Banff, April 2026). The combined notes from all three tutorials at that workshop, with Jessica N. Howard and Yidi Qi, are available as [arXiv:2610.07220](https://arxiv.org/abs/2610.07220).
