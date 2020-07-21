The quest for measuring myelin with MRI – An interactive meta-analysis
=========================================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matteomancini/myelin-meta-analysis/master?filepath=meta-analysis.ipynb)

<br>

This repository contains the Jupyter Notebook to generate the interactive figures and the meta-analysis results for our study "The quest for measuring myelin with MRI – An interactive meta-analysis of quantitative comparisons with histology".
[The full preprint is available on bioRxiv.](https://www.biorxiv.org/content/10.1101/2020.07.13.200972v2)


<br>

## Execute the notebook locally

The required packages can be installed using pip:

```
pip install -r requirements.txt
```

To generate the final HTML file from the Jupyter Notebook:


```
jupyter nbconvert meta-analysis.ipynb --no-input
```

---
**Note:**

R and the metafor package are both needed to fit the mixed-effect model in `meta-analysis.ipynb` through the package rpy2. Alternatively, you can use the conda environment described in `environment.yml`.

---

