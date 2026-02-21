---
title:          "FastServe: Iteration-Level Preemptive Scheduling for Large Language Model Inference"
date:           2026-05-04 00:01:00 +0800
selected:       false
pub:            "Networking Systems Design and Implementation (NSDI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
    This paper presents FastServe, a distributed inference serving system for LLMs. FastServe exploits the autoregressive pattern of LLM inference to enable preemption at the granularity of each output token. FastServe uses preemptive scheduling to minimize JCT with a novel skip-join Multi-Level Feedback Queue scheduler.

cover: /assets/images/covers/fastserve.png

authors:
  - Bingyang Wu*
  - Yinmin Zhong*
  - Zili Zhang*
  - Gang Huang
  - Xuanzhe Liu
  - Xin Jin

links:
  Paper: https://www.usenix.org/conference/nsdi26/presentation/wu-bingyang
  Code: https://github.com/LLMServe/FastServe
---
