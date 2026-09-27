# Analysis workflow

The repository is organized according to the major analysis components in the manuscript.

## 1. Cohort and clinical summaries

Folder: `scripts/00_cohort_table1/`

This section generates Table 1 and clinical supplementary summaries, including endoscopic and inflammatory characteristics.

## 2. DESeq2 and KEGG GSEA

Folder: `scripts/01_deseq2/`

This section performs differential expression analysis and ranked-list KEGG enrichment analysis for ileum and rectosigmoid colon transcriptomic data.

Main outputs include:
- Complete KEGG GSEA result files
- Inputs for Figure 1
- Sensitivity analyses using stricter remission definitions and targeted covariate adjustment

## 3. Multi-omics LASSO

Folder: `scripts/02_lasso/`

This section models fecal microbial abundance as the response and host gene expression as predictors. It includes LassoCV feature selection, de-sparsified LASSO inference, pathway analysis of selected host genes, and bootstrap feature-selection stability.

Main outputs include:
- Full-data LASSO gene–microbe result files
- Highlighted 12-pair summary
- Bootstrap selection-frequency results
- Inputs for Figure 2

## 4. Sparse canonical correlation analysis

Folder: `scripts/03_scca/`

This section performs sparse canonical correlation analysis using transcriptomic and microbial features within intestinal-site and symptom-status strata.

Main outputs include:
- sCCA model characteristics
- Canonical correlations
- Inputs for Figure 3

## 5. Figures and supplement

Folders:
- `figures/`
- `supplement/`

These folders contain final manuscript figures and supplementary material files.
