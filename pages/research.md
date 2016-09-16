---
layout: page
title: Research
---

[Google Scholar](http://scholar.google.com/citations?user=4T4qnL4AAAAJ) &nbsp; | &nbsp; 
[github](https://github.com/stephaniehicks)  &nbsp; | &nbsp; 
[ORCID](http://orcid.org/0000-0002-7858-0231)

#### Research Interests
My research interests are focused on developing statistical methods, tools and software for the analysis of genomics data, which often contains noisy or missing data and systematic biases. Specifically, my research addresses statistical and computational challenges in functional genomics such as the pre-processing, normalization, analysis of raw high-throughput data (microarray and next-generation sequencing) leading to an improved quantification and understanding of biological variability. Some of my previous and current work has involved statistical methods for inferring latent variables using genomic data including EM algorithms. Here are a few software packages and data packages that I have authored:


#### Software

- [R/qsmooth](https://github.com/stephaniehicks/qsmooth): R package available on GitHub that implements a generalization of quantile normalization, referred to as smooth quantile normalization (**qsmooth**), which is based on the assumption that the statistical distribution of each sample should be the same (or have the same distributional shape) within biological groups or conditions. 
- [R/quantro](http://www.bioconductor.org/packages/release/bioc/html/quantro.html): R package available on Bioconductor to test for global differences between groups of distributions to decide when to use quantile normalization.
- [R/quantroSim](https://github.com/stephaniehicks/quantroSim): Supporting data simulation R-package for the *quantro* R-package 
to simulate gene expression and DNA methylation data.
- [R/explainr](https://github.com/hilaryparker/explainr): translates S3 objects into text using standard templates in a simple and convenient way. 
- [postMUT](https://github.com/stephaniehicks/postMUT): A tool implemented in Perl and R to predict the functionality of missense mutations.


#### Data Packages

- [bodymapRat](https://github.com/stephaniehicks/bodymapRat): R data package that contains an ExpressionSet from the Yu et al. (2013) paper that performed the rat BodyMap across 11 organs and 4 developmental stage (PMID: 24510058). 
- [colonCancerWGBS](https://github.com/genomicsclass/colonCancerWGBS): Cov files produced from [Bismark](http://www.bioinformatics.babraham.ac.uk/projects/bismark/) after mapping six paired tumor-normal WGBS samples from Ziller et al. (2013) PMID: 23925113. Only chr22. 
- [myAffyData](https://github.com/stephaniehicks/mycAffyData): AffyBatch object from an experiment using P493-6 cells expressing low or high levels of c-Myc. Data from Loven et al. (2012) Cell 151: 476-482.
- [BackgroundExperimentYeast](https://github.com/stephaniehicks/BackgroundExperimentYeast): AffyBatch object from an experiment to measure NSB and optical noise in yeast.

#### Invited Talks	
- [On the widespread and critical impact of systemic bias and batch effects in single-cell RNA-seq data](https://speakerdeck.com/stephaniehicks/towards-progress-in-batch-effects-and-biases-in-single-cell-rna-seq-data). [Presented](http://hsci.harvard.edu/event/widespread-and-critical-impact-systemic-bias-and-batch-effects-single-cell-rna-seq-data?delta=0) at the [Boston Single-Cell Network Meeting](http://www.singlecellnetwork.org) in March 2016 (Boston, MA, USA), [presented](https://www.amstat.org/meetings/jsm/2016/onlineprogram/MainSearchResults.cfm) at the Joint Statistical Meetings Aug 2016 (Chicago, IL, USA), and [presented](https://coursesandconferences.wellcomegenomecampus.org/events/item.aspx?e=596) at the Single-Cell Genomics Conference Sept 2016 (Hinxton, UK). 
- [Why Statistics Matters in the Analysis of Genomics Data](https://speakerdeck.com/stephaniehicks/why-statistics-matters-in-the-analysis-of-genomics-data) ([Youtube video](https://www.youtube.com/watch?v=3EVtJPz4kCI)). Presented at the LSU Computational Biology seminar and the LSUConnect event in Feb 2015. 
- Normalization of DNA methylation and Gene Expression Data in the Context of Global Variation. Presented at the Bioinformatics Meeting, Division of Immunology, Harvard Medical School in Sept 2014. 
