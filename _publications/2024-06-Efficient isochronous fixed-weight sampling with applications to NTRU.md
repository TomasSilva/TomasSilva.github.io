---
title: "Efficient isochronous fixed-weight sampling with applications to NTRU"
collection: publications
category: manuscripts
permalink: /publication/2024-06-Efficient isochronous fixed-weight sampling with applications to NTRU
excerpt: #
date: 2024-06-03
venue: 'IACR Communications in Cryptology, Vol. 1, No. 2'
paperurl: 'https://cic.iacr.org/p/1/2/14'
citation: #
---
[IACR Communications in Cryptology, Vol. 1, No. 2](https://cic.iacr.org/p/1/2/14)

We present a solution to the open problem of designing a linear-time,
unbiased and timing attack-resistant shuffling algorithm for fixed-weight sampling.
Although it can be implemented without timing leakages of secret data in any
architecture, we illustrate with ARMv7-M and ARMv8-A implementations; for the
latter, we take advantage of architectural features such as NEON and conditional
instructions, which are representative of features available on architectures targeting
similar systems, such as Intel. Our proposed algorithm improves asymptotically
upon the current approach based on constant-time sorting networks (O(n) versus
O(n log2 n)), and an implementation of the new algorithm applied to NTRU is
also faster in practice, by a factor of up to 6.91 (591%) on ARMv8-A cores and
12.89 (1189%) on the Cortex-M4; it also requires fewer uniform random bits. This
translates into performance improvements for NTRU encapsulation, compared to
state-of-the-art implementations, of up to 50% on ARMv8-A cores and 72% on the
Cortex-M4, and small improvements to key generation (up to 2.7% on ARMv8-A
cores and 6.1% on the Cortex-M4), with negligible impact on code size and a slight
improvement in RAM usage for the Cortex-M4.
