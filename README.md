## Before starting, run this as a script:
```

install.packages("BiocManager")
BiocManager::install("devtools")
BiocManager::install("affy")
BiocManager::install("limma")
## The following is the annotation used for the data 
## we are using. It will be different for other data.
## Run annotate script to ensure it is correct.
BiocManager::install("ath1121501.db")

library("devtools")
devtools::install_github(”https://github.com/joemontoya505/simplecelanalysis")

```

Then run file to generate html report


## Background

The current project looks at a plant in the mustard family that does not generate fungal networks through mycorrhizal signalling like most plants. It is assumed that the genes to initiate fungal network development are present, but are inhibited by other mechanisms. RNA taken from plants after being inocculated with fungal spored was compared to control plants. Gene expression analysis should help to determine which genes turn on when exposed to fungal spores.



