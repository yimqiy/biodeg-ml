# biodeg-ml

Raw codes for processing chemical biodegradability data using SMILES and RDKit parameters, used to predict ready biodegradability values using regression and GNN-based methods.

This is the cumulative product of a project first started at [IHPC](https://www.a-star.edu.sg/ihpc/ihpc-research-capabilities/materials-science-chemistry) in mid 2022. The notebook contains scripts and functions for:
- Loading and saving .sdf and .csv databases containing molecular conformers and SMILES/RDKit parameters respectively.
- Automated extraction of above-mentioend RDKit parameters as identified.
- Pre-processing for sk-learn models.
- Implementation of group-based cross-validataion based on common SMILES (for multiple conformers).
