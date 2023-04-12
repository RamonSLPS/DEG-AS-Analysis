This pipelines were made to study Differentialy Expressed Genes and the occurrence of Alternative Splicing and isoform switching events parting from two biological triplicates of paired-end RNAseq data.

Pre-requirements and tools:
- Trimmomatic
- Salmon quant
- R v4.2 or higher
- Bioconductor package
- Tximport and TximportData
- GenomicFeatures
- DESeq2
- IsoformSwitchAnalyzeR

The "Processing and quantification" pipeline contains the data processing steps made in shell/bash using Trimmomatic and transcripts abundance quantification with Salmon.

The "Importing and DEG analysis" pipeline explain step by step how to import your salmon quantification results into R and the additional necessary information to run the Gene Differential Expression Analysis using the R packages GenomicFeatures, Tximport and DESeq2.

The "Alternative Splicing analysis" pipeline shows the last step of the study, showing how to use the R package IsoformSwitchAnalyzeR to identify and annotate the occurence, type and number of alternative splicing events and the resultant iform switching. 

