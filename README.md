# GuidedDifferentiation

Code used in the analysis of data generated from scRNA-seq of guided differentiation cell cultures, as reported in "Guided Differentiation of Pluripotent Stem Cells for Cardiac Cell Diversity"  
  
The R directory contains an R Markdown file with code for the following:
  
1. Manual annotation of guided differentiation cell cultures using Seurat. This code produces Fig. 1B and 1C, as well as Supplemental Fig. 2 and 3.  
2. Seurat integration of a 16-day iPSC-CM differentiation time-course dataset published by Elorbany et al. (2022), and the guided differentiation dataset. This code produces Fig. 2 and Supplemental Fig. 4.
3. Automated annotation of cells from guided differentiation cell cultures, mature multilineage organoids published by Silva, et al. (2021), and a PBMC dataset from 10x Genomics. Automated annotation was performed using the scPred prediction model trained on annotated fetal heart cells published by Miao et al. (2020). This code produces Fig. 3A, 3C, and 3D, as well as Extended Figure 5.

To see the knitted R Markdown file with figures, please visit:
https://erikmcintire.github.io/Guided_differentiation/