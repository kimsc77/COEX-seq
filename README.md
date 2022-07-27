# COEX-seq: COnvert a variety of measurements of gene EXpression in RNA-seq

COEX-seq is a web application(Shiny; a web application framework for R) framework for Convert a variety of measurements of gene expression in RNA-seq experiments. 


# INSTALL & RUN

1. Install R (www.r-project.org) & Rstudio (https://www.rstudio.com/)
2. Install Shiny package (https://cran.r-project.org/web/packages/shiny/index.html)
  - command line  
  - > install.packages("shiny") 
3. Download R codes (https://github.com/kimsc77/COEX-seq/issues/3)
  - Unzip COEX-seq.zip
  - load server.r and ui.r
4. Download Reference Dataset (https://github.com/kimsc77/COEX-seq/issues/2)
  - Ensemble_length.txt
  - Entrez_length.txt
  - GenBank_length.txt
  - GeneSymbol_length.txt
5. Run server.r(or ui.r) using Rstudio
6. Select Before Measurement : ex) Count
7. Select After Measurement : ex) TPM
8. Load Input file : ex) example file (https://github.com/kimsc77/COEX-seq/issues/1)
9. Click: Header, Seperator
10. Click Submit




