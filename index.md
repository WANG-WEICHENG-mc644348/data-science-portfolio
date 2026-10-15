---
layout: default
title: WANG Weicheng — Data Science Portfolio
---

# WANG Weicheng

**MSc in Data Science · University of Macau**

I work at the intersection of **computational social science** and **public
governance**, turning large social surveys into evidence that speaks to real
policy questions. My current focus is how digitalisation reshapes public
trust in institutions — using national survey data, transparent measurement
harmonisation, and reproducible Python analysis.

📧 Contact: via the University of Macau

---

## Technical skills

| Area | Tools & methods |
|---|---|
| **Languages** | Python, R, Stata, SQL |
| **Data analysis** | pandas, NumPy, statsmodels, scikit-learn |
| **Econometrics** | linear probability models, weighted estimation, clustered standard errors, regression with interaction terms |
| **Visualisation** | matplotlib, seaborn, geographic maps (provincial choropleths) |
| **Survey methods** | measurement harmonisation across waves, survey weighting, missing-data handling |
| **Text & policy data** | keyword-based corpus construction, bibliometric-style counts |
| **Workflow** | Git / GitHub, reproducible scripts, Jupyter |

---

## Project showcase

### Did Digital Media Erode Trust in China's Courts?

**Research question:** Does the spread of digital media erode public trust in
the judiciary? A two-wave study using the China General Social Survey
(CGSS 2017 and 2023).

![Judicial trust by birth cohort, 2017 vs 2023](https://raw.githubusercontent.com/WANG-WEICHENG-mc644348/data-science-project/main/figures/fig1_cohort_trust_en.png)

**What the figure shows.** Trust in the judiciary rose broadly between 2017
and 2023 — from 61.9% to 83.1% (+21 percentage points). The gain was largest
among the **1980s cohort**, which moved from the least-trusting group
(55.4%) to 85.1%, a **+29.7 point** increase. In other words, the generational
gap in judicial trust converged rather than widened: the rise was shared, not
polarised. Perceived **fairness** — a subjective, procedural judgment — turned
out to be the single strongest predictor of trust, while provincial digital
government spending showed no significant association with it.

📁 **Project repository:** [github.com/WANG-WEICHENG-mc644348/data-science-project](https://github.com/WANG-WEICHENG-mc644348/data-science-project)

**Status:** 🟡 **Ongoing** — being prepared for a public-governance data
analysis competition and a computational-sociology conference.

*Methods: pooled LPM with within-year normalised survey weights and
prefecture-city clustered standard errors; transparent multi-outcome
harmonisation of a question whose scale changed between waves.*

---

## What's next

- Extend the analysis with a **third wave** once a comparable survey is
  released, to move from two-point comparison toward trend estimation
- Add **Bayesian multilevel models** to handle the limited province coverage
- Build an interactive version of the province map on this site

---

<small>All analyses are reproducible from the linked repository. The CGSS
microdata is not redistributed — see the project README for access terms.</small>
