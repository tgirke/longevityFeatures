# longevityFeatures

R data package containing annotations of genes, proteins and other features associated with longevity and aging. The package is part of the [Longevity Genomics](http://www.longevitygenomics.org/) project funded by NIA. The website of this GitHub project is available [here](http://girke.bioinformatics.ucr.edu/longevityTools). The HTML vignettes of the package are available here:

* [longevityTools](https://htmlpreview.github.io/?https://github.com/tgirke/longevityTools/blob/master/vignettes/longevityTools.html): overview vignette
* [longevityTools_eQTL](https://htmlpreview.github.io/?https://github.com/tgirke/longevityTools/blob/master/vignettes/longevityTools_eQTL.html): eQTL, eSNP and GWAS analysis
* [longevityTools_eDRUG](https://htmlpreview.github.io/?https://github.com/tgirke/longevityTools/blob/master/vignettes/longevityTools_eDRUG.html): connecting drug- and age-related gene expression signatures
* [longevityDrugs](https://htmlpreview.github.io/?https://github.com/tgirke/longevityDrugs/blob/master/vignettes/longevityDrugs.html): structures, properties and annotations of small molecules associated with longevity
* [longevityFeatures](https://htmlpreview.github.io/?https://github.com/tgirke/longevityFeatures/blob/master/vignettes/longevityFeatures.html): this package

#### Installation 

```s
source("http://bioconductor.org/biocLite.R")
biocLite("tgirke/longevityFeatures", build_vignettes=FALSE, dependencies=FALSE)
```
