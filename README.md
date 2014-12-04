Cell Type Interactomes
===

Collection of 73 cell type-specific interactomes created through the integration of protein-protein interaction data (STRING) and gene-expression data (FANTOM5 Project). These interactomes were created using the **score.edges** function from the **DiseaseCellTypes** R-package.

**DiseaseCellTypes** R-package is available from: http://alexjcornish.github.io/DiseaseCellTypes.

Details of the method and data used to create these interactomes is given in the referenced paper. These interactomes can be recreated using the functions and data provided in the **DiseaseCellTypes** R-package.


File Description
===========

Each .tsv file contains 3 headers:
- **ID.A**: The Ensembl Gene ID of the first interactor.
- **ID.B**: The Ensembl Gene ID of the second interactor.
- **WEIGHT**: The edge weight of the interaction in the cell type-specific interactome. Computed using the **score.edges** function, percentile-normalised relative gene expression scores from the FANTOM5 Project and protein-protein interactions from the STRING database.


References
===========

Paper under preparation.
