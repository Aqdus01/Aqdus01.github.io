---
title: "WorkAffect: Inferring User Facial Affect in Work-like Settings"
collection: publications
permalink: /publication/2021-11-WorkAffect
excerpt: 'Dimensional affect modelling (valence/arousal) from facial cues in naturalistic work-like settings, developed within the EU Horizon 2020 WorkingAge project.'
date: 2021-11-22
venue: 'arXiv preprint (WorkingAge / EU Horizon 2020 Project)'
paperurl: 'https://arxiv.org/abs/2111.11862'
citation: 'Ilyas, C.M.A. et al. (2021). &quot;Inferring User Facial Affect in Work-like Settings.&quot; <i>arXiv preprint arXiv:2111.11862</i>.'
---

<center><img src='/images/publications/WorkAffect.png'></center>

## Abstract

Recognising and modelling the emotional state of workers in professional environments has direct implications for occupational health, ergonomics, and the design of affect-aware adaptive systems. Unlike categorical emotion classification (happiness, sadness, fear, anger, disgust, surprise), **dimensional affect modelling** in terms of *valence* (positivity–negativity) and *arousal* (intensity–calmness) has proven more flexible, applicable, and practically useful for naturalistic, real-world settings.

This paper presents a system for **inferring user facial affect in work-like settings**, developed as part of the EU Horizon 2020 **WorkingAge** project, which aims to promote healthy working habits and improve the wellbeing of workers across diverse occupational contexts. The proposed approach captures continuous valence and arousal dimensions from facial cues observed during realistic work-like activities, moving beyond acted or laboratory-constrained expressions towards in-the-wild affective monitoring.

The system is designed to handle the particular challenges of occupational affect inference: subtle, low-intensity expressions typical of professional settings; variable illumination and camera angles in workspaces; and the need for unobtrusive, non-intrusive sensing compatible with real workplaces.

## Key Contributions

- Dimensional (valence/arousal) affect inference from facial cues in naturalistic work-like scenarios
- Addresses the specific challenges of in-the-wild occupational affective computing
- Developed within the EU Horizon 2020 WorkingAge project framework
- Demonstrates the practical advantages of continuous dimensional modelling over discrete categorical classification for workplace applications

## Research Context: WorkingAge Project

This work was conducted as part of the [WorkingAge](https://www.workingage.eu/) project (EU Horizon 2020, Grant No. 826232), a multi-institutional European research initiative targeting the affective wellbeing of workers. The project develops a suite of sensing and modelling technologies — covering facial affect, physiological signals, and activity recognition — to promote healthier working conditions and support workers across different life stages.

## Dimensional Affect Model

The system operates in the **Russell circumplex model** of affect:

| Dimension | Low | High |
|-----------|-----|------|
| **Valence** | Negative (stress, frustration) | Positive (engagement, satisfaction) |
| **Arousal** | Calm, relaxed | Activated, alert |

Continuous regression in this 2D space allows fine-grained affective state tracking more suited to the subtle dynamics of workplace emotion than discrete category labels.

## Files

- [arXiv Preprint](https://arxiv.org/abs/2111.11862)
- [WorkingAge Project](https://www.workingage.eu/)
