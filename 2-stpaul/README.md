# Connecting genetic mutations to cytokine levels

**Hosted by:** St. Paul's Hospital  
**Mentor:** Keith Walley  
**Project Room:** ORCH 3068

## Summary

Cytokines are a broad and loose category of small proteins that are important in cell signaling. Their release has an effect on the behavior of cells around them. The challenge in this problem is to find patterns of Single Nucleotide Polymorphisms (SNPs: genotypes) that beget particular cytokine levels (phenotypes). Part of the data set provided is a list of patients’ blood work measurements (cytokine levels). These data are in a straightforward CSV file. The other part of the dataset is genomic data of the patients. These data are large collections of SNP markers on the patients’ genomes and are represented in plink format, a common format for genome studies. A part of the work the students would have to do is to unpack the plink data into a useful form for analysis. Finally, there is a genome reference online that indicates what is known about each SNP marker. There are about 330 (anonymized) patients, perhaps 40 cytokine markers, and entire genomes worth of data for each patient.

## Auxiliary Info

Non-clinical data (i.e., fully anonymized) from the VASST trial:
* ~330 patients
* ~50 cytokine concentration measurements per patients
* ~1.2 million SNP measurements in each patient

* Is there any relationship between any SNP (or a sensible combination of SNPs)
and a cytokine level?  Of course there will be because so many comparisons are
allowed.  Many of the cytokine levels substantially co-vary so replication
across covarying cytokines might help eliminate false positives.  Maybe the
results should include a prior from a publicly available GWAS (cf. paper in this
directory).

* Would AI approaches find relationships between genotype patterns and cytokine
levels?  


## About


[St. Paul’s Hospital](http://www.providencehealthcare.org/hospitals-residences/st-paul's-hospital) is an acute care, teaching and research hospital located in downtown Vancouver. It is home to many world-class medical and surgical programs, including heart and lung services, HIV/AIDS, mental health, emergency, critical care, kidney care, elder care and numerous surgical specialties.
