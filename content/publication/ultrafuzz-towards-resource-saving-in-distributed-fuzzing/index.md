---
title: "UltraFuzz: Towards Resource-saving in Distributed Fuzzing"
publication_types:
  - "2"
authors:
  - Xu Zhou
  - Pengfei Wang 􀀀
  - Chenyifan Liu
  - Tai Yue
  - Yingying Liu
  - Congxi Song
  - Kai Lu
  - Qidi Yin
  - Xu Han
author_notes:
  - ""
  - Correspondence
  - ""
doi: 10.1109/TSE.2022.3219520
publication: IEEE Transactions on Software Engineering
publication_short: IEEE TSE
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: |-
  Recent research has sought to improve fuzzing
  performance via parallel computing. However, researchers focus
  on improving efficiency while ignoring the increasing cost of
  testing resources. Parallel fuzzing in the distributed environment
  amplifies the resource-wasting problem caused by the random
  nature of fuzzing. In the parallel mode, owing to the lack
  of an appropriate task dispatching scheme and timely fuzzing
  status synchronization among different fuzzing instances, task
  conflicts and workload imbalance occur, making the resource-wasting
  problem severe. In this paper, we design UltraFuzz,
  a fuzzer for resource-saving in distributed fuzzing. Based on
  centralized dynamic scheduling, UltraFuzz can dispatch tasks
  and schedule power globally and reasonably to avoid resource-wasting.
  Besides, UltraFuzz can elastically allocate computing
  power for fuzzing and seed evaluation, thereby avoiding the
  potential bottleneck of seed evaluation that blocks the fuzzing
  process. UltraFuzz was evaluated using real-world programs, and
  the results show that with the same testing resource, UltraFuzz
  outperforms state-of-the-art tools, such as AFL, AFL-P, PAFL,
  and EnFuzz. Most importantly, the experiment reveals certain
  results that seem counter-intuitive, namely that parallel fuzzing
  can achieve “super-linear acceleration” when compared with
  single-core fuzzing. We conduct additional experiments to reveal
  the deep reasons behind this phenomenon and dig deep into
  the inherent advantages of parallel fuzzing over serial fuzzing,
  including the global optimization of seed energy scheduling and
  the escape of local optimal seed. Additionally, 24 real-world
  vulnerabilities were discovered using UltraFuzz.
date: 2022-12-11T10:31:03.043Z
---
