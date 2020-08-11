---
layout: default
title: Provide citation language
---

### Provide clear acknowledgement instructions for your software citation

Acknowledgement of your software is important for a number of reasons, the most important of which is proper attribution for your hard work.  The information you place on your site should provide clear instructions on how you would like your citation to appear.  For example, your `README.MD` should provide a clear example of the citation as you would like it to appear publications and other works that cite your software.

#### Your software package’s web page or Github repository should include language indicating how you would like attribution

Provide a recommended citation on the software DOI’s landing page.  Here is an actual example from the [unidata IDV project](https://www.unidata.ucar.edu/software/idv/):

![](/software-citation/assets/idv_citation_example.PNG)

and 

> Unidata, (2012): Integrated Data Viewer (IDV) Version 3.1 [software]. Boulder, CO: UCAR/Unidata. ([http://doi.org/10.5065/d6rn35xm](http://doi.org/10.5065/d6rn35xm))

Based on this acknowledgement template the end user has clear awareness of the *name of the software package*, the *software version*, the *creator an the DOI* reference to the package.  It is consistent with what would be expected of an academic citation style found in a publication.

On the software's Github page include a recommended citation so if users find the landing page, but have not yet visited the source code, they can quickly understand how to cite the work.  Here is an example from the [wrf-python](https://github.com/ncar/wrf-python) software package repository on github:

![](/software-citation/assets/wrf_citation_example.PNG)

#### Add a Software DOI Badge to your Repository

DOI badges help improve the visibility of your software on your software repository.  This is a very simple way to let your visitors and end users know that there indeed exists a DOI and that they are being encouraged to use it.

You can add a DOI badge very easily to your top-level master branch `README.md` file with the following shortcode that uses the [shields.io](https://shields.io) badge catalog:

```markdown
[![DOI](https://img.shields.io/badge/DOI-YOUR NCAR DOI)](https://doi.org/YOUR_NCAR_DOI)
```

And once you add this to the first line of your `README.md`, your badge will look like this:

![](/software-citation/assets/doi_badge_example.PNG)


**&dagger; (Advanced) Include a command in the software that allows users to generate a citation:**

You can optionally include a command in the software that allows users to generate a citation.  The [latticekrig](https://cran.r-project.org/web/packages/LatticeKrig/index.html) project makes heavy use of the R programming language.  To encourage citation and to remind users that within their R environment that they may get an example of the citation as the authors intended, the `citation("latticekrig")` command in the language will generate the citation with the current running version of the software.