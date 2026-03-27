---
title: "NLIR-BERT: Native Language Identification from Gaze — Logistic Regression vs. BERT on MECO-L2"
collection: publications
permalink: /publication/2026-01-NLIR-BERT
excerpt: 'Comparative study of logistic regression and a BERT-based classifier for native language identification from eye-tracking gaze data on the MECO-L2 dataset, showing BERT produces linguistically more meaningful language clustering despite comparable accuracy on small data.'
date: 2026-01-01
venue: 'IEEE 7th International Conference on Cybernetics, Cognition and Machine Learning Applications (ICCCMLA 2025), IEEE'
paperurl: 'https://orbit.dtu.dk/en/publications/native-language-identification-from-gaze-logistic-regression-vs-b/'
citation: 'Tashk, A., Ilyas, C.M.A., Cooreman, B., Beier, S. and Bækgaard, P. (2026). &quot;Native Language Identification from Gaze: Logistic Regression vs. BERT on MECO-L2.&quot; In <i>Proceedings of ICCCMLA 2025</i>. IEEE. (Accepted/In press)'
---

<center><img src='/images/publications/NLIR-BERT.png'></center>

## Abstract

Native Language Identification from Reading (NLIR) is an emerging interdisciplinary field that leverages eye-tracking technology to investigate how readers' native languages influence their second language (L2) reading behaviour. Different first-language backgrounds produce distinct gaze signatures — patterns of fixation, regression, and saccade — that encode language-specific cognitive processing strategies.

This study replicates a linear **logistic regression model** for NLIR and introduces an enhanced **BERT-based classifier** to identify native languages from reading patterns in the **MECO-L2 Wave 1** dataset, considering either the full set of nationalities or a targeted subset. The effect of new feature sets on the predictive performance of both models is examined systematically.

To address the limited number of participants and ensure robust generalisation, **Monte Carlo simulation with 20 randomised splits** for training, validation, and testing is employed. Results show that while the logistic regression model achieves performance levels comparable to BERT — primarily due to the small dataset constraining BERT's full training potential — the **BERT classifier produces a linguistically more meaningful clustering** of native languages, aligning better with findings in the existing NLIR literature.

## Key Contributions

- First BERT-based classifier applied to Native Language Identification from Reading (NLIR) using eye-tracking gaze features
- Rigorous comparison against logistic regression on the MECO-L2 Wave 1 benchmark dataset
- Monte Carlo simulation with 20 randomised splits for robust small-sample evaluation
- Demonstrates that BERT captures linguistically coherent language clusters even when accuracy metrics converge with simpler models
- Provides feature importance analysis revealing which gaze characteristics most distinguish readers by native language background

## Methodology

| Component | Detail |
|-----------|--------|
| Dataset | MECO-L2 Wave 1 (multilingual L2 reading corpus) |
| Models | Logistic regression (baseline replication) · BERT-based classifier |
| Validation | Monte Carlo simulation — 20 randomised train/validation/test splits |
| Metrics | Precision · Recall · F1-score · Accuracy |
| Features | Gaze-derived reading features (fixation count/duration, regression rate, saccade length) |
| Conditions | Full nationality set · Targeted nationality subset |

## Native Language Identification from Reading (NLIR)

NLIR exploits the well-established finding that a reader's first language shapes how they process text in a second language — including where they fixate, how often they regress, and how long they dwell on words. Eye-tracking provides a non-intrusive window into these processes, enabling automatic identification of readers' linguistic backgrounds from gaze alone — with potential applications in personalised reading support, adaptive language learning, and forensic linguistics.

## Research Context

Part of the **"Reading the Reader" (RtR)** project at DTU Compute, Cognitive Systems Section, funded by the Novo Nordisk Foundation. This paper extends the project's scope beyond typography to examine how individual linguistic and cognitive characteristics encoded in gaze can be decoded through machine learning.

## Venue

Presented at the **IEEE 7th International Conference on Cybernetics, Cognition and Machine Learning Applications (ICCCMLA 2025)**, 1–2 November 2025. To be published by IEEE. (Accepted/In press as of early 2026.)

## Files

- [Accepted Manuscript (Open Access PDF)](https://orbit.dtu.dk/files/420980447/2025353639.pdf)
- [DTU Orbit](https://orbit.dtu.dk/en/publications/native-language-identification-from-gaze-logistic-regression-vs-b/)
