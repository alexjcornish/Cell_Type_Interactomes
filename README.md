Cell Type-Specific Interactomes
==========

Collection of 73 cell type-specific interactomes created through the integration of protein-protein interaction data (STRING) and gene-expression data (FANTOM5 Project). Details of the method and data used to create the interactomes are given in Cornish et al. (2015). The interactomes can be recreated using the functions and data provided in the [DiseaseCellTypes R-package][1].


File Description
----------

Each .tsv file contains 3 columns:
- **ID.A**: The Ensembl Gene ID of the first interactor.
- **ID.B**: The Ensembl Gene ID of the second interactor.
- **WEIGHT**: The edge weight of the interaction in the cell type-specific interactome. Computed using the score.edges function, percentile-normalised relative gene expression scores from the FANTOM5 Project and protein-protein interactions from the STRING database.


References
----------

[Cornish AJ, Filippis I, David A and Sternberg MJE (2015) Exploring the cellular basis of human disease through a large-scale mapping of deleterious genes to cell types. Genome Medicine, 7:95][2]

[1]: http://alexjcornish.github.io/DiseaseCellTypes
[2]: http://genomemedicine.com/content/7/1/95