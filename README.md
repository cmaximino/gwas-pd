# gwas-pd
Data packages for the research project "Exploratory analyses of GWAS data on PD"
The data shared here form the bases of a [metanalysis](metanalysis/README.md) of genome-wide association studies (GWAS) with patients with panic disorder. The metanalysis produced a [SNP list](metanalysis/metanalysis.csv) which was further analysed in R to produce a [candidate gene list](metanalysis/candidate_gene_table.csv). This candidate gene list was further compared with data retrieved from [GWASdb2](http://jjwanglab.org/gwasdb). The resulting [final list of candidate genes](candidate_genes.md) was analysed on the following databases:
* [PathwayLinker](https://pathwaylinker.org), producing [networks of interactors and a list of associated signaling pathways](pathwaylinker/report.pdf)
* [Brain RNA-Seq](https://web.stanford.edu/group/barres_lab/brain_rnaseq.html), producing [median values of RNA-Seq data for expression in mouse cortex](RNA-Seq/rnaseq.csv); these data were later processed via hierarchical cluster on [Cluster 3.0](http://bonsai.hgc.jp/~mdehoon/software/cluster/software.htm)
* [Allen Human Brain Atlas](http://human.brain-map.org/), producing [median values of microarray expression across 20 brain areas](Allen/coarse.csv); these data were also processed via hierarchical cluster
* [GeneNetwork / WebQTL](http://www.genenetwork.org/webqtl/main.py), producing [raw mRNA expression data](GeneNetwork/raw-expression), [correlation matrices](GeneNetwork/correlations), and [networks](GeneNetwork/networks) correlating behavioral data in BXD mice and mRNA levels of candidate genes in amygdala, hippocampus, prefrontal cortex, hypothalamus, and adrenal gland of mice.

[![DOI](https://zenodo.org/badge/113213690.svg)](https://zenodo.org/badge/latestdoi/113213690)
