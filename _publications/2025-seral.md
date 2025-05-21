---
title: "Bursting Filter Bubble: Enhancing Serendipity Recommendations with Aligned Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-seral
excerpt: '**Yunjia Xi**, Muyan Weng, Wen Chen, Chao Yi, Dian Chen, Gaoyang Guo, Mao Zhang, Jian Wu, Yuning Jiang, Qingwen Liu, Yong Yu, Weinan Zhang'
date: 2025-05-16
venue: "Proceedings of the 31th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'25)"
paperurl: 'https://arxiv.org/pdf/2502.13539'
---

Recommender systems (RSs) often suffer from the feedback loop phenomenon, e.g., RSs are trained on data biased by their recommendations. This leads to the filter bubble effect that reinforces homogeneous content and reduces user satisfaction. To this end, serendipity recommendations, which offer unexpected yet relevant items, are proposed. Recently, large language models (LLMs) have shown potential in serendipity prediction due to their extensive world knowledge and reasoning capabilities. However, they still face challenges in aligning serendipity judgments with human assessments, handling long user behavior sequences, and meeting the latency requirements of industrial RSs. To address these issues, we propose SERAL (Serendipity Recommendations with Aligned Large Language Models), a framework comprising three stages: (1) Cognition Profile Generation to compress user behavior into multi-level profiles; (2) SerenGPT Alignment to align serendipity judgments with human preferences using enriched training data; and (3) Nearline Adaptation to integrate SerenGPT into industrial RSs pipelines efficiently. Online experiments demonstrate that SERAL improves exposure ratio (PVR), clicks, and transactions of serendipitous items by 5.7%, 29.56%, and 27.6%, enhancing user experience without much impact on overall revenue. Now, it has been fully deployed in the "Guess What You Like" of the Taobao App homepage.
