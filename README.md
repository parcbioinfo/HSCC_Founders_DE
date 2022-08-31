# HSCC_Founders_DE
Differential expression (DE) analysis script for the HS-CC Founders manuscript published in the "Leveraging Genetic Diversity in Animal Models to Inform the Understanding of Human Disorders and Disease" special issue of "Frontiers in Behavorial Neuroscience". Script includes all figures produced for manscript as well as analysis.

https://www.doi.org/10.3389/fnbeh.2022.992727

https://www.frontiersin.org/articles/10.3389/fnbeh.2022.992727

Raw sequencing files (FASTQ), raw counts (STAR) and normalized counts (limma+voom TMM) are available from the Gene Expression Omnibus at accession ID GSE212000: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212000.  

The analysis script requires the raw counts (STAR) file located at https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE212000&format=file&file=GSE212000%5FHSCC%5FFounders%5FSTAR%5FCounts%2Etxt%2Egz. And the sample metadata file is stored here as "HSCC_Founders_Metadata.csv".

Additional differential expression results (computed via topTable) are also available here:
  (1) All pairwise results by region and strain are in the "Pairwise_DE_Results" folder.  Each .xlsx has 7 sheets corresponding to every comparison available for that strain.
  (2) All "signature genes" (Figure 5) by region are in the folder "Other_DE_results".
  (3) All DE using the "high" versus "low" contrast in limma+voom (Figure 6) are in the folder "Other_DE_Results".
  
Everything else is already present in the supplemental tables available at the journal.

Feel free to reach out if there is any other data you are interested in please reach out to the corresponding author, Dr. Justin Anderson(andejust@ohsu.edu).


Many of the above DE results are available as GeneSets on GeneWeaver.  These are listed below:
