---
title: "HybridDep: An elastic hybrid resources allocation strategy for I/O-intensive applications"
collection: publications
category: manuscripts
permalink: /publication/2025-iet-hybriddep
excerpt: 'We propose HybridDep, an elastic hybrid deployment strategy for multiple I/O-intensive applications that exploits staggered peak and valley patterns in both temporal and spatial dimensions to minimize deployment cost while ensuring QoS.'
date: 2025-01-03
venue: 'IET Communications'
paperurl: 'https://doi.org/10.1049/cmu2.70007'
citation: 'Pengmiao Li, Yuchao Zhang, Shaoxuan Yun, Fucai Yu, and Aizhi Wu. (2025). &quot;HybridDep: An elastic hybrid resources allocation strategy for I/O-intensive applications.&quot; <i>IET Communications</i>.'
---
Along with the rapid development of B5G/6G, the number of applications grows rapidly and the data amount explodes exponentially, putting a massive burden on the resource-limited edge servers. To fully utilize the limited resources, virtualization technology is introduced to provide elastic deployment for applications in edge servers. But for I/O-intensive applications, allocating elastic resources is not as easy as for compute-intensive ones, because the amount of required I/O resources is unknown due to the request uncertainty. In this paper, we propose an elastic hybrid deployment strategy HybridDep, which consists of two phases: coarse-grained scheduling and fine-grained tuning. Coarse-grained minimizes deployment costs based on complementary peak and valley patterns in time and space dimensions by integer linear programming. Fine-grained dynamically adjusts each application's resources allocated to meet the time-varying application resource requirements. Results show that the deployment cost is 3.2% below the Optimal's while ensuring high quality of service (QoS).
