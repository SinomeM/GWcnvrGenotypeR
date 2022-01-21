# README

GWcnvGenotypeR (Genome Wide CNV regions genotyper) is an R packege that implements 
alogorithms to precisely genotype CNVR in the human genome from SNP array data of
reasonably large cohort.

The results is a file resembling a VCF of CNV Regions found in the dataset. Each
sample will have a genotype for each CNVR (normal CN/deletion/duplication)
and a confidence score/probability attached to it.

Each genotype is validated using a series of iterative algorithms in order to
extract the most from the inital raw data and avoid the need of visual inspection.
