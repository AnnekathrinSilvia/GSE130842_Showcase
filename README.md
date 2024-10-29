# ASN_PhD_Thesis
The repository accompanying my PhD thesis "Enhancing Analysis and Interpretation Workflows for Transcriptome Data with an Interactive R/Bioconductor Toolkit"

This repository contains several files spanning several different topics of the thesis. 

# Showcase of Analysis of Transcriptome Data

In my thesis I presented an analysis of publicly available murine transcriptome data published on GEO under accession number GSE130842.
The data was downloaded and can be found in the "GSE130842_Count_table_Delacher_et_al_2019.xlsx" Excel file. Accompanying meta data to the dataset can be found in "GSE130842_Metadata.csv".

All conducted analyses can be found in the "Enhancing analysis and interpretation workflows for transcriptome data with an interactive R/Bioconductor toolkit.Rmd", with a rendered version available in the corresponding HTML file.

Intermediate results of the analysis, such as the GeneTonicList object and calculated distance scores can be found in the RDS objects in this repository. The results of the DE and funcitonal enrichment analysis can be found in the corresponding csv files. Further details can be found in the Rmd file. 

# Figure Generation for the Thesis

Some of the figures for my thesis have been generated using R code. This code can as well be found in the 
All conducted analyses can be found in the "Enhancing analysis and interpretation workflows for transcriptome data with an interactive R/Bioconductor toolkit.Rmd" file.


# Literature Review

In this thesis I conducted a Literature Review to assess the current standard of functional enrichment analysis reporting in published literature. 

The results of the manual Pubmed search can be found in the "Manual_Search_of_Pubmed_11.09.2024.csv" file, with the list of the 20 randomly selected articles found in "Manual_Search_20_Randomly_Selected_Articles.csv".
The results of the two searches using the `pubmedR` package can be found in the files "PubmedR_Randomly_Selected_50_Articles.csv" and "Manual_Search_20_Randomly_Selected_Articles.csv". 

A detailed evaluation of the articles can be found in "Reviewed_Paper_Summary.xlsx" Excel file. This file contains a description of the evaluated parameters and a sheet for each of the three literature searches.

The code for the `pubmedR` searches and the random selection of the articles can be found in the following Github repository: https://github.com/imbeimainz/HIPSTER




