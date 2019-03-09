---
title: "RankRoute: Efficient Interests Forwarding by Nodes Ranking"
collection: publication
permalink: /publication/rankroute
venue: "IEEE ICNC"
date: 2019-02
citation: 'Dongbiao He, Cedric Westphal, and J.J. Garcia-Luna-Aceves. 2018. Joint Rate and FoV adaptation in immersive video streaming. In SIGCOMM Workshop on AR/VR Network, August 24, 2018, Budapest, Hungary'
---
[Download paper here](https://herbdb.github.io/herbthu.github.io/files/rankr.pdf)

## Abstract
The exponential growth of data traffic creates great challenges for content delivery. As a novel paradigm, Information Centric Network (ICN) can better deliver content using Interest aggregation and in-network caching. However, most research has ignored the potential improvement of using paths that are individually sub-optimal between a single client and the content, but offer opportunity to aggregate the traffic from multiple clients along the path. We consider Named Data Networking (NDN) as the basic architecture, and present RankRoute, an Interest forwarding solution that guides the Interests to meet two objectives: 1) allow for Interest aggregation and the creation of multicast opportunities; 2) discover nearby replicas of the content. To achieve this purpose, RankRoute ranks the nodes by their connectivity and the popularity of the workload they serve. Comparisons with several benchmark forwarding strategies show that RankRoute reduces the data transfer completion latency by almost 32%, while the rate of dropped packets is comparable with the ideal Best-Route algorithm.