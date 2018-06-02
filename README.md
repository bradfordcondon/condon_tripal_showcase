Hello!  I create Tripal modules for use on [Hardwood Genomics](hardwoodgenomics.org).  This site is to showcase what I've made, and give **you**, a fellow Tripal site maintainer, a place to see my work in one place.


I'd really love to collaborate.  Most of these modules were developed in partnership with @Almsaeed who is a blast to work with.  Interested in using one of my modules, but need an extra feature?  Reach out, here or on the project repo!


# Modules I maintain

## Developer Tools

### Tripal Devseed
* Miniature dataset to load all supported Chado data.
* Detailed, step-by-step guide for loading in Tripal 3.
* SQL dump to quickly boot a dev site with data.

### TripalDock

### Tripal Test Suite
* One command to add PHPunit with access to your Drupal site, and Travis-CI setup.
* Helper methods, such as **factories** to generate test Chado data.

### Tripal Fields Generator
* Specify a CVterm, and this tool creates the Field class, formatter, widget, and `fields.info` stub code for it!
* Connects to your DB to verify term information.


## Biological Data

### Tripal Analysis Expression
#### Tripal Biomaterial
#### Tripal Analysis Expression
* Load in NGS or microarray expression data!
* Generates heatmaps for list of features with plot.ly.
* Display D3.js expression graphs on feature pages.


#### Tripal Protocol
* Deals with the Protocol, Assay, Arraydesign MAGE tables.
* Needs collaborators!

### Tripal CV-Xray 
### Tripal SSR
### Tripal Ortholog
### Tripal Elasticsearch
### Tripal Transcriptomes Table
### Tripal Manage Analyses
### Tripal cmap field and loader

## Site Admin
### Tripal Alchemist
* Convert Tripal Entities from one bundle to another.
* Used at HWG to change feature types, or to convert analyses to sub-types with specialized fields.
* Supports **collections** to easily convert entities.

### Tripal Curator

* Curation toolbox for Chado properties.
* Batch alter Chado properties cvterms from local terms to ontological terms.
* Chado 1.4 will suport cvterms for property **values**.  Curator lets you convert **text values** to **Cvterm values**.
* reports on property ontology usage by Chado table.

# Modules I contribute to
### Tripal
### Tripal Blast
### Tripal Analaysis KEGG
### Tripal Analysis GO (?)