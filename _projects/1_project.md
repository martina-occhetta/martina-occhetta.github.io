---
layout: page
title: PertEval-scFM
description: Benchmarking single-cell foundation models for perturbation effect prediction
img: assets/img/PertEval-scFM.png
importance: 1
category: work
related_publications: true
---

**PertEval-scFM: Benchmarking single-cell foundation models for perturbation effect prediction**

_In silico_ modeling of transcriptional responses to perturbations is crucial for advancing our understanding of cellular processes and disease mechanisms. We present PertEval-scFM, a standardized framework designed to evaluate models for perturbation effect prediction. We apply PertEval-scFM to benchmark zero-shot single-cell foundation model (scFM) embeddings against simpler baseline models to assess whether these contextualized representations enhance perturbation effect prediction. Our results show that scFM embeddings do not provide consistent improvements over baseline models, especially under distribution shift. Additionally, all models struggle with predicting strong or atypical perturbation effects. Overall, this study provides a systematic evaluation of zero-shot scFM embeddings for perturbation effect prediction, highlighting the challenges of this task and revealing the limitations of current-generation scFMs. Our findings underscore the need for specialized models and high-quality datasets that capture a broader range of cellular states. Source code and documentation can be found on <a href='https://github.com/aaronwtr/PertEval'>Github</a>. Pre-print available at {% cite wenteler_perteval_2024 %}.
