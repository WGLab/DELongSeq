# Installation Guide

## Prerequisites:

`delongseq` has been tested on **python** 3.5, 3.6, 3.7 and **R** 3.5.2. If you don’t know the version of python you can check it by:
```bash
$ python --version
# Python 3.7.3
$ R --version
# R version 3.5.2
```

Following packages are required for running `delongseq`: 

  - Python:
    * Pysam
    * Numpy
    * Scipy
    * Lifelines
  - R:
    * metatest
    * betareg

Among the required packages, `math`, `sys`, `os`, `re` and `time` are included in the python standard library, meaning that they should be already installed with python.

## Github  
Download the package from [Github](https://github.com/WGLab/DELongSeq) and install it locally:

```bash
git clone https://github.com/WGLab/DELongSeq.git
cd DELongSeq
```

## Test
You can check whether the installation is complete by:
```bash
$ delongseq

# Please specify task (delongseq -task <task>):
#
#        refgene:   preprocess reference file
#
#        quantify:   quantify isoform expression
#
#        diff:   detect differential splicing gene/isoform

```
