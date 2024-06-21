## R Biovigilance of Phytopathogens Based on a Metabarcoding Approach

### Workshop organization committee
##### Wen Chen (AAFC -Workshop Instructor), Hervé Van der Heyden (AAFC - Preparation of workshop materials and website development) and Guillaume J. Bilodeau (CFIA)*

## Description 
##### Metabarcoding combines DNA barcoding with high-throughput sequencing (HTS) technologies for rapid and high-throughput identification of multiple species from environmental samples, offering a powerful tool for biodiversity studies and ecosystem monitoring. It has transformed our ability to profile complex microbial communities and track plant pathogens in various environments. 

##### This workshop will provide hands-on experience in metabarcoding-based community analysis using R, a versatile programming language and environment for statistical computing and graphics. You will learn about various R packages and tools that are essential for community data analysis, enabling you to effectively analyze and interpret metabarcoding data. 

##### This workshop is designed to demonstrate how you may use metabarcoding for plant pathogen monitoring and tracking. This is crucial for early detection and management of plant diseases and for agriculture and biodiversity conservation. We will explore case studies and practical applications, highlighting how metabarcoding, combined with R analysis, becomes a potential diagnostic tool for Biovigilance of phytopathogens.

## Data used for the workshop  
##### Data were collected once a week in 2021 in the southwest Montreal Muck soil region using a Cyclone sampler. DNA extractions were performed in Dr. Chen's laboratory and sequenced on Illumina (Chen), IonTorrent (Bilodeau) and Nanopore (Van der Heyden).

##### Data were collected by Dr. Carrisse's team once a week in 2021 in the Muck's region southwest of Montreal using a Cyclone sampler (Figure 1). DNA extractions were performed in Dr. Chen's laboratory and sequenced on Illumina (Chen), IonTorrent (Bilodeau) and Nanopore (Van der Heyden). Illumina and IonTorrent data were analysed using Dr Marc-Olivier Duceppe's pipeline (avilable here: https://github.com/duceppemo/QIIME2_ITS) with a database modified from UNITE v9.0 (2023-07-18). 

![plot](https://github.com/hvanderheyden/Plant_Canada_2024_workshop/blob/main/4_Figures/Pr%C3%A9sentation1.jpg)
*Figure 1. Location of the sites sampled used for this workshop (credit to Philippe Vigneault (AAFC))*

## R packages needed for the workshop  
```{r}
install.packages("BiocManager")
library("tidyverse") # install.packages("tidyverse")
library("phyloseq") # BiocManager::install("phyloseq")
library(microbiome) # BiocManager::install("microbiome")
library(microbiomeutilities) # remotes::install_github("microsud/microbiomeutilities")
library("ape") # install.install.packages('ape')
library(ampvis2) # install.packages("remotes") remotes::install_github("kasperskytte/ampvis2", Ncpus = 6)
library(MicrobiotaProcess) # BiocManager::install("MicrobiotaProcess")
``` 
