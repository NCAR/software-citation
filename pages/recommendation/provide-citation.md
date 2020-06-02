---
layout: default
title: Provide citation language
---

### Provide clear acknowledgement instructions for your software citation

Acknowledgement of your software is important for a number of reasons, the most important of which is proper attribution for your hard work.  The information you place on your site should provide clear instructions on how you would like your citation to appear.  For example, your `README.MD` should provide a clear example of the citation as you would like it to appear publications and other works that cite your software.

#### your software package’s web page or github repository should include language indicating how you would like attribution

Provide a recommended citation on the software DOI’s landing page.  Here is an actual example from the [unidata idv project](https://www.unidata.ucar.edu/software/idv/):

![](/software-citation/assets/idv_citation_example.PNG)

and 

> unidata, (2012): integrated data viewer (idv) version 3.1 [software]. boulder, co: ucar/unidata. ([http://doi.org/10.5065/d6rn35xm](http://doi.org/10.5065/d6rn35xm))

based on this acknowledgement template the end user has clear awareness of the *name of the software package*, the *software version*, the *creator an the DOI* reference to the packaage.  It is consistent with what would be expected of an academic citation style found in a publication.

On the software's github page include a recommended citation on the that if users find the landing page but do have not yet visited the source code.  This is an example from the [wrf-python](https://github.com/ncar/wrf-python) software package repository on github:

![](/software-citation/assets/wrf_citation_example.PNG)

#### Include a command in the software that allows users to generate a citation
You can optionally include a command in the software that allows users to generate a citation.  the latticekrig project makes heavy use of the r programming language.  to encourage citation and to remind users that within their r environment that they may get an example of the citation as the authors intended, with the `citation("latticekrig")` command in the language which will generate the citation with the current running version of the software.

#### Add a Software DOI Badge to your Repository

DOI badges help improve the visibility of your software on your software repository.  They are a very simple way to let your visitors and end users know that there indeed exists a DOI and that they are being encouraged to use it.

You can add a DOI badge very easily to your top-level master branch `README.md` file with the following shortcode that uses the [shields.io](https://shields.io) badge catalog:

```markdown
[![DOI](https://img.shields.io/badge/DOI-YOUR NCAR DOI)](https://doi.org/YOUR_NCAR_DOI)
```

And once you add this to the first line of your `README.md`, your badge will look like this:

![](/software-citation/assets/doi_badge_example.PNG)


