---
title: "Mood-TBI: Rehabilitation of Traumatic Brain Injured Patients — Patient Mood Analysis from Multimodal Video"
collection: publications
permalink: /publication/2018-06-Mood-TBI
excerpt: 'Multimodal video analysis combining facial expressions and body posture for mood monitoring of TBI patients during rehabilitation activities.'
date: 2018-06-01
venue: '25th IEEE International Conference on Image Processing (ICIP 2018) Workshop'
paperurl: 'https://vbn.aau.dk/en/publications/rehabilitation-of-traumatic-brain-injured-patients-patient-mood-a/'
citation: 'Ilyas, C.M.A., Nasrollahi, K., Rehm, M. and Moeslund, T.B. (2018). &quot;Rehabilitation of Traumatic Brain Injured Patients: Patient Mood Analysis from Multimodal Video.&quot; <i>25th IEEE International Conference on Image Processing (ICIP 2018)</i>, IEEE Signal Processing Society, IEEE Xplore.'
---

<center><img src='/images/publications/Mood-TBI.png'></center>

## Abstract

Monitoring the emotional and affective state of Traumatic Brain Injured (TBI) patients during rehabilitation is critical for personalising therapeutic interventions and tracking recovery progress. However, TBI patients exhibit highly atypical expressive behaviour — including facial paralysis, limited voluntary muscle control, and reduced body mobility — making standard unimodal emotion recognition systems unreliable in this clinical context.

This paper presents a **multimodal video-based mood analysis system** that fuses information from both facial expressions and upper-body movements to produce robust affective state estimates for TBI patients. By combining complementary cues from face and body channels, the system achieves more stable performance across the diverse symptom presentations seen in TBI populations.

The approach is validated on a dataset collected from a neurological rehabilitation centre, covering multiple rehabilitation activity types. Results demonstrate that multimodal fusion substantially outperforms unimodal facial or body-only analysis for this challenging population.

## Key Contributions

- Multimodal fusion of facial expression and upper-body movement cues for TBI mood analysis
- Evaluation in ecologically valid clinical rehabilitation settings
- Demonstrated benefit of cross-modal fusion over unimodal analysis for impaired populations
- Contribution to the evidence base for affect-aware assistive and robotic rehabilitation systems

## Methodology

The system pipeline includes:
1. **Facial Region Processing** — detection, alignment, and spatial feature extraction under constrained expressivity
2. **Upper Body Pose Estimation** — skeletal joint tracking to infer body posture and gesture states
3. **Feature-Level Fusion** — late fusion of face and body representations using learned combination weights
4. **Temporal Smoothing** — sequence-level inference for stable mood labels across rehabilitation sessions

## Venue

Presented at the **IEEE Signal Processing Society workshop** in conjunction with the 25th IEEE International Conference on Image Processing (ICIP 2018), Athens, Greece.

## Files

- [VBN AAU Research Portal](https://vbn.aau.dk/en/publications/rehabilitation-of-traumatic-brain-injured-patients-patient-mood-a/)
