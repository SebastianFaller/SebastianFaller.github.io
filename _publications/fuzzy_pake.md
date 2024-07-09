---
title: "Generalized Fuzzy Password-Authenticated Key Exchange from Error Correcting Codes"
collection: publications
permalink: /publication/fuzzy_pake
venue: 'ASIACRYPT 2023'
date: 2023-12-19
authors: 'Jonathan Bootle, Johannes Ernst, Sebastian Faller, Julia Hesse, Kristina Hostáková'
eprint: 'https://eprint.iacr.org/2023/1415'
proceedings: 'https://doi.org/10.1007/978-981-99-8742-9_4'
abstract: 'Fuzzy Password-Authenticated Key Exchange (fuzzy PAKE) allows cryptographic keys to be generated from authentication data that is both fuzzy and of low entropy. The strong protection against offline attacks offered by fuzzy PAKE opens an interesting avenue towards secure biometric authentication, typo-tolerant password authentication, and automated IoT device pairing. Previous constructions of fuzzy PAKE are either based on Error Correcting Codes (ECC) or generic multi-party computation techniques such as Garbled Circuits. While ECC-based constructions are significantly more efficient, they rely on multiple special properties of error correcting codes such as maximum distance separability and smoothness. 
We contribute to the line of research on fuzzy PAKE in two ways. First, we identify a subtle but devastating gap in the security analysis of the currently most efficient fuzzy PAKE construction (Dupont et al., Eurocrypt 2018), allowing a man-in-the-middle attacker to test individual password characters. Second, we provide a new fuzzy PAKE scheme based on ECC and PAKE that provides a built-in protection against individual password character guesses and requires fewer, more standard properties of the underlying ECC. Additionally, our construction offers better error correction capabilities than previous ECC-based fuzzy PAKEs.'
---

