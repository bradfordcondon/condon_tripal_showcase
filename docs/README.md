Hello!   This is the code repository for the [Tripal modules showcase site](https://statonlab.github.io/hardwoods_tripal_showcase/)!  This site showcases Tripal modules developed by the Staton laboratory and in use at [Hardwood Genomics](hardwoodgenomics.org).  Our hope is that you'll consider trying out our modules and collaborating with us!


### Setting up your own site

You can use this repo as a template for your own show case site!

* Clone the repository
* Post modules in the `_posts` folder.  See below for format.
* Change variables in `_config.yml`.  In particular set the URL and base URL to your github pages location.
* install [jekyll](https://jekyllrb.com/docs/installation/).
* run `jekyll serve` to test your site.
* build with `jekyll serve`, and push to your repository.
* Configure [github pages](https://pages.github.com/)  for your repo.  This site builds to `docs/`, so check that option (or reconfigure the build process).


### post format
The below file is an example post.

```
---
layout: post
title:  "TripalDock"
img: docker_logo.png
github: https://github.com/statonlab/tripaldock
zenodo_badge: https://zenodo.org/badge/DOI/10.5281/zenodo.1187125.svg
zenodo_url: https://doi.org/10.5281/zenodo.1187125
---

* Wraps a Docker container running Tripal.  
* Ideal for getting new developers up and running quickly.

```

