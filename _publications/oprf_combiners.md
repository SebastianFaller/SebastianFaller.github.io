---
title: "How to (not) combine Oblivious Pseudorandom Functions"
collection: publications
permalink: /publication/oprf_combiners
venue: 'Eprint'
date: 2024-06-09
authors: 'Sebastian Faller, Julia Hesse'
eprint: 'https://eprint.iacr.org/2025/1084'
proceedings: ''
abstract: "
An oblivious pseudorandom function (OPRF) is a cryptographic tool that enables fast and secure authentication and key derivation from passwords. In the past few years, the adoption of OPRFs has flourished and today they are at the core of the PIN-protected backup methods of WhatsApp and Signal, and of privacy-enhancing browser technologies. All vendors deploy the so-called 2Hash-Diffie-Hellman (2HashDH) OPRF, which relies on discrete-logarithm-type assumptions that are standard yet known to be prone to quantum attacks.

Recent advancements in cryptographic research (e.g., Beullens et al., Eurocrypt 2025) have brought up post-quantum OPRFs that are fast enough to deploy them in the setting of, e.g., WhatsApp or Signal. Yet none of these constructions are based on standard assumptions.

In this work, we investigate combiners for OPRFs, namely a "best-of-both'' combination of a classical and a post-quantum OPRF that is secure as long as one of them is. First, we give formal evidence that so-called black-box combiners do not exist, indicating that combining OPRFs is subtle and bears similarities with other powerful yet hard-to-combine cryptographic primitives like oblivious transfer (OT).

We then give a (non-black-box) combiner for OPRFs and show that it can be instantiated with 2HashDH and the currently most efficient post-quantum OPRFs based on Legendre symbols. In particular, the reliance on the less standard Legendre-based hardness assumption does not harm the security of 2HashDH. This gives vendors a viable path to lift the security of their OPRF deployments to a post-quantum level.
"
---

