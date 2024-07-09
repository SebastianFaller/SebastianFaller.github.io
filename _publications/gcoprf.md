---
title: "Composable Oblivious Pseudo-Random Functions via Garbled Circuits"
collection: publications
permalink: /publication/gcoprf
venue: 'LATINCRYPT 2023'
date: 2023-09-26
authors: 'Sebastian Faller, Astrid Ottenhues, Johannes Ottenhues'
eprint: 'https://eprint.iacr.org/2023/1176'
proceedings: 'https://doi.org/10.1007/978-3-031-44469-2_13'
abstract: 'Oblivious Pseudo-Random Functions (OPRFs) are a central
tool for building modern protocols for authentication and distributed
computation. For example, OPRFs enable simple login protocols that do
not reveal the password to the provider, which helps to mitigate known
shortcomings of password-based authentication such as password reuse
or mix-up. Reliable treatment of passwords becomes more and more
important as we login to a multitude of services with different passwords
in our daily life.
To ensure the security and privacy of such services in the long term,
modern protocols should always consider the possibility of attackers with
quantum computers. Therefore, recent research has focused on constructing
post-quantum-secure OPRFs. Unfortunately, existing constructions
either lack efficiency, or they are based on complex and relatively new
cryptographic assumptions, some of which have lately been disproved.
In this paper, we revisit the security and the efficiency of the well-known
“OPRFs via Garbled Circuits” approach. Such an OPRF is presumably
post-quantum-secure and built from well-understood primitives, namely
symmetric cryptography and oblivious transfer. We investigate security
in the strong Universal Composability model, which guarantees security
even when multiple instances are executed in parallel and in conjunction
with arbitrary other protocols, which is a realistic scenario in today’s
internet. At the same time, it is faster than other current post-quantumsecure
OPRFs. Our implementation and benchmarks demonstrate that
our proposed OPRF is currently among the best choices if the privacy of
the data has to be guaranteed for a long time.'
---

