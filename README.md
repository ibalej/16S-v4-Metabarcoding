 This pipeline is based on the official QIIME 2 scripts (https://docs.qiime2.org/), with a custom workflow adapted to personal analysis needs.
 QIIME 2 is licensed under the BSD 3-Clause License.
 This repository is not officially affiliated with QIIME 2.
 16S-v4-Metabarcoding
# Microbiota in Headwater Stream Biofilms - Analysis with QIIME2

#This repository contains all the scripts, metadata, and files required to reproduce the microbial diversity analysis based on the 16S rRNA gene, performed using QIIME2.

## Structure

- `metadata/`: Metadata files (`sample-metadata-16S.tsv`).
- `scripts/`: Sequential scripts used in Cutadapt and QIIME2 (bash).
- `environment/`: Conda environment for reproducibility.

## Tools Used
- Python 3.12
- Cutadapt v. 4.7  
- QIIME2 amplicon 2023.9
- SILVA 138.1 reference database
- R + packages: phyloseq, vegan, ggplot2


## Reproducibility

To create the environment with Conda:

```bash

conda activate
conda activate qiime2-amplicon-2023.9


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15611455.svg)](https://doi.org/10.5281/zenodo.15611455)
