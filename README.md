# Transcriptomics_note
## P-value distribution issue
- Genes with low counts interfere with the p-value distribution, so removing those genes and re-observe the distribution. [Ref](https://divingintogeneticsandgenomics.com/post/downstream-of-bulk-rnaseq-read-in-salmon-output-using-tximport-and-then-deseq2/)

## Genes selection
- RNA-seq included many [types of RNA (GENETYPE)](https://asia.ensembl.org/info/genome/genebuild/biotypes.html). We typically want protein-coding genes, so we need to [filter only those](https://support.bioconductor.org/p/124462/) using [the annotation package](https://hbctraining.github.io/DGE_workshop_salmon_online/lessons/AnnotationDbi_lesson.html) to identify it.
