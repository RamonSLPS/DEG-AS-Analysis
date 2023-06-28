This Git shows a four-part pipeline to analyze eukaryotic RNA-seq data. Containing processing, quantification, differential expression and alternative splicing analysis. And a fifth non obligartory Ensembl codes gene annotation pipeline.

Dependencies and versions necessary:
- Trimmomatic (broken)
- Salmon (v. 1.4.0)
- R (v. 4.3)
- Bioconductor/BiocManager (v. 3.18)
- Tximport (v. 1.29)
- GenomicFeatures (v. 1.53)
- DESeq2 (v. 1.41)
- IsoformSwitchAnalyzeR (v. 1.99)

To perform this analysis you will need:
- At least 2 biological triplicates (three samples for each condition)
- A GTF file for the animal you are studying (or a related specie)
- Its corresponding cDNA transcripts file
  ## This two can be preferably obtained from ENSEMBL EBI.
