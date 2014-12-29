Cell Type Interactomes
==========

Collection of 73 cell type-specific interactomes created through the integration of protein-protein interaction data (STRING) and gene-expression data (FANTOM5 Project). Details of the method and data used to create the interactomes are given in the referenced paper. The interactomes can be recreated using the functions and data provided in the [DiseaseCellTypes R-package][1].


File Description
----------

Each .tsv file contains 3 headers:
- **ID.A**: The Ensembl Gene ID of the first interactor.
- **ID.B**: The Ensembl Gene ID of the second interactor.
- **WEIGHT**: The edge weight of the interaction in the cell type-specific interactome. Computed using the score.edges function, percentile-normalised relative gene expression scores from the FANTOM5 Project and protein-protein interactions from the STRING database.


References
----------

Our paper under preparation.

Forrest ARR et al. (2014) A promoter-level mammalian expression atlas. Nature 507(7493):462-470.

Franceschini A et al. (2013) STRING v9.1: protein-protein interaction networks, with increased coverage and integration. Nucleic Acids Res 41:D808-D815.


[1]: http://alexjcornish.github.io/DiseaseCellTypes
