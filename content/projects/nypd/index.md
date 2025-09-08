---
title: "NYPD Stop-and-Frisk Analysis Using Body-Worn Camera Data" 
date: 2025-05-20
tags: ["policing","irregular verbs","philology"]
author: ["Annie Chen"]
description: "Court-commissioned study on constitutional compliance and racial disparities in policing."
#summary: "This book discusses Portugese irregular verbs in great details."
cover:
    image: "fmpviz.png"
    alt: "Predicted probabilities of an unconstitutional stop by race"
    relative: true
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Regensburg University Press"
showToc: false
disableAnchoredHeadings: false

---


#### Highlights


- **Data Engineering & Preprocessing**
    - Processed **1.5M+ BWC recordings** into structured encounters using metadata string matching and **hierarchical clustering** to merge multi-officer recordings of the same incident.
- **Sampling & Study Design**
    - Implemented **stratified random sampling** across encounter types (low-level, stops, arrests/summonses).
    - Conducted post-hoc **power analysis** and calculated **minimum detectable effect sizes (MDES)** to gauge statistical precision in subgroup and disparity analyses.
- **Feature Engineering from Unstructured Video**
    - Research assistants trained to apply systematic **content coding protocols** to extract event-level variables (officer actions, civilian engagement, encounter type).
    - Linked structured video metadata to administrative stop reports.
- **Ground-Truth Labeling & Reliability**
    - Retired judges coded stop constitutionality under **Fourth Amendment standards**.
    - Used **Cohen’s κ** to measure inter-rater reliability; applied majority-rule consensus for labels.
- **Statistical Modeling & Inference**
    - Fit **logistic regression models** to predict unconstitutional stops based on encounter conditions (e.g., self-initiated vs. call-driven, Neighborhood Safety Team presence).
    - Applied a **doubly robust estimation framework** using **entropy balancing** to adjust for covariate imbalance and strengthen inference.
    - Estimated uncertainty with **robust standard errors** and **95% confidence intervals**.


---
#### Stack



---

#### Full report here.

+ [Chapter 1: History of the Portuguese language](chapter1.pdf)
+ [Chapter 2: Review of regular verbs](chapter2.pdf)
+ [Chapter 3: Analysis of irregular verbs](chapter3.pdf)

---


#### Citation

Moritz-Maria von Igelfeld. 1997. *Portugese Irregular Verbs*. Regensburg, Germany: Regensburg University Press. http://www.alexandermccallsmith.com/book/portuguese-irregular-verbs.

```BibTeX
@book{I97,
author = {Moritz-Maria von Igelfeld},
year = {1997},
title = {Portugese Irregular Verbs},
publisher = {Regensburg University Press},
address = {Regensburg, Germany},
url = {http://www.alexandermccallsmith.com/book/portuguese-irregular-verbs}}
```