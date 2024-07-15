# Multiple myeloma

## The SAGA acetyltransferase module is required for the maintenance of MAF and MYC oncogenic gene expression programs in multiple myeloma." [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10996596/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10996596/).

Below is a brief summary of the scripts used for data analysis and visualization in this publication. For any queries, please contact bgovinal@mdanderson.org or bhaskartigp@gmail.com.

#### *Expression_Accessibility_changes.R*

This script generates a stacked bar chart to visualize the relationship between differential gene expression and chromatin accessibility changes over a period of 3 days and 5 days of Doxycycline treatment that was used to induce reduced expression of ADA2B. The categories include genes with decreased accessibility and upregulation, decreased accessibility and downregulation, increased accessibility and downregulation, and increased accessibility and upregulation.

#### *Metaplots for ATAC_peaks of Differentially Expressed Genes.R*

This script performs ATAC-seq data analysis to identify and visualize changes in chromatin accessibility associated with upregulated and downregulated genes under different treatment conditions. The script reads peak information, normalizes read counts to counts per million (CPM), categorizes genes based on log2 fold change, and generates plots to illustrate the normalized read coverage across genomic regions.

#### *Volcano_ATAC_Peaks.R*

The script reads peak information, processes the data to categorize chromatin accessibility peaks based on differential accessibility, and generates volcano plots to visualize the changes in chromatin accessibility, indicating increased and decreased accessibility.

#### *Volcano_GeneExpression.R*

The script reads gene expression data, processes it to categorize genes based on differential expression, and generates volcano plots to visualize the changes in gene expression, indicating increased and decreased expression.

#### *DepMAP_ADA2B_Effect.R*

This script processes the data to summarize mean CRISPR scores and expression values for ADA2B gene by lineage, and generates a scatter plot with labeled points for low CRISPR scores, highlighting specific cell lineages.


#### *DepScore_SAGA_components.R*
This script performs data analysis and visualization for the study of SAGA subunits dependency scores in multiple myeloma (MM) cell lines. It processes CRISPR dependency scores and expression data, categorizes genes based on their module, and generates box plots to visualize the dependency scores of different genes across various cell lines. 
