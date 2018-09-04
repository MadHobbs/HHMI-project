# HHMI project

## Overview

In this HHMI summer 2017 research project, I:

• Established how all 4,377 genes in the E. coli genome respond to varying levels of rpoS (key transcription regulator protein) by performing cluster analysis and statistical tests for differential expression

• Parsed text using regular expressions to unify multiple files of messy data into tidy data

• Revealed key, unanticipated insights and presented at two poster sessions (see poster)

## Abstract 

There is biological interest in how the gene expression of all RpoS-regulated genes in E. coli change at different levels of RpoS, a protein which regulates the bacteria’s general stress response. Although many studies have investigated the genome-wide effects of turning RpoS on and off, varying the level of RpoS had been largely unexplored prior to the work done in Dr. Stoebel’s lab. Our prior research has focused on the sensitivity of genes to different RpoS levels, for instance whether gene expression is affected even at low levels of RpoS or whether higher RpoS levels are needed before gene expression changes. We design six gene expression profiles: sensitive positive regulation, sensitive negative regulation, insensitive positive regulation, insensitive negative regulation, linear positive regulation, and linear negative regulation. Dr. Stoebel's lab conducted an experiment with three RpoS levels (0%, 26%, 100), and we classified genes into the six groups above. This summer, with six levels of RpoS (0%, 0.35%, 20.40%, 48.37%, 129.96%, 190.38%), we have been comparing our results to the earlier profile assignments and developing new ways to group genes according to expression shape. The vast majority of genes in the six-level RpoS dataset show a sensitive positive or sensitive negative regulation shape when using the profiles we designed, however the genes are generally poorly correlated and lack differentiability between the six profiles. To get a better sense of the primarily observed expression shapes, we implement Partitioning Around Medoids (Maechler et al. 2017) clustering analysis. The most prevalent shapes in the data identified by Partitioning Around Medoids clustering include shapes that appear sensitive positive, sensitive negative, linear positive, and non-monotonic. A deeper level of sequencing and other concerns regarding technical error need to be addressed however before we draw conclusions from the six-level RpoS data. 

## Note

The code and data cannot be shared because it is private research which belongs to Dr. Jo Hardin and Dr. Dan Stoebel. You can view their publication which laid the groundwork for my research [here](https://jb.asm.org/content/early/2017/01/18/JB.00755-16).
