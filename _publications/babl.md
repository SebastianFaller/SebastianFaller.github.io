---
title: "Black-Box Accumulation Based on Lattices"
collection: publications
permalink: /publication/babl
venue: 'IMACC 2021'
date: 2021-01-01
authors: 'Sebastian Faller, Pascal Baumer, Michael Klooss, Alexander Koch, Astrid Ottenhues, Markus Raiber'
eprint: 'https://eprint.iacr.org/2021/1303'
proceedings: 'https://doi.org/10.1007/978-3-030-92641-0_11'
abstract: 'Black-box accumulation (BBA) is a cryptographic protocol
that allows users to accumulate and redeem points, e.g. in payment
systems, and offers provable security and privacy guarantees. Loosely
speaking, the transactions of users remain unlinkable, while adversaries
cannot claim a false amount of points or use points from other users.
Attempts to spend the same points multiple times (double spending)
reveal the identity of the misbehaving user and an undeniable proof of
guilt. Known instantiations of BBA rely on classical number-theoretic
assumptions, which are not post-quantum secure. In this work, we propose
the first lattice-based instantiation of BBA, which is plausibly post-
quantum secure. It relies on the hardness of the Learning with Errors
(LWE) and Short Integer Solution (SIS) assumptions and is secure in the
Random Oracle Model (ROM).
Our work shows that a lattice-based instantiation of BBA can be realized
with a communication cost per transaction of about 199 MB if built on
the zero-knowledge protocol by Yang et al. (CRYPTO 2019) and the
CL-type signature of Libert et al. (ASIACRYPT 2017). Without any
zero-knowledge overhead, our protocol requires 1.8 MB communication.'
---

