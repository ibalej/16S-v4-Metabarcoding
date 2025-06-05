# 16S-v4-Metabarcoding
# Microbiota in Headwater Stream Biofilms - Analysis with QIIME2

This repository contains all the scripts, metadata, and files required to reproduce the microbial diversity analysis based on the 16S rRNA gene, performed using QIIME2.

## Structure

- `metadata/`: Metadata files (`sample-metadata-16S.tsv`).
- `scripts/`: Sequential scripts used in QIIME2 (bash).
- `data/`: Original FASTQ files, exported `.qza` and `.qzv` artifacts.
- `outputs/`: Taxonomically collapsed results and visualizations.
- `environment/`: Conda environment for reproducibility.

## Tools Used
- Python 3.12
- Cutadapt v. 4.7  
- QIIME2 amplicon 2023.9
- SILVA 138.1 reference database
- R + packages: phyloseq, vegan, ggplot2
- Optional Python scripts for collapsing ASVs

#Licences
The **code** (scripts) is licensed under the [Apache License 2.0](LICENSE)

##️ Reproducibility

To create the environment with Conda:

```bash

conda activate
conda activate qiime2-amplicon-2023.9
