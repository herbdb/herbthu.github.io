---
title: "Coda: Achieving Multipath Data Transmission in NDN"
collection: publications
permalink: /publications/coda
venue: "IEEE IPCCC"
date: 2018-8-24
citation: 'Dongbiao He, Jinlei Jiang, Guangwen Yang, Cedric Westphal. Coda: Achieving Multipath Data Transmission in NDN. Proceedings of IPCCC. IEEE, 2018'
---
[Download paper here](https://herbdb.github.io/files/coda.pdf)

## Abstract
The exponential growth of data traffic raises a great challenge to content delivery in current TCP/IP networks. To answer this challenge, Information-Centric Networking (ICN) has been proposed with the purpose of bringing content caching and name-based content access to the network layer. Though great progress has been made, most existing ICN proposals lack support for parallel data transfer over multiple paths with low data redundancy. To deal with the issue, we present CODA, a fully distributed cooperative multipath data transmission solution that enhances content delivery further. Taking Named Data Networking (NDN) as a basis, CODA works in a distributed manner with the following contributions: 1) it extends the standard Interest model in NDN to support transmission of data over multiple paths so as to reduce the flow completion time; 2) it devises a traffic scheduling model to form parallel paths for transmitting data in a cooperative way; and 3) it proposes a transmission control scheme to select paths in an efficient and reliable manner. Extensive simulation comparisons with existing data transmission methods show that: 1) CODA speeds up the data rate twice as high as that of the best-route method; and 2) the amount of Interests required by CODA to build multiple data transmission paths in the network accounts for only 66% of that by MSRT, another multipath transmission proposal.