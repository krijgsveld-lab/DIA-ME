# Enhanced feature matching in single-cell proteomics
This repository contains the Python code used in the DIA-ME pre-print (https://www.biorxiv.org/content/10.1101/2024.01.10.575010v1.article-metrics). 
Proteomic data originates from acquistion on a timsTOF Pro and Fusion Orbitrap instrument, and raw data can be found on PRIDE under the accession numbers:

# Project description (Abstract)
Proteome analysis by data-independent acquisition (DIA) has become a powerful approach to obtain deep proteome coverage, and has gained recent traction for label-free analysis of single cells. However, optimal experimental design for DIA-based single-cell proteomics has not been fully explored, and performance metrics of subsequent data analysis tools remain to be evaluated. Therefore, we here present DIA-ME, a data analysis strategy that exploits the co-analysis of low-input samples with a so-called matching enhancer (ME) of higher input, to increase sensitivity, proteome coverage, and data completeness. We evaluate the matching specificity of DIA-ME by a two-proteome model, and demonstrate that false discovery and false transfer are maintained at low levels when using DIA-NN software, while preserving quantification accuracy. We apply DIA-ME to investigate the proteome response of U-2 OS cells to interferon gamma (IFN-γ) in single cells, and recapitulate the time-resolved induction of IFN-γ response proteins as observed in bulk material. Moreover, we observe co- and anti-correlating patterns of protein expression within the same cell, indicating mutually exclusive protein modules and the co-existence of different cell states. Collectively our data show that DIA-ME is a powerful, scalable, and easy-to-implement strategy for single-cell proteomics.

# Project structure
1. Introduction and evaluation of the DIA-ME workflow
2. Comparison of DIA-ME and standard analysis of 200-pg samples in respect to results from conventional 200-ng bulk samples
3. Application of our enhanced workflow to individual U-2 OS cells treated with interferon gamma (IFN-γ)
