---
title: "CtxRead: Context Preservation Through Eye Tracking — Adaptive Reading Application Design for an Optimal Reading Experience"
collection: publications
permalink: /publication/2025-05-CtxRead
excerpt: 'Eye-tracking study evaluating four context-preservation intervention designs (Popup, Undo, Notification, Gradual) in an adaptive reading application, showing the Gradual intervention minimises reading-resume time and is most preferred by readers.'
date: 2025-05-26
venue: '2025 Symposium on Eye Tracking Research and Applications (ETRA 2025), ACM'
paperurl: 'https://doi.org/10.1145/3715669.3725897'
citation: 'Jensen, H.E., Ilyas, C.M.A., Tashk, A., Cooreman, B., Beier, S. and Bækgaard, P. (2025). &quot;Context Preservation Through Eye Tracking: Adaptive Reading Application Design for an Optimal Reading Experience.&quot; In <i>Proceedings of ETRA 2025</i>, Article 78. Association for Computing Machinery. https://doi.org/10.1145/3715669.3725897'
---

<center><img src='/images/publications/CtxRead.png'></center>

## Abstract

Adaptive reading interfaces offer real-time typographical adjustments to optimise reading comfort and performance — but such adjustments inevitably disrupt the reading flow, forcing readers to search for where they were in the text. This paper introduces **context preservation**: a mechanism that uses eye-tracking to help readers resume reading rapidly after a typographic intervention is applied.

The reading application implements four distinct intervention designs — **Popup, Undo, Notification, and Gradual** — each representing a different strategy for re-establishing reading context after a typographical adjustment. A within-subjects experiment with **22 participants** evaluated all four designs, measuring **Reading-Resume Time (RRT)** as the primary outcome alongside subjective preference ratings.

Results show **significant differences in RRT between intervention types**. The **Gradual intervention** — which transitions smoothly from the old to the new typography while preserving visual context — is both the fastest and the most preferred design among participants, providing actionable design guidance for adaptive reading systems.

## Key Contributions

- Introduces the concept of **context preservation** as a design principle for adaptive reading interfaces
- Proposes and evaluates four concrete intervention designs varying in how reading context is maintained during typographic adjustments
- Empirical evidence from a 22-participant within-subjects eye-tracking experiment
- Identifies the **Gradual intervention** as the optimal design for minimising reading-resume time
- Provides design recommendations for adaptive reading applications using real-time eye-tracking feedback
- Open dataset available via DTU Data Repository

## Experimental Design

| Component | Detail |
|-----------|--------|
| Participants | 22 readers, within-subjects |
| Eye-tracker | Tobii (gaze tracking for context preservation) |
| Intervention conditions | Popup · Undo · Notification · Gradual |
| Primary measure | Reading-Resume Time (RRT) |
| Secondary measure | Participant preference ratings |
| Analysis | Within-subjects comparison across all four intervention types |

## Intervention Designs

- **Popup** — A visual overlay highlights the last read position before the typographic change
- **Undo** — An undo button allows the reader to revert the typographic adjustment and re-find their place
- **Notification** — A notification badge signals that a change occurred without disrupting the page
- **Gradual** — Typography transitions incrementally, maintaining visual continuity of the reading position

The Gradual design achieved the lowest RRT and highest participant satisfaction, suggesting that preserving spatial-visual coherence during typographic transitions is key to minimising reading disruption.

## Research Context

Part of the **"Reading the Reader" (RtR)** project, funded by the Novo Nordisk Foundation, at DTU Compute Cognitive Systems Section. This paper directly addresses the UX and interface design dimension of the project, translating eye-tracking insights into actionable adaptive reading application design.

## Venue

Presented at the **2025 Symposium on Eye Tracking Research and Applications (ETRA '25)**, Tokyo, Japan, 26–29 May 2025. Published open access by the Association for Computing Machinery (ACM). Licence: CC BY 4.0.

## Files

- [Paper (ACM DOI)](https://doi.org/10.1145/3715669.3725897)
- [Full Text PDF (Open Access)](https://orbit.dtu.dk/files/406853513/3715669.3725897.pdf)
- [Dataset (DTU Data)](https://doi.org/10.11583/DTU.28683917.v1)
- [DTU Orbit](https://orbit.dtu.dk/en/publications/context-preservation-through-eye-tracking-adaptive-reading-applic/)
