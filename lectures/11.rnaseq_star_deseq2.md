---
layout: page
title: RNA-Seq data analysis
summary: "RNA-seq data analyss with different approachs."
---

![Pipeline]({{site.url}}/images/pipeline.jpg)

## Introduction

RNA-Seq (RNA sequencing ) also called whole transcriptome sequncing  use next-generation sequeincing (NGS)  to reveal the presence and quantity of RNA in a biolgical sample at a given moment.
As we discuss during the talk we can use different approach and different  tools. Here we present the  DEseq2 vignette  it wwas composed using STAR and HTseqcount and then Deseq2. The other part we show kallisto
Unfortunately our computer not allow the work some stap was only for demonstration purpose.


## Practical 1



In this example we will use a downsampled version of simulated Drosophila melanogaster RNA-seq data used by Trapnell et al. 2012. These include two conditions (C1 and C2), each containing three replicates (R1, R2, and R3) sequenced as a paired end library. Thus in total there are 12 fastq datasets.  



[Galaxy version] (https://galaxyproject.org/tutorials/rb_rnaseq/#lets-try-it)


Here we use  the snakemake  version of rna-seq pipeline with  STAR and  htseqcount and DESEq2:

```

		git clone https://github.com/bioinfo-dirty-jobs/rna-seq-star-deseq2

		cd  rna-seq-star-deseq2

		conda create -n rnaseq

		conda activate rnaseq

		conda install snakemake

		
```