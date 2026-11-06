# Alzheimer’s Disease and Immune Responses in Microglia

## About this project
This project uses RNA-seq data to study how IFN-beta stimulation changes gene expression in human microglia, the immune cells of the brain. The goal is to explore how these changes relate to immune pathways involved in Alzheimer’s disease.

The samples compare resting and stimulated microglia, rather than people with and without Alzheimer’s disease.

## Dataset
The data come from the published study, *Functional characterization of Alzheimer’s disease genetic variants in microglia*.

- **BioProject:** [PRJNA851057](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA851057)
- **GEO:** [GSE206478](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE206478)
- **Data type:** Paired-end RNA-seq
- **Organism:** Human

There are 8 samples:

| Cell line | Resting | IFN-beta stimulated |
|---|---:|---:|
| WTC11 | 2 | 2 |
| H1 | 2 | 2 |

The analysis will compare the 4 resting samples with the 4 stimulated samples while accounting for differences between the two cell lines.

## Planned steps
1. Download the sequencing data from SRA.
2. Convert the data into FASTQ files.
3. Process the files using nf-core/rnaseq.
4. Compare gene expression between resting and stimulated microglia.
5. Create PCA plots, volcano plots, and heatmaps.
6. Explore Alzheimer’s-related immune pathways and compare findings with the original study.
