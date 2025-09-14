---
title: "NYPD Stop-and-Frisk Analysis Using Body-Worn Camera Data" 
date: 2025-05-20
tags: ["policing","racial disparities","stop and frisk"]
author: ["Annie Chen"]
description: "Court-commissioned study on constitutional compliance and racial disparities in policing."
#summary: "This book discusses Portugese irregular verbs in great details."
cover:
    image: "fmpviz.png"
    alt: "Predicted probabilities of an unconstitutional stop by race"
    relative: true
showToc: false
disableAnchoredHeadings: false

---


## Highlights


- **Data Engineering & Preprocessing**
    - Processed **1.5M+ BWC recordings** into structured encounters using metadata string matching and **hierarchical clustering** to merge multi-officer recordings of the same incident.
- **Sampling & Study Design**
    - Implemented **stratified random sampling** across encounter types (low-level, stops, arrests/summonses).
    - Conducted post-hoc **power analysis** and calculated **minimum detectable effect sizes (MDES)** to gauge statistical precision in subgroup and disparity analyses.
- **Feature Engineering from Unstructured Video**
    - Research assistants trained to apply systematic **content coding protocols** to extract event-level variables (officer actions, civilian engagement, encounter type).
    - Entity resolution of encounters by linking structured video metadata to administrative reports.
- **Ground-Truth Labeling & Reliability**
    - Retired judges coded stop constitutionality under **Fourth Amendment standards**.
    - Used **Cohen’s κ** to measure inter-rater reliability; applied majority-rule consensus for labels.
- **Statistical Modeling & Inference**
    - Fit **logistic regression models** to predict unconstitutional stops based on encounter conditions (e.g., self-initiated vs. call-driven, Neighborhood Safety Team presence).
    - Applied a **doubly robust estimation framework** using **entropy balancing** to adjust for covariate imbalance and strengthen inference.
    - Estimated uncertainty with **robust standard errors** and **95% confidence intervals**.


---
## Tools and Stack


#### Statistical Analysis
<!-- ![Hierarchical Clustering](https://img.shields.io/badge/Hierarchical%20Clustering-228B22?labelColor=#2F81F7) ![Random Forest](https://img.shields.io/badge/Random%20Forest-228B22?labelColor=#3776AB) ![Doubly Robust ML](https://img.shields.io/badge/Random%20Forest-228B22) 

#### Software
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white) -->
<!-- <img alt="Random Forest" src="https://img.shields.io/badge/Random%20Forest-%20?color=1E90FF"> -->

---

## Click here for the [full report.](https://www.nypdmonitor.org/wp-content/uploads/2025/05/2025.05.01-956-ISLG-Report-An-Examination-of-NYPD-Stop-and-Frisk-Practices.pdf)

---


## Citation

Chen, Annie Y., and Kathleen Doherty. 2025. An Examination of NYPD Stop and Frisk Practices: Using Body-Worn Camera Recordings to Determine the Constitutionality and Documentation of Street Stops. CUNY Institute for State and Local Governance. Research. https://www.nypdmonitor.org/wp-content/uploads/2025/05/2025.05.01-956-ISLG-Report-An-Examination-of-NYPD-Stop-and-Frisk-Practices.pdf.

```BibTeX
@techreport{
	type = {Research},
	author = {Chen, Annie Y. and Doherty, Kathleen},
    month = Apr,
	year = {2025},
	title = {An {Examination} of {NYPD} {Stop} and {Frisk} {Practices}: {Using} {Body}-worn {Camera} {Recordings} to {Determine} the {Constitutionality} and {Documentation} of {Street} {Stops}},
	institution = {CUNY Institute for State and Local Governance},
    publisher = {NYPD Monitor},
    url = {Denerstein - encounters that officers categorized as a low-leve.pdf:files/8403/Denerstein - encounters that officers categorized as a low-leve.pdf:application/pdf}}
```
