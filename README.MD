# Zhang\_et\_al\_2025

**Code & analysis notebooks for Zhang *****et al.*****, 2025**

---

## Overview

This repository contains the analysis pipelines used in the Zhang *et al.* 2025 study investigating how internal state (hunger, satiation, threat, safety) shapes population‑level neural dynamics in prelimbic cortex and behavior in rats.
The code is organised as a set of Jupyter notebooks that:

* quantify cue‑evoked responses across states
* train **CEBRA** behaviour‑based embeddings
* perform spectral clustering analyses
* generate figure panel included in the paper.

All workflows run in pure Python.

---

## Repository structure

| Path                   | Purpose                                                                                                  |
| ---------------------- | -------------------------------------------------------------------------------------------------------- |
| `Behavior/`            | Ethogram construction, behavioural metrics, and statistical analysis notebooks. Related to Fig. 1 and Extended Data Fig. 1.                          |
| `CEBRA/`               | Training & visualisation of CEBRA embeddings. Related to Fig. 2 and Extended Data Fig. 3. |
| `Cue responses/`       | State‑specific cue response quantification and decoding analyses. Related to Fig. 3 and Extended Data Fig. 4-5.         |
| `Spectral Clustering/` | Unsupervised clustering of calcium imaging and single‑unit peri‑event activity. Related to Fig. 4-5 and Extended Data Fig. 6-10.                   |
| `Cross_regist/`        | Cross‑session cell‑identity registration and footprint visualisation. Related to Fig. 4.                                   |


## Dependencies

- CEBRA notebooks – see https://cebra.ai for up‑to‑date environment requirements.

- Other notebooks – tested with python==3.11 and scikit‑learn==1.2.2.

---

*Last updated: 2 July 2025.*

