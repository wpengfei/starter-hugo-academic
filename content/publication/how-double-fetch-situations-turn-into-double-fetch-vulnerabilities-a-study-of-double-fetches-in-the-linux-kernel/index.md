---
publication_types:
  - "1"
authors:
  - Pengfei Wang*
  - Jens Krinke
  - Kai Lu
  - Gen Li
  - Steve Dodier-Lazaro
publication_short: USENIX Security '17
abstract: >-
  We present the first static approach that systematically detects potential
  double-fetch vulnerabilities in the Linux kernel. Using a pattern-based
  analysis, we identified 90 double fetches in the Linux kernel. 57 of these
  occur in drivers, which previous dynamic approaches were unable to detect
  without access to the corresponding hardware. We manually investigated the 90
  occurrences and

  inferred three typical scenarios in which double fetches occur. We discuss each of them in detail. We further developed a static analysis, based on the Coccinelle matching engine, that detects double-fetch situations which can cause kernel vulnerabilities. When applied to the Linux, FreeBSD, and Android kernels, our approach found six previously unknown double-fetch bugs, four of them in drivers, three of which are exploitable double-fetch vulnerabilities. All of the identified bugs and vulnerabilities have been confirmed and patched by maintainers. Our approach has been adopted by the Coccinelle team and

  is currently being integrated into the Linux kernel patch vetting. Based on our study, we also provide practical solutions for anticipating double-fetch bugs and vulnerabilities. We also provide a solution to automatically patch detected double-fetch bugs.
draft: false
url_pdf: publication\how-double-fetch-situations-turn-into-double-fetch-vulnerabilities-a-study-of-double-fetches-in-the-linux-kernel/sec17-wang.pdf
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "How Double-Fetch Situations turn into Double-Fetch Vulnerabilities: A
  Study of Double Fetches in the Linux Kernel"
subtitle: ""
publication: The 26th USENIX Security Symposium, Vancouver, Aug. 16-18, 2017.
featured: true
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
date: 2017-08-16T06:03:35.745Z
url_slides: https://www.usenix.org/sites/default/files/conference/protected-files/usenixsecurity_slides_wang_pengfei_.pdf
url_poster: ""
url_code: ""
---
