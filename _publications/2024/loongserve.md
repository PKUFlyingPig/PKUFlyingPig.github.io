---
title:          "LoongServe: Efficiently Serving Long-context Large Language Models with Elastic Sequence Parallelism"
date:           2024-10-12 00:01:00 +0800
selected:       false
pub:            "Symposium on Operating Systems Principles (SOSP)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
    This paper propose a new parallelism paradigm, elastic sequence parallelism (ESP), to elastically adapt to the variance between different requests and phases. Based on ESP, we design and build LoongServe, an LLM serving system that (1) improves computation efficiency by elastically adjusting the degree of parallelism in real-time, (2) improves communication efficiency by reducing key-value cache migration overhead and overlapping partial decoding communication with computation, and (3) improves GPU memory efficiency by reducing key-value cache fragmentation across instances.
cover:    /assets/images/covers/loongserve.png
authors:
  - Bingyang Wu
  - Shengyu Liu
  - Yinmin Zhong
  - Peng Sun
  - Xuanzhe Liu
  - Xin Jin
links:
  Paper: https://arxiv.org/pdf/2404.09526
  Code: https://github.com/LoongServe/LoongServe
---
