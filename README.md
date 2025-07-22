# Seabirds-Migration-Proteomics



\# 🐦 Seabirds‑Migration‑Proteomics



This repository contains code and analysis for a study investigating proteomic signatures in seabirds during migration. Blood plasma samples from Sable Shearwater fledglings prior to commencing migration and adults returning from migration were sampled. 



---



\## 📁 Repository Structure



&nbsp;   ├── Seabirds‑Migration‑Proteomics.Rproj     # RStudio project file

&nbsp;   ├── Seabirds‑Migration‑Proteomics.Rmd       # Main analysis in R Markdown

&nbsp;   ├── Seabirds‑Migration‑Proteomics.html      # Rendered HTML output

&nbsp;   ├── LICENSE

&nbsp;   └── README.md



---



\## ✅ Requirements



\- R version ≥ 4.0

\- Recommended packages:



```r

install.packages(c(

&nbsp; "tidyverse", "ggplot2", "MSnbase",

&nbsp; "limma", "readxl", "pheatmap", "clusterProfiler"

))



The analysis includes:

\- Data import and quality control

\- Protein quantification and z-scoring

\- PCA and clustering analyses

\- Differential protein expression analysis

\- Visualization (volcano plots, heatmaps)

\- Functional enrichment and pathway analysis



Data notes: 

Processed data are not included in this public repositiory. Raw proteomic data can be downloaded from ProteomeXchange. Project accession code: PXD064350. 



Reference:

de Jersey, A. M., Wilson, R., Bond, A. L., Zosky, G. R., Rivers-Auty, J., \& Lavers, J. L. (in review). Proteomic insights into the migration readiness and recovery of Sable Shearwater fledglings and adults. ICES Journal of Marine Science. 



Contact:

Alix de Jersey

PhD Candidate | University of Tasmania | Adrift Lab

Email: alix.dejersey17@gmail.com



