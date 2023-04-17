## Intro

Before starting, run code:

install.packages("BiocManager")
BiocManager::install("affy")
BiocManager::install("limma")
BiocManager::install("ath1121501.db") # This is the annotation used for the data we are using. It will be different for other data. Run annotate script to ensure it is correct.
