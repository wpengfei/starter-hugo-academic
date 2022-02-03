---
title: "MEBS: Uncovering Memory Life-Cycle Bugs in Operating System Kernels"
url_pdf: publication/mebs-uncovering-memory-life-cycle-bugs-in-operating-system-kernels/JCST-MEBS.pdf
publication_types:
  - "2"
authors:
  - Gen Zhang
  - PengFei Wang
  - Tai Yue
  - Xu Zhou
  - Kai Lu
doi: 10.1007/s11390-021-1593-4
publication: "Journal of Computer Science and Technology (ISSN:
  1000-9000),36(6): pp1248-1268, Nov. 2021."
publication_short: JCST
abstract: "Allocation, dereferencing, and freeing of memory data in kernels are
  coherently linked. There widely exist real cases where the correctness of
  memory is compromised. This incorrectness in kernel memory brings about
  signi\fficant

  security issues, e.g., information leaking. Though memory allocation,
  dereferencing, and freeing are closely related, previous work failed to
  realize they are closely related. In this paper, we study the life-cycle of
  kernel memory, which consists of allocation, dereferencing, and freeing.
  Errors in them are called memory life-cycle (MLC) bugs. We propose an in-depth
  study of MLC bugs and implement a memory life-cycle bug sanitizer (MEBS) for
  MLC bug detection. Utilizing an inter-procedural global call graph and novel
  identi\ffication approaches, MEBS can reveal memory allocation, dereferencing,
  and freeing sites in kernels. By constructing a modi\ffied defi\fne-use chain
  and examining the errors in the life-cycle, MLC bugs can be identifi\fed.
  Moreover, the experimental results on the latest kernels demonstrate that MEBS
  can effectively detect

  MLC bugs, and MEBS can be scaled to different kernels. More than 100 new
  bugs are exposed in Linux and FreeBSD, and 12 common vulnerabilities and
  exposures (CVE) are assigned."
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-11-01T15:05:00.000Z
---
