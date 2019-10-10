This project aims to perform a primary analysis of a single cell RNA sequencing (scRNAseq) data set. The data set will be
downloaded from the website 10X genomics who provides sample data sets and all intermediate results to check your own work. 
The goal is to start from a .fastq file, which represents the outut file from state-of-the-art NGS sequencing devices, and 
to end with a dataframe containing m cells with n features with all metadata attached.
The primary single scRNAseq workflow has multiple consecutive steps:

  1. Quality control (QC) of the reads (Using FastQC)
  2. Allignment of the reads (here: pseudoalignment using kallisto/salmon)
  3. Mapping QC
  4. Cell QC
  5. Normalization
  6. Confounders
  
