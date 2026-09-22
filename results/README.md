# Results

This directory contains derived analytical outputs from the
Flyer × Hartwig soybean linkage-map reconstruction and QTL reanalysis.

## Directory structure

- `linkage_map/` — reconstructed linkage-map, structural-correction,
  physical-anchoring, and validation outputs
- `qtl/` — genome-wide QTL scans, empirical permutation thresholds,
  regional QTL results, and physical-localization outputs
- `candidate_genes/` — candidate-gene and genomic-context outputs
- `tables/` — publication-facing main and supplementary tables
- `figures/` — publication-facing main and supplementary figures

## Analytical versus publication-facing terminology

Some frozen analytical outputs retain internal status labels or filenames
such as `suggestive_10pct` or `provisional`. These labels are preserved
for computational provenance and compatibility with the original analysis
workflow.

In the manuscript and publication-facing tables and figures, QTL exceeding
the 10% genome-wide empirical permutation threshold are described as
significant at the 10% genome-wide empirical threshold. None of the QTL
identified in this study exceeded the 5% genome-wide empirical threshold.

The term `provisional` is not used in the final publication-facing
description of the structurally corrected linkage map.

## Reproducibility

The files in this directory are derived outputs. The corresponding
Python/Jupyter workflows are provided in the repository's `notebooks/`
directory, and the archived genotype and phenotype matrices are provided
under `data/`.

## License and reuse

Derived scientific results in this directory are made available under the
Creative Commons Attribution 4.0 International (CC BY 4.0) license.

Users may share and adapt these materials for any purpose provided appropriate
credit is given to the source and the associated repository/publication is
cited.

License information:
https://creativecommons.org/licenses/by/4.0/

The MIT License in the repository root applies to the software and
computational code and does not apply to these derived scientific results.
