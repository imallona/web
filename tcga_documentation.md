---
title: "Resources for TCGA data mining"
output:
  html_document:
    toc: true
    theme: readable
---
  
## Data sources

### The Cancer Genome Atlas
* [Overview](https://cancergenome.nih.gov/)
* [Data Portal](https://portal.gdc.cancer.gov/)
* [Legacy Data Portal](https://portal.gdc.cancer.gov/legacy-archive)

#### Working with TCGA barcodes
* [TCGA Barcodes](https://docs.gdc.cancer.gov/Encyclopedia/pages/TCGA_Barcode/)

### GDAC Broad Firehose
* [GDAC Firehose](https://gdac.broadinstitute.org/)
* [GDAC Firebrowse](http://firebrowse.org/)

Example expression dataset retrieval for ACC:

```{bash}

# ACC RSEM genes normalized
wget http://gdac.broadinstitute.org/runs/stddata__2016_01_28/data/ACC/20160128/gdac.broadinstitute.org_ACC.Merge_rnaseqv2__illuminahiseq_rnaseqv2__unc_edu__Level_3__RSEM_genes_normalized__data.Level_3.2016012800.0.0.tar.gz

tar xzvf gdac.broadinstitute.org_ACC.Merge_rnaseqv2__illuminahiseq_rnaseqv2__unc_edu__Level_3__RSEM_genes_normalized__data.Level_3.2016012800.0.0.tar.gz

head gdac.broadinstitute.org_ACC.Merge_rnaseqv2__illuminahiseq_rnaseqv2__unc_edu__Level_3__RSEM_genes_normalized__data.Level_3.2016012800.0.0/ACC.rnaseqv2__illuminahiseq_rnaseqv2__unc_edu__Level_3__RSEM_genes_normalized__data.data.txt

```

## Good practices

### Reproducibility and transparency
* [Good enough practices in scientific computing (Wilson et al.)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
* [The extent and consequences of p-hacking in science (Head et al.)](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002106)

### Version control
* [Git manual (short)](http://rogerdudler.github.io/git-guide/)
* [A Quick Introduction to Version Control with Git and GitHub (Blischak et al.)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)
* [Github](github.com)
* [Bitbucket](bitbucket.org/)

### Literate programing
* [Rmarkdown (R)](https://rmarkdown.rstudio.com/lesson-1.html)
* [Python notebooks](https://jupyter.org/)

### Code styling
* [Google's R style guide](https://google.github.io/styleguide/Rguide.xml)
* [Python PEP8](https://www.python.org/dev/peps/pep-0008/)

## Training

* [SIB Swiss Institute of Bioinformatics tutorial on UNIX](https://edu.sib.swiss/pluginfile.php/2878/mod_resource/content/4/couselab-html/content.html)
* [Shell cheatsheet](https://files.fosswire.com/2007/08/fwunixref.pdf)
* [awk cheatsheet](http://www.grymoire.com/Unix/Awk.html)

## Slack channel
* [Pancancer Epigenomics Slack channel](https://pancancer-epigenomics.slack.com/)

_Last updated 15th Jan 2019 by imallona_

[Back to teaching](teaching.html)
