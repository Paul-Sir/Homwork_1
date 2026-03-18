# Homwork_1
Firstly was used fastqc was used to check the quality of raw sequence data. Then trim_galore was used to apply adapter and quality trimming to FastQ files. Using hisat2-build reference file is indexed. Then using hisat2 samples are mapped. samtools view was used to translate sam to bam files. samtools collate shuffles and groups reads together by their names, then samtools fixmate to correct file information, samtools sort to sort by coordinates and lastly samtools markup to check for duplicates. The geneBody_coverage.py was used to compute coverage on percentiles of the transcripts length. featureCounts was used to count reads for exons. 
multiBamSummary was also used to compute the read coverages for genomic regions for BAM files. These bam files were used to create correlation and PCA plots by using plotCorrelation and plotPCA. Pilnas kodas yra faile remote_code.txt


The rest of analysis was done in R through RStudio. 
These packeges were used: scales, ggplot2, ggfortify, pheatmap, RColorBrewer, enrichplot, ggridges, dplyr, data.table, tibble, tidyr, reshape2, DESeq2, apeglm, org.Hs.eg.db, clusterProfiler, msigdbr, biomaRt.
Pilnas analizės kodas yra faile HomWork_1.qmd.
