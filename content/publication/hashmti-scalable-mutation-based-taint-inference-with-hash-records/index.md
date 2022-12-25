---
title: "HashMTI: Scalable Mutation-based Taint Inference with Hash Records"
publication_types:
  - "1"
authors:
  - Xiangdong Kong
  - Yong Tang
  - Pengfei Wang
  - Shuning Wei
  - Tai Yue
publication: 2021 IEEE International Conference on Software Analysis, Evolution
  and Reengineering
publication_short: SANER 2021
abstract: >-
  Mutation-based taint inference (MTI) is a novel technique for taint analysis.
  Compared with traditional techniques

  that track propagations of taint tags, MTI infers a variable is tainted if its values change due to input mutations, which is lightweight and conceptually sound. However, there are 3 challenges to its efficiency and scalability: (1) it cannot efficiently record variable values to monitor their changes; (2) it consumes a large amount of memory monitoring variable values, especially on complex programs; and (3) its excessive memory overhead

  leads to a low hit ratio of CPU cache, which slows down the speed of taint inference. This paper presents an efficient and scalable solution named HashMTI. We first explain the above challenges based on 4 observations. Motivated by these challenges, we propose a hash record scheme to efficiently monitor changes in variable values and significantly reduce the memory overhead. The scheme is based on our specially selected and optimized hash

  functions that possess 3 crucial properties. Moreover, we propose the DoubleMutation strategy, which applies additional mutations to mitigate the limitation of the hash record and detect more taint information. We implemented a prototype of HashMTI and evaluated it on 18 real-world programs and 4 LAVA-M programs.

  Compared with the baseline OrigMTI, HashMTI significantly reduces the overhead while having similar accuracy. It achieves a speedup of 2.5X to 23.5X and consumes little memory which is on average 70.4 times less than that of OrigMTI.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-03-09T14:22:44.809Z
---
