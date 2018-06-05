---
layout: post
title:  "Tripal Analysis Expression"
img: analysis_expression_heatmap.png
github: https://github.com/tripal/tripal_analysis_expression
zenodo_badge: https://zenodo.org/badge/DOI/10.5281/zenodo.1115662.svg
zenodo_url: https://doi.org/10.5281/zenodo.1115662
---

Tripal Analysis Expression lets you load in biomaterials and expression data into Chado.  It provides heatmap and bar plot visualizations.

Analysis Expression is a huge module that we've split into three submodules:

#### Tripal Biomaterial
* Load in NCBI Biosamples in XML format.
* Full support for ontologies in Biosample properties.

#### Tripal Analysis Expression
* Load in NGS or microarray expression data!
* Generates heatmaps for list of features with plot.ly.
* Display D3.js expression graphs on feature pages.


#### Tripal Protocol
* Deals with the Protocol, Assay, Arraydesign MAGE tables.
* Needs collaborators!
