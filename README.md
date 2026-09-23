# Flyer × Hartwig Soybean QTL Reanalysis

This repository contains the Python/Jupyter computational workflow supporting
the genome-enabled reconstruction and QTL reanalysis of the historical
Flyer × Hartwig soybean recombinant inbred line (RIL) population.

## Repository contents

The Jupyter notebooks implement the principal computational analyses, including:

- genotype and phenotype quality control
- linkage-map reconstruction
- marker-order evaluation
- independent physical anchoring to Wm82.gnm6
- structural-map correction
- QTL analysis and empirical permutation testing
- physical localization of QTL significant at the 10% genome-wide empirical threshold
- candidate-gene prioritization
- manuscript figure and table generation

## Data availability

The archived genotype and phenotype matrices analyzed in this study are
provided in `data/raw/`.

The repository therefore contains the primary analytical inputs, computational
notebooks, and principal derived outputs associated with the study.

Publicly available Wm82.gnm6 soybean marker and gene-model resources used for
independent physical anchoring and genome annotation were obtained from
SoyBase and are documented in the repository but are not redistributed here.

## Reproducibility

The Jupyter notebooks document the computational workflow from source-data
quality control through linkage-map reconstruction, QTL analysis, physical
localization, candidate-gene analysis, and generation of manuscript figures
and tables.

Software versions used for the final analyses are recorded in
`requirements.txt`.

## Citation

A version of this repository corresponding to the published study will be
permanently archived in Zenodo and assigned a DOI.

## License and reuse

The Python/Jupyter software and computational code in this repository are
licensed under the MIT License; see `LICENSE`.

Research data distributed in `data/` and derived scientific outputs distributed
in `results/` are licensed under the Creative Commons Attribution 4.0
International (CC BY 4.0) license, as documented in the corresponding
directory README files.

External reference resources obtained from SoyBase are not redistributed in
this repository and remain subject to the terms of their original provider.

