# Adapted-circlize-to-visualize-regulator-and-target-gene-associations

<ins>Notes/ file information: <ins>

The file labeled "original_code" corresponds to the script of the circlize package used to generate two modified versions, namely "enzyme_highlight" and "gene_highlight", which were subsequently used to generate the circle plots shown in Figure 4C, E of the associated review manuscript entitled "On the Drivers of Kidney Disease: Dysregulation of Tubular Cell Metabolism by Histone-Modifying Enzymes" (PMID not available yet).
 
The excel file labeled "updated circle plot - glucose.xlsx" corresponds to the input table for the modified codes ("enzyme_highlight" and "gene_highlight"). The table is adapted from Table S3 of the associated review manuscript, with formatting changes to enable simplified use in R.

<ins>Methods:<ins> 

Visualization of histone-modifying enzymes predicted to regulate glucose-related genes 

The associations between 17 glucose-related input genes and the 18 transcriptional regulators predicted to regulate them, were illustrated as circle plots using the circlize package in R (version 4.5.0) (Gu et al., 2014). The original R script, as well as the two modified versions of the script used to highlight specific regulators or target genes of interest have been made publicly available in this repository (https://github.com/SCFLab2026/Adapted-circlize-to-visualize-regulator-target-gene-associations). Genes were grouped by role (glucose transport or glycolysis), and epigenetic enzymes were categorized as activating or repressing based on their overall role in gene transcription (Table S3 of the associated review manuscript). Pubmed literature search was conducted to determine whether the epigenetic mark or marks associated with each regulator were activating or repressive of target gene transcription (Table S4 of the associated review manuscript). This information was used to assign the expected predominant effect of each of the regulators listed in Table S3 in activating or repressing gene transcription. In the circle plots, the edges depicting each regulator-target gene hit were colored according to the expected effect of the epigenetic regulator on gene expression (red = activating; blue = repressing).
<ins>Reference:<ins> 

Gu Z, Gu L, Eils R, Schlesner M, Brors B. circlize implements and enhances circular visualization in R. Bioinformatics. 2014;30(19):2811-2812. doi:10.1093/bioinformatics/btu393  
