---
layout: default
title: Mint a DOI
---

### Mint an NCAR DOI

Minting NCAR DOIs is handled through 
the [NCAR Library](https://library.ncar.edu) and there are specific instructions for quickly and easily minting a 
DOI. Please follow the instructions here:

1. Request a DOI from the NCAR Library: [https://library.ucar.edu/research/data-management/DOIs](https://library.ucar.edu/research/data-management/DOIs)
2. You will need be ready to provide the following information to the NCAR Library:
    1. **A landing page**: a URL where the DOI will point. This might be the Github page, or your own web page where the software is available for download. The URL should be permanent and immutable.
    2. **Required minimum metadata**, including at minimum 
    * the Creators (name, lab), 
    * Title of the software, 
    * Publisher, and
    * PublicationYear of the software.
    
You may submit additional metadata as needed.

If you have any further questions please contact: ???@ucar.edu

#### Add a Software DOI Badge to your Repository

DOI badges help improve the visibility of your software on your software repository.  They are a very simple way to let your visitors and end users know that there indeed exists a DOI and that they are being encouraged to use it.

You can add a DOI badge very easily to your top-level master branch `README.md` file with the following shortcode that uses the [shields.io](https://shields.io) badge catalog:

```markdown
[![DOI](https://img.shields.io/badge/DOI-YOUR NCAR DOI)](https://doi.org/YOUR_NCAR_DOI)
```

And once you add this to the first line of your `README.md`, your badge will look like this:

![]({{ site.url }}/assets/doi_badge_example.PNG)
