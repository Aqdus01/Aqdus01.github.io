---
title: "Pepper-FER: Teaching Pepper Robot to Recognize Emotions of Traumatic Brain Injured Patients Using Deep Neural Networks"
collection: publications
permalink: /publication/2019-10-Pepper-FER
excerpt: 'End-to-end pipeline deploying a CNN-LSTM emotion recognition model on the Pepper social robot for affect-aware interaction with TBI patients during rehabilitation.'
date: 2019-10-01
venue: 'IEEE International Conference on Robot and Human Interactive Communication (RO-MAN 2019)'
paperurl: 'https://doi.org/10.1109/RO-MAN46459.2019'
citation: 'Ilyas, C.M.A., Haque, M.A., Nasrollahi, K., Rehm, M. and Moeslund, T.B. (2019). &quot;Teaching Pepper Robot to Recognize Emotions of Traumatic Brain Injured Patients Using Deep Neural Networks.&quot; <i>IEEE RO-MAN 2019</i>, IEEE.'
---

<center><img src='/images/publications/Pepper-FER.png'></center>

## Abstract

Social robots have significant potential as assistive tools in the rehabilitation of Traumatic Brain Injured (TBI) patients, particularly for facilitating emotion-aware interactions during physiotherapy and cognitive exercises. This paper presents an end-to-end pipeline for **deploying deep neural network-based facial expression recognition directly on the Pepper social robot**, enabling real-time, affect-aware engagement with TBI patients.

The pipeline extends the CNN-LSTM architecture developed in prior work — achieving 87.97% accuracy on the challenging TBI database — and integrates it with Pepper's perception stack. A direct comparison is performed against Pepper's built-in FER module to quantify the improvement in recognition accuracy when using a domain-adapted model trained specifically on TBI patients versus a general-purpose commercial solution.

Results demonstrate that the domain-specific CNN-LSTM substantially outperforms the robot's native FER system on TBI patients, highlighting the importance of population-specific training data and architecture choices in clinical Human-Robot Interaction scenarios.

## Key Contributions

- Full deployment of a deep emotion recognition pipeline on the Pepper robot platform
- First systematic comparison of a custom TBI-adapted FER model against Pepper's built-in commercial emotion recognition module
- Demonstrates concrete accuracy improvements from domain-specific training on TBI patients
- Provides a reproducible framework for affect-aware social robotics in neurorehabilitation

## System Architecture

```
RGB Camera (Pepper) → Face Detection → CNN Feature Extraction
                                              ↓
                                     LSTM Temporal Modelling
                                              ↓
                               Emotion Label → Robot Behaviour Adaptation
```

The robot's response layer uses recognised emotion labels to adapt verbal and gestural outputs, supporting therapist-guided interactions.

## Venue

Presented at the **28th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN 2019)**, New Delhi, India.

## Files

- [ResearchGate](https://www.researchgate.net/publication/338588588_Teaching_Pepper_Robot_to_Recognize_Emotions_of_Traumatic_Brain_Injured_Patients_Using_Deep_Neural_Networks)
- [VBN Research Portal](https://vbn.aau.dk/en/publications/teaching-pepper-robot-to-recognize-emotions-of-traumatic-brain-in/)
