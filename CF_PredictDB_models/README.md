These are predictive models of genetically regulated gene expression from cis-SNPs within 1 Mbase flanking the genes derived from Cystic Fibrosis patients' training data sets according to the PredictDB GTEx release v7 pipeline (https://github.com/hakyimlab/PredictDB_Pipeline_GTEx_v7).

  * The models are stored in SQLite3 database files (.db), and the filtered predictive models for predictable gene models (following filtering criteria by GTEx7_predictDB_pipeline) are named _signif.db.
  * Corresponding gene lists and annotations were saved as text tables for convenience formatting analysis results.
  * Covariance matrices of cis-SNPs among the training data were saved as text tables in compressed gzip (.gz) files. These maybe used for adjustment of LD structures and haplotypes among SNPs.
