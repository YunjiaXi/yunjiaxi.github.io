---
title: "Efficiency Unleashed: Inference Acceleration for LLM-based Recommender Systems with Speculative Decoding"
collection: publications
category: conferences
permalink: /publication/2025-laser
excerpt: '**Yunjia Xi**, Hangyu Wang, Bo Chen, Jianghao Lin, Menghui Zhu, Weiwen Liu, Ruiming Tang, Weinan Zhang, Yong Yu'
date: 2025-04-04
venue: "Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR'25)"
paperurl: 'https://arxiv.org/pdf/2408.05676'
---

The past few years have witnessed a growing interest in LLM-based recommender systems (RSs), although their industrial deployment remains in a preliminary stage. Most existing deployments leverage LLMs offline as feature enhancers, generating augmented knowledge for downstream tasks. However, in recommendation scenarios with numerous users and items, even offline knowledge generation with LLMs demands significant time and computational resources. This inefficiency arises from the autoregressive nature of LLMs. A promising solution is speculative decoding, a Draft-Then-Verify approach that increases the number of tokens generated per decoding step. In this work, we first identify recommendation knowledge generation as a highly fitting use case for retrieval-based speculative decoding. Then, we discern its two characteristics: (1) the vast number of items and users in RSs leads to retrieval inefficiency, and (2) RSs exhibit high diversity tolerance for LLM-generated text. Building on these insights, we introduce Lossless Acceleration via Speculative Decoding for LLM-based Recommender Systems (LASER), which features a Customized Retrieval Pool to enhance retrieval efficiency and Relaxed Verification to improve the acceptance rate of draft tokens. LASER achieves a 3-5x speedup on public datasets and saves about 67\% of computational resources during the online A/B test on a large-scale advertising scenario with lossless downstream recommendation performance.