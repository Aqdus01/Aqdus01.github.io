---
title: "BodyEmotion: Deep Emotion Recognition through Upper Body Movements and Facial Expression"
collection: publications
permalink: /publication/2021-02-BodyEmotion
excerpt: 'A deep CNN model that learns a joint embedding of upper body movements and facial expressions for robust emotion recognition, enabling gesture-level affect inference from facial features alone.'
date: 2021-02-08
venue: '16th International Conference on Computer Vision Theory and Applications (VISAPP 2021), SciTePress'
paperurl: 'https://doi.org/10.5220/0010359506690679'
citation: 'Ilyas, C.M.A., Viana Nunes, A.R., Nasrollahi, K., Rehm, M. and Moeslund, T.B. (2021). &quot;Deep Emotion Recognition through Upper Body Movements and Facial Expression.&quot; In <i>VISAPP 2021</i>, SciTePress, pp. 669–679.'
---

<center><img src='/images/publications/BodyEmotion.png'></center>

## Abstract

Human emotion recognition in Human-Robot Interaction (HRI) contexts must contend with significant variability in how emotion is expressed — through facial configuration, body posture, and gesture. While facial expression has long been the dominant modality, upper body movements provide complementary and often more reliable affective cues, particularly for users with restricted facial expressivity.

This paper presents a **deep convolutional neural network that learns a correspondence between upper body movements and facial expressions**, enabling emotion and gesture recognition from either modality independently once this cross-modal mapping is established. The model is trained on benchmark datasets exhibiting diverse emotion categories and corresponding body movement patterns. Once the mapping is learned, the system can infer body-level emotional context from facial features alone — a property of practical value in scenarios where full-body capture is unavailable.

Experiments on standard benchmark datasets demonstrate that the joint body-face model achieves competitive emotion recognition performance while providing additional gesture-level inference capability not available in face-only systems.

## Key Contributions

- Cross-modal deep architecture learning correspondences between facial expressions and upper body movement patterns
- Enables emotion recognition from facial features that generalises to body-level gesture states
- Evaluated on established benchmark datasets across multiple emotion categories
- Directly relevant to HRI scenarios where full-body tracking is unreliable or unavailable

## Architecture

The model is structured as a **two-stream deep CNN**:
- **Facial Stream** — spatial CNN processing normalised face regions
- **Body Movement Stream** — temporal CNN over optical flow or pose sequences capturing upper-body dynamics
- **Cross-Modal Embedding Layer** — shared representation space learning facial–body correspondences
- **Emotion Classifier** — joint softmax head over fused representations

At inference, only the facial stream is required, with the body stream providing supervision during training through the shared embedding.

## Venue

Presented at the **16th International Conference on Computer Vision Theory and Applications (VISAPP 2021)**, part of VISIGRAPP, Online conference, February 8–10, 2021.

## Files

- [Paper (DOI)](https://doi.org/10.5220/0010359506690679)
- [VBN Research Portal](https://vbn.aau.dk/en/publications/deep-emotion-recognition-through-upper-body-movements-and-facial-/)
