---
title: "Kaggle Computational Tool"
excerpt: "A computational tool developed as a Kaggle notebook for KNES 381 Assignment."
collection: portfolio
---

## Python Data Analysis: VO2 Kinetics and Gas Exchange

This project was completed as part of KNES 381 and uses Python to analyze VO2 kinetics and gas exchange data collected during exercise testing. From a physiological standpoint, VO2 (oxygen uptake) kinetics describe how the body's aerobic energy system responds to increasing exercise intensity. As workload rises, two key thresholds emerge: the Gas Exchange Threshold (GET), the point at which the body begins to supplement aerobic metabolism with anaerobic pathways, and the Respiratory Compensation Point (RCP), where the respiratory system can no longer buffer the rising acidity in the blood and ventilation increases sharply. These thresholds are fundamental markers used in sport science, clinical exercise testing, and athletic performance assessment.

The notebook was built by modifying a provided Python script to process a new VO2 dataset from scratch. The analysis produces a primary VO2 plot over time, as well as two additional gas exchange plots showing FECO2 versus VO2 and VCO2 versus VO2, both sharing a common x-axis. Beyond the standard plots, the script uses Python logic to automatically detect and annotate the GET and RCP as vertical reference lines, rather than placing them by hand. The emphasis throughout was on reproducible, well-structured scientific code that could be reapplied to any new dataset simply by changing the input file path.

---

<iframe src="https://www.kaggle.com/embed/udhambains/knes-381-assignment?kernelSessionId=308587231" height="800" style="margin: 0 auto; width: 100%; max-width: 950px;" frameborder="0" scrolling="auto" title="KNES 381-Assignment"></iframe>
