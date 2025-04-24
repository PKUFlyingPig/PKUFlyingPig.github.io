---
title:          "StreamRL: Scalable, Heterogeneous, and Elastic RL for LLMs with Disaggregated Stream Generation"
date:           2025-05-1 00:01:00 +0800
selected:       true
pub:            "In preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
    StreamRL is designed with disaggregation from first principles and fully unlocks its potential by addressing two types of performance bottlenecks in existing disaggregated RL frameworks: pipeline bubbles, caused by stage dependencies, and skewness bubbles, resulting from long-tail output length distributions. To address pipeline bubbles, StreamRL breaks the traditional stage boundary in synchronous RL algorithms through stream generation and achieves full overlapping in asynchronous RL. To address skewness bubbles, StreamRL employs an output-length ranker model to identify long-tail samples and reduces generation time via skewness-aware dispatching.

cover:    /assets/images/covers/streamrl.png
authors:
    - Yinmin Zhong
    - Zili Zhang
    - Xiaoniu Song
    - Hanpeng Hu
    - Chao Jin
    - Bingyang Wu
    - Nuo Chen
    - Yukun Chen
    - Yu Zhou
    - Changyi Wan
    - Hongyu Zhou
    - Yimin Jiang
    - Yibo Zhu
    - Daxin Jiang

links:
  Paper: https://arxiv.org/abs/2504.15930
---