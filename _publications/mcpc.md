---
title: "MCPC: Improving In-network Caching by Network Partition"
collection: publications
permalink: /publications/mcpc
venue: "IEEE ICPADS"
date: 2018-12-11
citation: 'Dongbiao He, Jinlei Jiang, Guangwen Yang, Cedric Westphal. MCPC: Improving In-network Caching by Network Partition. Proceedings of International Conference on Parallel and Distributed Systems. IEEE, 2018 '
---
[Download paper here](https://herbdb.github.io/files/mcpc.pdf)

## Abstract
In-network caching is considered to be an important solution to efficiently using network resources to achieve a high overall content delivery performance in both information-centric networks (ICNs) and 5G wireless networks. Content placement plays a key role in achieving this goal. Unfortunately, most content placement strategies today rely on opportunistic caching due to the problem complexity. We analyze the content placement problem in detail and present MCPC, a new content placement strategy for architectures that support in-network caching. Unlike existing content placement approaches that try to increase cache hit ratio, MCPC leverages the information recorded in each network node to reduce content access latency. MCPC proposes two new mechanisms: 1) a content load allocation estimation method based on local requests aggregation information; and 2) a content placement algorithm that avoids long-distance signaling messages by partitioning the network into smaller domains. We evaluate MCPC on a variety of network topologies, cache sizes and content popularity distributions. The experimental results show that MPCP can reduce by up to 56% the content access latency while providing comparable cache hit ratios as traditional benchmarks.