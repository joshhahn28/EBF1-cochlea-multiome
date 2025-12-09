# EBF1-cochlea-multiome
This repository contains the code used in the paper "EBF1 regulates sensory establishment in the cochlea by positioning the medial boundary of the prosensory domain and restricting proliferation of the sensory progenitor population" to perform the multiome analysis and generate figures.

## Abstract
In our previous study, we reported that Ebf1 excision throughout the inner ear epithelium and before the onset of cochlear development leads to dramatic sensory expansion in the cochlea by neonatal stages. Ebf1 conditional knockout cochleae possess over twice as many sensory cells as littermate controls and develop ectopic sensory patches in their Kölliker’s organs. To better understand the mechanism behind EBF1’s role in restricting sensory establishment, we performed multiome sequencing in our current study. EBF1 is a transcription factor best known for its importance in B cell lineage specification, during which it acts as both an activator and a repressor. Our results indicate that EBF1 prevents the Kölliker’s organ cells from being recruited to the prosensory domain by promoting expression of Prdm16 and repressing expression of Jag1 and Sox2. We also found that EBF1 may promote cell cycle exit by repressing Ccnjl expression. In summary, medial expansion of the prosensory domain, together with delayed cell cycle exit in the developing cochlear epithelium, underlies the robust increase in sensory cells seen in Ebf1 conditional knockouts.

## Notebook Details
This repository contains two notebooks, Object Creation.Rmd and Figure Plotting.Rmd. 

### Object Creation.Rmd
This notebook details the creation of Seurat objects from a 10x Multiome run. Raw sequencing data has been published on GEO under accession number GSE310246. 10x cellranger runs, as well as the final Seurat objects, can be supplied upon request. 

### Figure Plotting.Rmd
Given the objects generated in Object Creation.Rmd, this notebook provides code to generate the figures presented in the paper. 
