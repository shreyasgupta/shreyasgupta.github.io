---
title: "Secure Vickrey Auctions with Rational Parties"
collection: publications
category: conferences
permalink: /publication/spa
excerpt: 'This paper is has a rational security model that assumes no honest parties'
date: 2024-12-09
venue: 'CCS 24: Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security'
paperurl: 'https://doi.org/10.1145/3658644.3670311'
citation: 'Chaya Ganesh, **Shreyas Gupta**, Bhavana Kanukurthi, and Girisha Shankar. 2024. Secure Vickrey Auctions with Rational Parties. In Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS 24). Association for Computing Machinery, New York, NY, USA, 4062–4076. https://doi.org/10.1145/3658644.3670311'
---

In this work, we construct a second price (Vickrey) auction protocol (SPA), which does not require any auctioneers and ensures total privacy in the presence of rational parties participating in the auction. In particular, the confidentiality of the highest bid and the identity of the second highest bidder are protected. We model the bidders participating in the second price auction as rational, computationally bounded and privacy-sensitive parties. These are self-interested agents who care about winning the auction more than learning about the private bids of other parties. A rational party does not deviate from the protocol arbitrarily but does so only for its own individual 'advantage' -- without any consideration for others. Such an advantage is modelled using suitable utility functions.
We show that for rational and computationally bounded parties participating in our second-price auctions protocol, there exists a privacy-preserving dominant strategy equilibrium in which every party prefers to follow the protocol rather than to deviate.
Our protocol is implemented using open-source cryptographic constructs. Running our SPA protocol on commodity hardware with 15 bidders, with bids of length 10 bits, completes in 1.26sec and has total communication of 0.77MB whereas, under similar conditions, Atlas (semi-honest) protocol takes 40% more time (2.11 sec) and 87% more communication (6.09MB).
