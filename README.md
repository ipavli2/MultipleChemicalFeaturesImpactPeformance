# MultipleChemicalFeaturesImpactPeformance
Repository of median profiles used to profile a library of benzofuran and benzopyran and the commands used to generate data and figures in DOI: 10.1002/cbic.202000356

CellProfiler_illum, CellProfiler_QC, CellProfiler_analysis were the pipelines used for the generation of single-cell profiles from images using CellProfiler 3.0 as described here: DOI: 10.1038/nprot.2016.105.

Single-cell profiles were aggretgated, normalized and reduced with Cytominer_Aggregation, Cytominer_Robustize amd Cytominer_VariableSelection.

Aggregation, normalization and feature selection was adapted from: https://rdrr.io/github/cytomining/cytominergallery/

Mahalanobis and mp-value calculation were done using the mpvalue amd mpvalue_calculation. These were adapted from: DOI: 10.1177/1087057112469257

Hierchical clustering was done using hierchical_clustering.

PCA plots with confidence intervals were made using PCA_plots.

All analysis in R was done using R version 3.4.4. 
