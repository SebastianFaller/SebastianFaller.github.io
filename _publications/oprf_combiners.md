---
title: "Combining Oblivious Pseudorandom Functions"
collection: publications
permalink: /publication/oprf_combiners
venue: 'to appear at Eurocrypt 26'
date: 2026-05-01
authors: 'Sebastian Faller, Marc Fischlin, Julius Hardt, Julia Hesse'
eprint: 'https://eprint.iacr.org/2025/1084'
proceedings: ' '
abstract: "An oblivious pseudorandom function (OPRF) is an interactive protocol between a client and server, where the client aims to evaluate a keyed pseudorandom function for a key held by the server, without revealing its input. OPRFs are a versatile tool for enhancing privacy, inciting extensive research and standardization efforts in this area. The round-efficient 2Hash-Diffie-Hellman OPRF is widely deployed, but unfortunately, it is prone to quantum attacks. The search for post-quantum alternatives started in 2019 and is currently more disputed, with several candidates on the table.Given the lack of test of time of post-quantum OPRFs and their underlying cryptographic assumptions, hybridization can help mitigate risks in this interim period. Most preferably, we want to combine existing classical deployments like 2HashDH with post-quantum candidates. However, analogous two-party settings like oblivious transfer, where both parties have security requirements, indicate that combining OPRFs might be trickier than it is for hashing or encryption. In this paper, we give combiners for OPRFs with minimal overhead over the combined schemes. We also formally prove that 'ideal' combiners, i.e., ones that do not make additional assumptions on how an underlying OPRF may break, cannot exist. Our constructions avoid this theoretical result by assuming the underlying OPRFs to satisfy certain statistical guarantees. Crucially, these extra conditions are satisfied by both the 2Hash-Diffie-Hellman OPRF and the currently most efficient post-quantum candidates, rendering our results suitable for upgrading existing deployments with quantum-safe guarantees already today."
---

