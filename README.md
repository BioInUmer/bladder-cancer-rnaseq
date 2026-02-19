# RNA-Seq Analysis: Bladder Cancer

This project explores transcriptomic differences between early-stage (I–II) and late-stage (III–IV) bladder cancer using publicly available TCGA RNA-seq data from [recount2](https://jhubiostatistics.shinyapps.io/recount/).

The motivation behind this analysis is both academic and personal — a close relative was recently diagnosed with early-stage bladder cancer, which sparked an interest in understanding what changes at the molecular level as the disease progresses.

## Overview

The analysis walks through a complete RNA-seq differential expression pipeline in R:

- **Data acquisition** — downloading and preparing the bladder cancer RSE object from TCGA
- **Quality control & normalization** — comparing CPM, RPKM, and TPM normalization strategies
- **Exploratory analysis** — PCA and hierarchical clustering to visualize sample structure
- **Differential expression** — identifying 737 DE genes between early and late stages using DESeq2
- **Functional enrichment** — linking DE genes to diseases (DisGeNET) and biological processes (Gene Ontology)

## Repository Contents

| File | Description |
|------|-------------|
| `Transcriptomics_analysis.Rmd` | R Markdown source with full code and narrative |
| `Transcriptomics_analysis.html` | [View the rendered report](https://BioInUmer.github.io/bladder-cancer-rnaseq/Transcriptomics_analysis.html) |


> The raw data files are not included due to their size. See the report for download instructions and sources.

## Built With

R · DESeq2 · clusterProfiler · ggplot2 · pheatmap · EnhancedVolcano

## Author

**Muhammad Umer Hussain Kousar**
