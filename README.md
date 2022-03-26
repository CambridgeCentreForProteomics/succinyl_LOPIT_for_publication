# Succinyl_LOPIT
An extension of LOPIT to explore the subcellular distribution of succinylated peptides

Repository structure:
- *raw*: PSM-level output from Proteome Discoverer
- *shared files*: Reference and cRAP fasta files, protein abundances and GO annotations
- *notebooks*: Analyses in R markdown notebooks, with order indicated by prefix     
- *results*: Intermediate and final outputs from notebooks and plots
- *figures*: Figure panels for manuscript


###### Dependencies for notebooks:
- R >= 4.0.3
- tidyverse (CRAN)
- ggrepel (CRAN)
- RColorBrewer (CRAN)
- MSnbase (Bioconductor)
- biomaRt (Bioconductor)
- goseq (Bioconductor)
- pRoloc  (Bioconductor)
- camprotR (https://github.com/CambridgeCentreForProteomics/camprotR)
- OptProc (https://github.com/TomSmithCGAT/OptProc)
- pRolocExt (https://github.com/TomSmithCGAT/pRolocExt)


