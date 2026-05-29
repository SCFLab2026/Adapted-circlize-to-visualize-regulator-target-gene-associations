# Adapted-circlize-to-visualize-regulator-and-target-gene-associations

<ins>Notes/ file information: <ins>

File named "original_code" made by Maya Bozzo-Rey using open source tutorials on the "circlize" package in R.
Original associations file used in "original_code" contained genes related to glycolysis, TCA cycle and glutaminolysis. As the project evolved, the selected list of genes was altered to focus on glycolysis and glucose transporters only. As well, list of epigenetic enzymes was altered following analysis by GeneCards to determine function of the enzymes. 

Files named "enzyme_highlight" and "gene_highlight" were created by Maya Bozzo-Rey with the use of ChatGPT in step 5 (altering transparency of certain links) of both files. 

Table labeled "updated circle plot - glucose.xlsx" is adapted from Table S3 with formatting changes to enable simplified use in R. 

Methods: 

Visualization of histone-modifying enzymes predicted to regulate glucose-related genes 

The associations between the 17 glucose-related input genes and the 18 transcriptional regulators predicted to regulate them, were illustrated as circle plots using the circlize package in R (version 4.5.0) (Gu et al., 2014). The two different R scripts used to highlight specific histone-modifying enzymes or target genes of interest have been shared as .txt files in a compressed .zip folder (see Supplemental Materials). Genes were grouped by role (glucose transport or glycolysis), and epigenetic enzymes were categorized as activating or repressing based on their overall role in gene transcription (see Table S3). Pubmed literature search was conducted to determine whether the epigenetic mark or marks associated with each regulator were activating or repressive of target gene transcription (Table S4). This information was used to assign the expected predominant effect of each of the regulators listed in Table S3 in activating or repressing gene transcription. In the circle plots, the edges depicting each regulator-target gene hit were colored according to the expected effect of the epigenetic regulator on gene expression (red = activating; blue = repressing). 

Reference: 

Gu Z, Gu L, Eils R, Schlesner M, Brors B. circlize implements and enhances circular visualization in R. Bioinformatics. 2014;30(19):2811-2812. doi:10.1093/bioinformatics/btu393  
