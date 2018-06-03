Hello!  I create Tripal modules for use on [Hardwood Genomics](hardwoodgenomics.org) as a member of the Staton laboratory.  This site is to showcase what I've made, and give **you**, a fellow Tripal site maintainer, a place to see my work in one place.


I'd really love to collaborate.  Most of these modules were developed in partnership with Abdullah Almsaeed who is a blast to work with.  Interested in using one of my modules, but need an extra feature?  Reach out, here or on the project repo!

>![tripal cards](/tripal_cards.jpg)
> Some of our production ready Tripal modules. 

# Modules I maintain

## Developer Tools

### [Tripal Devseed](https://github.com/statonlab/tripal_dev_mini_dataset)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1252453.svg)](https://doi.org/10.5281/zenodo.1252453)


* Miniature dataset to load all supported Chado data.
* Detailed, step-by-step guide for loading in Tripal 3.
* SQL dump to quickly boot a dev site with data.

### [Tripal Test Suite](https://github.com/statonlab/TripalTestSuite)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1257164.svg)](https://doi.org/10.5281/zenodo.1257164)

* One command to add PHPunit with access to your Drupal site, and Travis-CI setup.
* Helper methods, such as **factories** to generate test Chado data.

### [Tripal Fields Generator](https://github.com/statonlab/fields_generator)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1200662.svg)](https://doi.org/10.5281/zenodo.1200662)

* Specify a CVterm, and this tool creates the Field class, formatter, widget, and `fields.info` stub code for it!
* Connects to your DB to verify term information.

### [TripalDock](https://github.com/statonlab/tripaldock)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1187125.svg)](https://doi.org/10.5281/zenodo.1187125)

* Wraps a Docker container running Tripal.  
* Ideal for getting new developers up and running quickly.

## Biological Data

### [Tripal Analysis Expression](https://github.com/tripal/tripal_analysis_expression)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1115662.svg)](https://doi.org/10.5281/zenodo.1115662)


This is a huge module that we've split into three submodules:

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

### [Tripal CV-Xray](https://github.com/statonlab/tripal_cv_xray)

* Map entities onto Ontologies.
* For example, create per-organism browsable GO-term trees with links to genes annotated with those GO terms.

### [Tripal SSR](https://github.com/statonlab/tripal_ssr)

* Load in primer information for amplifying predicted simple sequence repeats (SSRs).

### [Tripal Ortholog](https://github.com/statonlab/tripal_ortholog)

* Not released, on hiatus.
* Load and display gene ortholog information.

### [Tripal Elasticsearch](https://github.com/tripal/tripal_elasticsearch/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1222187.svg)](https://doi.org/10.5281/zenodo.1222187)


* Manage your elasticsearch instance.
* Provides indexes for nodes, entities, and features. 
* Easily create Chado table specific indexes.
* Cross-site search!

### [Tripal Manage Analyses](https://github.com/statonlab/tripal_manage_analyses)
* Custom fields for entity lists: analyses, organisms, libraries...

### [Tripal cmap field and loader](https://github.com/statonlab/tripal_cmap_loader)
* Under development.
* Load and view genetic map data.


## Site Admin

### [Tripal Alchemist](https://github.com/statonlab/tripal_alchemist)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1187120.svg)](https://doi.org/10.5281/zenodo.1187120)

* Convert Tripal Entities from one bundle to another.
* Used at HWG to change feature types, or to convert analyses to sub-types with specialized fields.
* Supports **collections** to easily convert entities.

### [Tripal Curator](https://github.com/statonlab/tripal_curator)

* Curation toolbox for Chado properties.
* Batch alter Chado properties cvterms from local terms to ontological terms.
* Chado 1.4 will suport cvterms for property **values**.  Curator lets you convert **text values** to **Cvterm values**.
* reports on property ontology usage by Chado table.

# Modules I contribute to
* Tripal
* Tripal Blast
* Tripal Analaysis KEGG
* Tripal Analysis GO