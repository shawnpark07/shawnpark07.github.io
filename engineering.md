---
layout: page
title: Engineering
---

> "Engineering is the closest thing to magic that exists in the world" / Elon Musk


## (2021.03 ~ 2023.03) 3D Multi-Person Pose Estimation from Monocular Videos in the Wild

Focusing on the potential practical value of AI models, I have elaborated on 3D Pose Estimation from Monocular Videos during my M.S. 3D pose estimation is an invaluable task in computer vision with various practical applications. Especially, 3D pose estimation for multi-person from a monocular video (3DMPPE) is particularly challenging and is still largely uncharted, far from applying to in-the-wild scenarios yet. I pose three unresolved issues with the existing methods: lack of robustness on unseen views during training, vulnerability to occlusion, and severe jittering in the output. As a remedy, we propose POTR-3D, the first realization of a sequence-to-sequence 2D-to-3D lifting model for 3DMPPE, powered by a novel geometry-aware data augmentation strategy, capable of generating unbounded data with a variety of views while caring about the ground plane and occlusions. Through extensive experiments, we verify that the proposed model and data augmentation robustly generalizes to diverse unseen views, robustly recovers the poses against heavy occlusions, and reliably generates more natural and smoother outputs. The effectiveness of our approach is verified not only by achieving the state-of-the-art performance on public benchmarks, but also by qualitative results on more challenging in-the-wild videos.



## (2018.03 ~ 2018.06) E-Scooter (w 3-Phase BLDC Motor) Manufacturing Project

This project was carried out during my internship at the research laboratory (EEPEL) of Professor Seung-Ki Sul, a guru with his research on motors.

The motor used in the electric scooter is a Brushless DC (BLDC) motor. Compared to a typical DC motor, it is more environmentally friendly as it does not generate dust due to friction during operation. Since motors account for approximately 50% of global electricity consumption, replacing DC motors with BLDC motors can have a significant positive impact on the environment.

The BLDC motor is driven by a 3-phase AC signal. By converting the DC battery signal into a 3-phase AC signal and inputting it into the motor, a magnetic field that rotates at the desired speed can be generated within the motor. The rotation axis, which is connected to the wheel and made of permanent magnets, rotates in response to this magnetic field.

The stable driving speed was approximately 15km/h.

<p float="left" align="middle">
  <img src="/assets/escooter.jpg" width="350" height="200" hspace="20"/>
  <img src="/assets/escooter_team.jpg" width="350" height="200"/>
</p>
<p float="left" align="center">
  Final Product / Our Team
</p>
