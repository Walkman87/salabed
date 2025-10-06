---
title: AI in CMR
summary: AI pipeline to improve efficiency of cardiac MRI reporting workflow
tags:
  - AI in CMR
date: '2025-09-26T00:00:00Z'


image:
  filename: "ai_cmr.png"
  caption: Autoreporting for cardiac MRI scans
  anchor: Smart
  quality: 100
  resampleFilter: lanczos
  srcset: 2000
draft: false

---

This project  aims to improve the efficiency of cardiac MRI (CMR) reporting workflow by combining the output of several AI processes in one pipeline. This includes AI image post-processing (Sonic DL), segmentation of all CMR series ([SHAIPS](/project/shaips)),  draft report creation based on automated measurements ([HeartTalk](/project/hearttalk)) and generating patient friendly summaries of the verified report ([MIRACLE](/project/miracle)).

The pipeline aims to half the time radiologists spend on analysing and reporting CMR scans from an average of 120 minutes to 60 minutes. This pipeline is in development and currently Sonic DL, SHAIPS and HeartTalk are integrated into the pipeline with MIRACLE being integrated in the future.