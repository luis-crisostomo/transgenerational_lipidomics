# transgenerational_lipidomics
R code used to analyse lipidomics data, based on R package "mixOmics"

The code provided in this repository was used to analyse lipidomics data for the paper "Transgenertional Lipidomics".
Univariate statistics were previously performed in SPSS v.26. The multivariate analysis based on the R package "mixOmics" was performed in RStudio running R 4.0.2.

The "mixOmics" R package implements unsupervised (without any grouping input) and supervised (with grouping input) multivariate analysis, mostly based on Projection of Latent Structures (PLS) Discriminant Analysis (DA). It further implements "sparse" methods to improve the selectivity of meaningful variables.

This analysis is structured as follows:
1) sPLS-DA of data obtained from GC-MS of testicular lipids (lipidomics)
2) 2-omics sPLS, combining GC-MS data (lipidomics) with 1H-NMR data from lipid percursors in testicular extracts (metabolomics)
3) block.sPLS-DA (DIABLO), combining the previous data plus the metabolomics data previously published by our research group (Crisóstomo et al., 2019; Crisóstomo et al., 2020)
