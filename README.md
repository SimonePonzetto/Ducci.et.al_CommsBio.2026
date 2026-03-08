# PaperDucciReview
Corroborative bioinformatic analyses for Paper review (Ducci G. et al.)

for now the repository includes:
1) Differential expression analysis and GSEA on Lab cell line panel (Bulk RNA Seq of cell lines monolayers)

2) Differential expression analysis and GSEA on URINARY_TRACT cell lines from CCLE dataset (considering 17 relevant cell lines)

3) Differential expression analysis and GSEA on TCGA - BLCA (2017) Dataset

4) Differential expression analysis and GSEA on Merged datasets (LabCL and CCLE)

regarding the latter, PCA is clearly showing, as expected, batch effects between the datasets urging the need for batch correction approach. for Now DESeq2 batch handling has been adopted; Possibly more robust methods could yield more satisfactory results, but in this context, it is deemed sufficient to consider separate analyses for validation of the observed enrichment results without introducing unnecessary mathematical correction.