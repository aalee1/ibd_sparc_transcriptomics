# IBD SPARC Transcriptomics: Persistent Symptoms in Quiescent Crohn’s Disease

This repository contains analysis code, figure-generation scripts, and non-sensitive aggregate results for the manuscript:

**Mucosal Transcriptomic and Fecal Microbiome Signatures Associated With Persistent Symptoms in Quiescent Crohn’s Disease**

## Project overview

This study investigates why some patients with quiescent Crohn’s disease continue to experience persistent gastrointestinal symptoms despite limited endoscopic inflammatory activity. The analyses integrate mucosal bulk RNA sequencing and stool metagenomic data to evaluate transcriptomic signatures and fecal microbe–host gene covariation in ileal/proximal-colon and rectosigmoid/left-colon analyses.

The repository is organized around three main analytic approaches:

1. **DESeq2 differential expression and KEGG pathway enrichment**
2. **Multi-omics LASSO regression**
3. **Sparse canonical correlation analysis (sCCA)**

## Repository structure

```text
scripts/
├── 01_deseq2/      # DESeq2 differential expression and KEGG pathway analyses
├── 02_lasso/       # LASSO, de-sparsified LASSO, pathway analysis, and bootstrap stability
└── 03_scca/        # Sparse canonical correlation analysis and pathway summaries

figures/            # Final manuscript figures
supplement/         # Supplementary material, tables, and supplementary data files
environment/        # Software and package version information
docs/               # Data-access notes and analysis workflow documentation
