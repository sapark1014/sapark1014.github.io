---
layout: page
title: CROP Fellowship
description: Online Adaptive Radiotherapy Automation (MSCA COFUND at CTU Prague)
img:
importance: 1
category: research
---

**Grant:** CROP Postdoctoral Fellowship (Marie Skłodowska-Curie COFUND Action)  
**Role:** Postdoctoral Fellow  
**Period:** Mar 2026 – Aug 2027  
**Host:** Czech Technical University in Prague, Czech Republic  
**Supervisor:** Dr. Petra Trnková  

### Overview

Radiotherapy for cancer patients can be compromised by anatomical changes during treatment, such as tumor shrinkage or weight changes. Online adaptive radiotherapy (oART) addresses this by updating the treatment plan based on the patient's current anatomy, immediately before dose delivery. However, dedicated adaptive systems are costly and unavailable in most clinics. The majority of hospitals use conventional C-arm LINACs with CBCT imaging capability but lack built-in adaptive workflows, making oART too labor-intensive for routine use.

This project develops and validates a **RayStation-native automation framework** that performs end-to-end oART on conventional C-arm LINACs through a single executable script.
It builds on my expertise in biomedical image processing and computational workflow automation, extending these methods from microscopy imaging to clinical CT data in radiotherapy.

### My Expected Contribution

- Build a **Python-based orchestrator** within RayStation automating the complete oART sequence: CBCT import → registration to planning CT → dose computation → plan optimization → QA verification → plan export
- Conduct **proof-of-concept validation** on retrospective clinical datasets from Czech partner hospitals, benchmarking against manual planning in terms of dose quality, clinical acceptability, and runtime
- Release the developed automation library as **open-source software** with documentation and example datasets
- Collaborate with partner institutions including University Motol University Hospital, Medical University of Vienna, Paul Scherrer Institut (Switzerland)
- Leverage expertise in **biomedical image analysis** to evaluate and optimize key imaging components of the oART pipeline, including CBCT-to-planning CT registration, deep-learning auto-segmentation of organs at risk, and image quality assessment
