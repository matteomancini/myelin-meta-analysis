An interactive meta-analysis of MRI biomarkers of myelin
==============================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matteomancini/myelin-meta-analysis/master?filepath=meta-analysis.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matteomancini/myelin-meta-analysis/blob/master/meta-analysis.ipynb)

<br>

This repository contains the Jupyter Notebook to generate the interactive figures and the meta-analysis results for our study "An interactive meta-analysis of MRI biomarkers of myelin"<sup>*</sup>.
[The full preprint is available on bioRxiv.](https://www.biorxiv.org/content/10.1101/2020.07.13.200972v4)

<sup>*</sup> It was previously entitled "The quest for measuring myelin with MRI – An interactive meta-analysis of quantitative comparisons with histology"."

<br>

## Execute the notebook locally

Python (3.7), Jupyter, R (3.6) and the R packages [metafor](http://www.metafor-project.org) and multcomp are required to run the notebook. The mixed-effect model is fitted using metafor through the package [rpy2](https://rpy2.github.io).

The required Python packages can be installed using pip:

```
pip install -r requirements.txt
```

To generate the final HTML file from the Jupyter Notebook:


```
jupyter nbconvert meta-analysis.ipynb --no-input
```

---
**Note:**

The very first code cell needs to be run on Google Colab in order to retrieve the necessary packages and files.

---

