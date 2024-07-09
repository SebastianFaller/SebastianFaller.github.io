---
title: "Password-Protected Key Retrieval with(out) HSM Protection"
collection: publications
permalink: /publication/ppkr
date: 2024-07-09
venue: 'CCS 2024'
authors: 'Sebastian Faller, Tobias Handirk, Julia Hesse, Máté Horváth, Anja Lehmann'
abstract: "Password-protected key retrieval (PPKR) enables users to store and retrieve high-entropy keys from a server securely. The process is bootstrapped from a human-memorizable password only, addressing the challenge of how end-users can manage cryptographic key material. The core security requirement is protection against a corrupt server, which should not be able to learn the key or offline- attack it through the password protection. PPKR is deployed at a large scale with the WhatsApp Backup Protocol (WBP), allowing users to access their encrypted messaging history when switching to a new device. Davies et al. (Crypto’23) formally analyzed the WBP, proving that it satisfies most of the desired security. The WBP uses the OPAQUE protocol for password-based key exchange as a building block and relies on the server using a hardware security module (HSM) for most of its protection. In fact, the security analysis assumes that the HSM is incorruptible – rendering most of the heavy cryptography in the WBP obsolete. In this work, we explore how provably secure and efficient PPKR can be built that either relies strongly on an HSM – but then takes full advantage of that – or requires less trust assumption for the price of more advanced cryptography. To this end, we expand the definitional work by Davies et al. to allow the analysis of PPKR with fine-grained HSM corruption, such as leakage of user records or attestation keys. For each scenario, we aim to give minimal PPKR solutions. For the strongest corruption setting, namely a fully corrupted HSM, we propose a protocol with a simpler design and better efficiency than the WBP. We also fix an attack related to client authentication that was identified by Davies et al."
---

