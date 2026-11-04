---
title: "Learning Almost Complex and Complex Structures"
collection: publications
category: preprints
permalink: /publication/2026-11-Learning Almost Complex and Complex Structures
excerpt: 'joint with Edward Hirst, Tancredi Schettini Gherardini, and Jakob Stein' 
date: 2026-11-02
venue: #
slidesurl: # 
paperurl: 'https://arxiv.org/abs/2611.03872'
citation: # 
---
[arXiv:2611.03872](https://arxiv.org/abs/2611.03872) -- [code and data](https://github.com/edhirst/learning-acs-cs)

We study the numerical constructions of almost complex and complex structures on spheres and products of spheres up to real dimension six. Our general set-up parametrises almost complex structures via a global matrix field in an ambient Euclidean space, compressed by the tangent projector. The projector's algebraic residual measures the almost complex condition, while its Nijenhuis tensor is evaluated in the intrinsic norm of the round product metric.

Polynomial features and neural networks are trained without prescribed targets to perform general searches for these structures. The almost complex search passes numerical admissibility checks on all nine examples that admit such structures and rejects \\(S^4\\), where a topological obstruction is known. A matrix correction then enforces the almost complex identity, subject to a novel uniform admissibility condition.

For integrability, a free polynomial representation with Levenberg--Marquardt optimisation learns the complex structures on \\(S^2\times S^2\\), \\(S^3\times S^1\\), \\(S^3\times S^3\\) and \\(S^5\times S^1\\), with the largest Nijenhuis norms found by adversarial search all below \\(10^{-9}\\). These general searches were unsuccessful on \\(S^6\\), \\(S^4\times S^2\\) and \\(S^4\times T^2\\). Therefore, for these three cases direct numerical reconstructions were built in torus-fibred coordinates. They are integrable by construction, satisfy their compatibility conditions to better than \\(10^{-11}\\), and corroborate the recent constructions on \\(S^6\\) and \\(S^4\times S^2\\).
