---
layout: default
title: Provide  citation language
---

### Provide clear acknowledgement instructions for your software citation

Acknowledgement of your software is important for a number of reasons, the most important of which is proper attribution for your hard work.  The information you place on your site should provide clear instructions on how you would like your citation to appear.  For example, your `README.md` should provide a clear example of the citation as you would like it to appear publications and other works that cite your software.

#### Your software package’s web page or Github repository should include language indicating how you would like attribution

Provide a recommended citation on the software DOI’s landing page.  Here is an actual example from the [Unidata IDV project](https://www.unidata.ucar.edu/software/idv/):

![](/software-citation/assets/idv_citation_example.PNG)

and 

> Unidata, (2012): Integrated Data Viewer (IDV) version 3.1 [software]. Boulder, CO: UCAR/Unidata. ([http://doi.org/10.5065/D6RN35XM](http://doi.org/10.5065/D6RN35XM))

Based on this acknowledgement template the end user has clear awareness of the name of the software package, the version, the creator an the DOI reference to the packaage.  It is consistent with what would be expected of an academic citation style found in a publication.

On the software's Github page include a recommended citation on the that if users find the landing page but do have not yet visited the source code.  This is an example from the [WRF-Python](https://github.com/NCAR/wrf-python) software package repository on Github:

![](/software-citation/assets/wrf_citation_example.PNG)

#### Include a command in the software that allows users to generate a citation
You can optionally include a command in the software that allows users to generate a citation.  The LatticeKrig project makes heavy use of the R programming language.  To encourage citation and to remind users that within their R environment that they may get an example of the citation as the authors intended, with the `citation("LatticeKrig")` command in the language which will generate the citation with the current running version of the software.
