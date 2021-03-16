# network-inference-by-aracne-in-R

## Overview


**net_inf_ARACNE.Rmd** and **net_inf_WGCNA.Rmd** scripts provide mutual information-based and bicor-based methods for the genome-wide reverse engineering of gene regulatory networks, implemented in [Minet R package](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-461), and [WGCNA R package](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/), respectively. Here, we use [ARACNE](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-7-S1-S7) and [WGCNA](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/) to infer a gene regulatory network from a [data set](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE119931) of 27123 genes and 6 samples. For further details about pre-processing steps (normalization and noise elimination), please refer to https://github.com/saezlab/transcriptutorial/blob/master/scripts/01_normalisation.md.

The **dorothea_int_aracne.Rmd** script is used to extract matching TF-Target ineractions between [Dorothea](https://bioconductor.org/packages/release/data/experiment/html/dorothea.html) and [ARACNE](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-7-S1-S7) inferred regulons.

