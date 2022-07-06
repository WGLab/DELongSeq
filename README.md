# DELongSeq
A computational algorithm and software tool for isoform quantification and differential isoform detection by long-read transcriptome sequencing

## Background
Conventional gene expression quantification approaches, such as microarrays or quantitative PCR, have similar variations of estimates for all genes. However, next-generation short-read or long-read sequencing use read counts to estimate expression levels with much wider dynamic ranges. In addition to the accuracy of estimated isoform expression, efficiency, which measures the degree of estimation uncertainty, is also an important factor for downstream analysis. Instead of read count, we present DELongSeq, which employs information matrix of EM algorithm to quantify uncertainty of isoform expression estimates to improve estimation efficiency. DELongSeq uses random-effect regression model for the analysis of DE isoform, in that within-study variation represents variable precision in isoform expression estimation and between-study variation represents variation in isoform expression levels across samples. More importantly, DELongSeq allows 1 case vs 1 control comparison of differential expression which has specific application scenarios in precision medicine (such as before vs after treatment, or tumor vs stromal tissues). 

## Inputs of DELongSeq
The input of DELongSeq is long-read RNA-seq read data in BAM format together with a refrence isoform annotation file.

## Installation
Please refer to [Installation](https://github.com/WGLab/DELongSeq/blob/master/doc/Install.md) for how to install DELongSeq.

## Usage
Please refere to [Usage](https://github.com/WGLab/DELongSeq/blob/master/doc/Usage.md) for how to use DELongSeq.

## Contact

If you have any questions/issues/bugs, please post them on [GitHub](https://github.com/WGLab/DELongSeq/issues). They would also be helpful to other users. 
