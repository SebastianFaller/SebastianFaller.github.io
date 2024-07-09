---
title: "Security Analysis of the WhatsApp End-to-End Encrypted Backup Protocol"
collection: publications
permalink: /publication/whatsapp_backups
venue: 'CRYPTO 2023'
date: 2023-08-09
authors: 'Gareth T. Davies, Sebastian Faller, Kai Gellert, Tobias Handirk, Julia Hesse, Máté Horvath, Tibor Jager'
eprint: 'https://eprint.iacr.org/2023/843'
proceedings: 'https://doi.org/10.1007/978-3-031-38551-3_11'
abstract: 'WhatsApp is an end-to-end encrypted (E2EE) messaging service used by billions of people. In late 2021, WhatsApp rolled out a new protocol for backing up chat histories. The E2EE WhatsApp backup protocol (WBP) allows users to recover their chat history from passwords, leaving WhatsApp oblivious of the actual encryption keys. The WBP builds upon the OPAQUE framework for password-based key exchange, which is currently undergoing standardization. While considerable efforts have gone into the design and auditing of the WBP, the complexity of the protocol’s design and shortcomings in the existing security analyses of its building blocks make it hard to understand the actual security guarantees that the WBP provides.
In this work, we provide the first formal security analysis of the WBP. Our analysis in the universal composability (UC) framework confirms that the WBP provides strong protection of users’ chat history and passwords. It also shows that a corrupted server can under certain conditions make more password guesses than what previous analysis suggests.'
---

