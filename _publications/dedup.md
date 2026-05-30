---
title: "Secure Fuzzy Deduplication: Definitions and Constructions"
collection: publications
category: conferences
permalink: /publication/Dedup
excerpt: 'This paper takes the step to formally define secure fuzzy deduplication'
date: 2025-11-14
venue: 'CCSW 25: Proceedings of the 2025 Cloud Computing Security Workshop'
paperurl: 'https://doi.org/10.1145/3733812.3765537'
citation: 'Anirban Chakrabarti, Shreyas Gupta, Bhavana Kanukurthi, and Girisha Shankar. 2025. Secure Fuzzy Deduplication: Definitions and Constructions. In Proceedings of the 2025 Cloud Computing Security Workshop (CCSW 25). Association for Computing Machinery, New York, NY, USA, 80–94. https://doi.org/10.1145/3733812.3765537'
---

At Eurocrypt 2013, Bellare, Keelveedhi, and Ristenpart initiated a rigorous study of the important, practically-motivated problem of "Secure Deduplication". Deduplication deals with storing data efficiently by storing duplicate data only once; when data is spread across multiple parties, ensuring privacy becomes an added concern. Even though deduplication and privacy might appear to be mutually incompatible, Bellare et al. offer a meaningful definition as well as theoretical and practical constructions for the same. Our work considers the setting of Secure Fuzzy Deduplication where deduplication of nearby–and not equal–files is desired. We provide a rigorous definition of fuzzy message locked encryption as well as fuzzy deduplication. We build constructions that satisfy our definitions in the random oracle model and provide proof-of-concept implementations of the same by instantiating our random oracle using AES. Finally, we propose a general paradigm of data-adaptive clustering, where the clusters, which are intrinsic to fuzzy deduplication, are created based on the data. We believe this paradigm yields better deduplication efficiency for typical use cases involving time-series data, such as medical images (e.g., X-ray scans taken over time), CCTV footage from secure locations, DNA sequencing datasets, and longitudinal studies that collect large volumes of data (e.g., voice samples, videos capturing subject movement).
