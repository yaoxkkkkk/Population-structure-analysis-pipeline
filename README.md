# Population structure analysis pipeline
A pipeline uses SNP vcf file to conduct population structure analysis. 

## Dependent software/script
- PLINK
- VCF2PCACluster
- ADMIXTURE
- FastTree
- VCFtools
- bgzip
- [vcf2phylip](https://github.com/edgardomortiz/vcf2phylip)

## What the pipeline does
- SNP vcf convert to plink format
- SNP pruned according to LD block
- PCA cluster
- ADMIXTURE analysis
- Phylogenic tree construction

## What to input
Just vcf file containing your population variant information.
> Since ADMIXTURE only accpets vcf file with integer format chromosome ID (e.g. 01 for Chr01), so please remeber modify your file.

## What to output
