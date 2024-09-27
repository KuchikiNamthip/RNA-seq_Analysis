# Transcriptomics_note
## Tutorial and course
- NIH/NCI: [Bioinformatics Training and Education Program by BioStar](https://bioinformatics.ccr.cancer.gov/docs/b4b/)
- [Computational Genomics with R](https://compgenomr.github.io/book/)
  
## Downstream tools
- [Biomedical Knowledge Mining using GOSemSim and clusterProfiler](http://yulab-smu.top/biomedical-knowledge-mining-book/index.html)
- [Rafael Irizarry lab](http://rafalab.dfci.harvard.edu/)
- [Saez-Rodriguez Group](https://saezlab.org/?#research)
- [X. Shirley Liu lab](https://liulab-dfci.github.io/software/)
- [Ma'ayan lab](https://labs.icahn.mssm.edu/maayanlab/research/)
  
## P-value distribution issue
- Genes with low counts interfere with the p-value distribution, so removing those genes and re-observe the distribution. [Ref](https://divingintogeneticsandgenomics.com/post/downstream-of-bulk-rnaseq-read-in-salmon-output-using-tximport-and-then-deseq2/)


## Genes selection
- RNA-seq included many [types of RNA (GENETYPE)](https://asia.ensembl.org/info/genome/genebuild/biotypes.html). We typically want protein-coding genes, so we need to [filter only those](https://support.bioconductor.org/p/124462/) using [the annotation package](https://hbctraining.github.io/DGE_workshop_salmon_online/lessons/AnnotationDbi_lesson.html) to identify it.
