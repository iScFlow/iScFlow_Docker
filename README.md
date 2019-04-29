# iScFlow_Docker
Docker Image for iScFlow

Docker image for iScFlow pipeline for single cell analysis on Ubuntu base



This is a work in process as we test and optimize the pipeline

We have currently locked the image to R version 3.5.2



Final Packages include:
* scPipe
* seurat
* fastqc (fastqcr)
* trimgalore (trim_fastq)
* oposSOM
* scMatch

As well as the required tools to benchmark, rapid prototype, and tweak scripts.


See [iScFlow](https://github.com/iScFlow/iScFlow/) package for more details 


Current Working List:

* Editing & Prototype Tools *(emacs, git, nodejs, make, grep, zip, etc)*
* Python 2.7
* R 3.5.2 & Tools
* Bioconductor
* ggplot2, tiddyverse, data.table, Matrix
* fastqcr
* scPipe
* seurat
* scMatch




## Authors

* **Wes Wilson** - Creator and maintainer of the image for iScFlow / Developer for iScFlow
* **Bhavna Hurgobin** - Creator & Lead Developer of iScFlow

See also the list of [contributors](https://github.com/iScFlow/iScFlow_Docker/graphs/contributors) who participated in this project.
