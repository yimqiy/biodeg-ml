# biodeg-ml

Raw codes for processing chemical biodegradability data using SMILES and RDKit parameters, used to predict ready biodegradability values using regression and GNN-based methods.

This is the cumulative product of a project first started at [IHPC](https://www.a-star.edu.sg/ihpc/ihpc-research-capabilities/materials-science-chemistry) in mid 2022, which is set for upload on chemRxiv soon. The notebook contains scripts and functions for:
- Loading and saving .sdf and .csv databases containing molecular conformers and SMILES/RDKit parameters respectively.
- Automated extraction of above-mentioend RDKit parameters as identified.
- Pre-processing for sk-learn models.
- Implementation of group-based cross-validataion based on common SMILES (for multiple conformers).

References:
1. [Predicting ready biodegradability in the Japanese Ministry of International Trade and Industry test](https://setac.onlinelibrary.wiley.com/doi/10.1002/etc.5620191013)
2. [Chemprop](https://chemprop.readthedocs.io/)
