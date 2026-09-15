# Flyer × Hartwig source data

This directory contains the archived genotype and phenotype matrices analyzed
in the genome-enabled reanalysis of the Flyer × Hartwig soybean recombinant
inbred line (RIL) population.

## Genotype data

`raw/fxh_genotypes.xlsx` contains the archived molecular-marker genotype matrix.

Rows represent RILs and columns represent legacy molecular markers. Genotype
calls used in the present analysis were coded as:

- `2` = Flyer allele
- `0` = Hartwig allele
- missing value = genotype unavailable

Quality-control procedures, marker filtering, and RIL exclusions are documented
in the accompanying Jupyter notebooks.

## Phenotype data

`raw/fxh_phenotypes.xlsx` contains the archived phenotype matrix used for QTL
analysis. The workbook includes disease, agronomic, seed-composition, root, and
other quantitative traits evaluated in the Flyer × Hartwig population, together
with the available trait-description information.

## Population

The population consists of F5-derived recombinant inbred lines developed from
the soybean cross Flyer × Hartwig.

## Data provenance and analysis

These archived matrices constitute the primary source data used for the analyses
reported in the associated study. Genotype quality control, linkage-map
reconstruction, QTL analysis, physical localization, and downstream genomic
analyses are documented in the Jupyter notebooks provided with this repository.

The historical linkage-map workbook was not used as an analytical input for the
reconstructed genetic map. Linkage relationships were reconstructed directly
from the genotype matrix, and physical chromosome assignments were evaluated
independently using contemporary soybean genomic resources.