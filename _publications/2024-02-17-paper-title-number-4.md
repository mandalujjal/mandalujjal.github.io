---
title: "On the Born series methods for solving inhomogeneous Helmholtz equation in biomedical photoacoustics"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'This paper is about fixing template issue #693.'
date: 2023-06-25
venue: 'Optica Publishing Group'
paperurl: 'https://opg.optica.org/abstract.cfm?uri=ecbo-2023-126310W'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The Born series methods, namely, traditional Born series (TBS) and convergent Born series (CBS), have been recently implemented to numerically solve the time-independent photoacoustic (PA) wave equation for an acoustically inhomogeneous source. The TBS algorithm diverges when the sound-speed mismatch is> 20%, however, the CBS technique provides faithful result even beyond this limit. These protocols are iterative in nature and computationally expensive. Currently, MATLAB-based implementations are available to study PA emission from a single source mimicking a cell. However, efficient numerical implementation strategy is further needed particularly to calculate PA field from a tissue. Therefore, to develop insights, uniprocessor-based C codes were realized for these schemes. The PA field (in 2D) was computed at a distance 35 µm from a source (a light absorbing disc of radius 7.5 µm) over a …



<img width="1251" height="945" alt="c2" src="https://github.com/user-attachments/assets/6a02e48b-103c-4d4e-b71c-8f32e4388994" />
