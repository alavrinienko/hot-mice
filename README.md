# Analysis: Comparable response of wild rodent gut microbiome to anthropogenic habitat contamination (Jupyter Notebook and R Markdown)

This repository contains the code used to analyse the data in Lavrinienko et al. 2021. The Jupyter Notebook and the R Markdown contain commands to process raw read data, reproduce the qiime2 analyses, stats and main figures.

This repository provides the main data files, i.e. metadata, dada2 feature-tables, representative sequences, phylogenetic tree and taxonomy. It should be possible to generate the rest of the data using these files and commands. The raw sequence data for this study have been deposited in the European Nucleotide Archive (ENA) at EMBL-EBI under accession number [PRJEB44039](https://www.ebi.ac.uk/ena/browser/view/PRJEB44039).

If you use this resource in your research, please cite the following [article](xxx):



## Requirements

qiime2 is required to run most of the commands described below (the xxxx.x qiime2 version was used).
To install qiime2 follow these instructions: xxx.
To activate the qiime2 conda environment run: source activate qiime2-xxx (or the other installed version).

### File explanations

 - qiime2 analysis notebook: chern-cmr-voles-v200419.ipynb
 - Metadata: metadata-malesrt.txt (metadata for wild bank voles from the Chernobyl Exclusion Zone, Ukraine)
 - qiime2 feature-table: malesrt2_table-dada2.qza (the original dada2 feature-table)
 - qiime2 rarefied feature-table: rarefied_table.qza (the 'filtered10', rarefied dada2 feature-table)
 - qiime2 representative sequences: malesrt2_rep-seqs-dada2.qza (the dada2 representative sequences)
