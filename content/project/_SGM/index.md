---
title: Semi-Global Stereo Matching with Monocular Disparity Guess
summary: Enhanced stereo depth estimation using monocular disparity initialization and SGM refinement. Reduced MSE by 75%.
tags:
  - CV
date: 2024-04-01
external_link: 
---

A stereo depth estimation project that combines classical and learning-based approaches: a monocular disparity prediction is used as the initial guess, which Semi-Global Matching (SGM) then refines into the final disparity map. Seeding SGM with the monocular estimate substantially improved accuracy over the baseline, reducing mean squared error by 75%.
