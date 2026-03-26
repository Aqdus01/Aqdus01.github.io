---
title: "PhD Thesis: Facial Emotion Recognition for Citizens with Traumatic Brain Injury for Therapeutic Robot Interaction"
collection: publications
permalink: /publication/2021-12-PhD-Thesis
excerpt: 'Doctoral dissertation developing computer vision and deep learning methods for facial affect recognition in TBI patients, enabling affect-aware therapeutic robot interaction.'
date: 2021-12-01
venue: 'Aalborg University Press, Aalborg University, Denmark'
paperurl: 'https://vbn.aau.dk/en/publications/facial-emotion-recognition-for-citizens-with-traumatic-brain-inju/'
citation: 'Ilyas, C.M.A. (2021). <i>Facial Emotion Recognition for Citizens with Traumatic Brain Injury for Therapeutic Robot Interaction</i>. PhD Dissertation, Aalborg University, Denmark. Aalborg Universitetsforlag.'
---

<center><img src='/images/publications/PhD-Thesis.png'></center>

## Abstract

This doctoral dissertation addresses a fundamental challenge in assistive robotics and clinical rehabilitation: how can a robot reliably perceive and respond to the emotional states of citizens with Traumatic Brain Injury (TBI), whose expressive behaviour is profoundly altered by neurological damage?

TBI patients present a uniquely difficult population for affective computing systems. Their facial expressions are constrained by muscle paralysis, reduced voluntary motor control, and asymmetric facial mobility — while their emotional lives remain rich and communicatively important. Standard facial emotion recognition (FER) systems, trained exclusively on healthy subjects, fail systematically when applied to this group, producing unreliable outputs that could cause harm if used to drive robotic therapeutic interactions.

This thesis makes four primary contributions to address this gap:

**1. TBI-Specific Database Construction** — A novel database of facial expressions from TBI residents at a Danish neurological rehabilitation centre, collected across three activity types (cognitive, physiotherapy, social), under ecologically valid, unconstrained conditions, capturing the diversity of expression profiles seen in this population.

**2. CNN-LSTM Architecture for TBI-FER** — A deep spatio-temporal model combining convolutional feature extraction with LSTM-based temporal reasoning, achieving 87.97% accuracy on the TBI database and outperforming general-purpose FER systems when applied to impaired subjects.

**3. Multimodal Imaging Pipeline** — Integration of RGB, depth, and thermal imaging modalities to compensate for the limitations of each individual sensor channel, providing more robust recognition under the challenging conditions of clinical rehabilitation.

**4. Pepper Robot Deployment** — End-to-end integration of the TBI-adapted FER pipeline with the Pepper social robot, enabling real-time, affect-aware interaction with TBI patients and demonstrating concrete performance advantages over the robot's native emotion recognition module.

Together, these contributions lay the groundwork for a new generation of affect-aware therapeutic robots capable of meaningful, sensitive, and personalised interaction with cognitively and physically impaired users.

## Supervision

- **Principal Supervisor:** Associate Professor Matthias Rehm, Human-Robot Interaction Lab, Aalborg University
- **Co-Supervisor:** Professor Kamal Nasrollahi, Visual Analysis and Perception Lab, Aalborg University
- **Co-Supervisor:** Professor Thomas B. Moeslund, Visual Analysis and Perception Lab, Aalborg University

## Research Environment

Conducted jointly within the:
- **Visual Analysis & Perception (VAP) Laboratory**, Aalborg University
- **Human-Robot Interaction (HRI) Laboratory**, Aalborg University

## Thesis Structure

| Chapter | Content |
|---------|---------|
| 1 | Introduction and Motivation |
| 2 | Background: TBI, Rehabilitation Robotics, and FER |
| 3 | TBI-FER Database Collection and Annotation |
| 4 | CNN-LSTM Architecture for Spatio-Temporal FER |
| 5 | Multimodal Imaging for Robust TBI-FER |
| 6 | Robot Deployment: Pepper and Real-Time Inference |
| 7 | Discussion and Future Directions |

## Files

- [Full Thesis (VBN AAU)](https://vbn.aau.dk/en/publications/facial-emotion-recognition-for-citizens-with-traumatic-brain-inju/)
- [Aalborg University Press](https://aaudigi.dk/)
