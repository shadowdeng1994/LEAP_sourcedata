# LEAP_sourcedata

Source data for the LEAP framework analyses.

## Overview

This repository contains source data and supplementary materials used in the study "Reconstructing cell phylogenies with resolved ancestral transcriptional states". This work presents **LEAP** (**L**UG-**e**ncoded **A**ncestral **P**rojection), a phylogeny-based computational framework designed to infer the transcriptional states of internal nodes within cellular lineages.

## Repository Structure

### DemoData
Example datasets for demonstrating the LEAP/TarCA workflow:
- `Query.RData` (7.4 MB) — Query single-cell RNA-seq dataset
- `Reference.RData` (114 MB) — Reference dataset for query-to-reference mapping

### SupplementaryMaterial
Annotation files and analysis results:

| File | Description |
|------|-------------|
| `Ann.IdentitySuperColor.tsv` | Cell identity annotations with germ layer classification, color coding, and ZFIN ontology links |
| `Ann.IndiName.tsv` | Individual-to-sample name mapping |
| `Ann.TimeSeries.tsv` | Developmental time series stages with hours-post-fertilization (hpf), cell counts, and cell division information |
| `Data.TarCA.RData` | TarCA analysis output data |
| `Var.HighConfidentLUGs.tsv` | High-confidence Lineage-specific Upregulated Genes (LUGs) with statistical metrics (HarmonicP, Signal Proportion, etc.) |
| `Var.InferredStateOfInternalNodes.tsv` | Inferred ancestral states of internal nodes in the phylogenetic tree, including cluster assignments and developmental stage information |

### Experiments
Contains experimental data and pipeline outputs.

## Related Resources

- **LEAP R package**: [github.com/shadowdeng1994/LEAP](https://github.com/shadowdeng1994/LEAP)
- **TarCA R package**: [github.com/shadowdeng1994/TarCA](https://github.com/shadowdeng1994/TarCA)
- **TarCA.beta R package (Quicker)**: [github.com/shadowdeng1994/TarCA](https://github.com/shadowdeng1994/TarCA.beta)
- **Relevant publication**: Deng et al. (2024) *Nature Methods*, DOI: [10.1038/s41592-024-02189-7](https://doi.org/10.1038/s41592-024-02189-7)
- **Contact**: Shanjun Deng (shadowdeng1994@gmail.com)

## Citation

If you use this data, please cite:

We're on track to publish something really exciting! **Star the repo and stay tuned!​** :smile:
