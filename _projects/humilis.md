---
title: "Cloud/Edge computing support Infrastructure Development"
collection: projects
type: "Cloud Computing"
permalink: /projects/humilis
venue: "Tsinghua University"
date: 2013-09-01
location: "Beijing, China"
---

In this project, we developed a lightweight virtual cluster management system, named as Humilis, for enabling adaptable resource management in practice. For the easy transformation from cloud to edge with the network, Humilis decouples the control module, computing module and storage module in order to fit the uncertain requirements of edge computing. This design offers flexibility in allocating the virtual instances disk files in a shared disk manner or non-shared disk manner. In this architecture, a mobile user exploits virtual machine (VM) technology to instantiate customized service software on a nearby cloudlet rapidly, and then uses that service over a wireless connection.

<p align="center">
  <img src="https://herbdb.github.io/images/arch.jpg?raw=true" alt="Photo" style="width: 450px;"/> 
</p>

# Key points
* Support self-defined software installation and KVM/LXC on-line migration;
* Support Data Deduplication Storage for VM images;
* A Cache manage plane for coordianting VM image blocks distribution and fast migration in WAN.


