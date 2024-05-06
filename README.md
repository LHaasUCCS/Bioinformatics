# Bioinformatics
Using HiCARN for all models

had to set pool_num = 12 for my machine limitations on predict.py files.

# Sets
# ***********
  'train': [7, 8, 9, 12, 13, 16, 17, 18, 19],
  'valid': [4, 6, 10, 11, 22],
  'GM12878_test': (5, 14, 15, 20, 21)}

  Due to system limitations of 32GB of memory, had to ommit the first 3 chromosomes as well as shuffle the train/valid/test chromosomes around so that training set wasn't so large.



# RESULTS
# ******************

HiCARN 1

Chr 5 SSIM:  0.9107
MSE:  0.0002
PSNR:  35.9088
GenomeDISCO:  0.9177


Chr 14 SSIM:  0.9079
MSE:  0.0003
PSNR:  35.1723
GenomeDISCO:  0.9204


Chr 15 SSIM:  0.8998
Chr 15 MSE:  0.0003
Chr 15 PSNR:  33.8577
Chr 15 GenomeDISCO:  0.919


Chr 20 SSIM:  0.9062
Chr 20 MSE:  0.0003
Chr 20 PSNR:  34.8319
Chr 20 GenomeDISCO:  0.9157


Chr 21 SSIM:  0.9036
Chr 21 MSE:  0.0002
Chr 21 PSNR:  36.1269
Chr 21 GenomeDISCO:  0.9204


___________________________________________
Means across chromosomes

SSIM:  0.9056
MSE:  0.0003
PSNR:  35.1795
GenomeDISCO:  0.9186
___________________________________________

HiCARN 2

Chr 5 SSIM:  0.9109
Chr 5 MSE:  0.0002
Chr 5 PSNR:  35.9116
Chr 5 GenomeDISCO:  0.9179


Chr 14 SSIM:  0.9081
Chr 14 MSE:  0.0003
Chr 14 PSNR:  35.1704
Chr 14 GenomeDISCO:  0.9207


Chr 15 SSIM:  0.9001
Chr 15 MSE:  0.0003
Chr 15 PSNR:  33.901
Chr 15 GenomeDISCO:  0.9192


Chr 20 SSIM:  0.9064
Chr 20 MSE:  0.0003
Chr 20 PSNR:  34.831
Chr 20 GenomeDISCO:  0.916


Chr 21 SSIM:  0.9037
Chr 21 MSE:  0.0002
Chr 21 PSNR:  36.1139
Chr 21 GenomeDISCO:  0.9206


___________________________________________
Means across chromosomes

SSIM:  0.9058
MSE:  0.0003
PSNR:  35.1856
GenomeDISCO:  0.9189
___________________________________________

DeepHiC

Chr 5 SSIM:  0.8981
Chr 5 MSE:  0.0003
Chr 5 PSNR:  35.4141
Chr 5 GenomeDISCO:  0.9065


Chr 14 SSIM:  0.8942
Chr 14 MSE:  0.0003
Chr 14 PSNR:  34.6048
Chr 14 GenomeDISCO:  0.9097


Chr 15 SSIM:  0.884
Chr 15 MSE:  0.0004
Chr 15 PSNR:  33.1733
Chr 15 GenomeDISCO:  0.9074


Chr 20 SSIM:  0.8947
Chr 20 MSE:  0.0004
Chr 20 PSNR:  34.24
Chr 20 GenomeDISCO:  0.905


Chr 21 SSIM:  0.8921
Chr 21 MSE:  0.0003
Chr 21 PSNR:  35.6639
Chr 21 GenomeDISCO:  0.9103


___________________________________________
Means across chromosomes

SSIM:  0.8926
MSE:  0.0003
PSNR:  34.6192
GenomeDISCO:  0.9078
___________________________________________

HiCNN

Chr 5 SSIM:  0.9014
Chr 5 MSE:  0.0003
Chr 5 PSNR:  34.832
Chr 5 GenomeDISCO:  0.8993


Chr 14 SSIM:  0.8982
Chr 14 MSE:  0.0003
Chr 14 PSNR:  34.2842
Chr 14 GenomeDISCO:  0.9045


Chr 15 SSIM:  0.8693
Chr 15 MSE:  0.0005
Chr 15 PSNR:  31.2099
Chr 15 GenomeDISCO:  0.8989


Chr 20 SSIM:  0.8992
Chr 20 MSE:  0.0005
Chr 20 PSNR:  34.0096
Chr 20 GenomeDISCO:  0.9004


Chr 21 SSIM:  0.8962
Chr 21 MSE:  0.0003
Chr 21 PSNR:  35.4144
Chr 21 GenomeDISCO:  0.9049


___________________________________________
Means across chromosomes

SSIM:  0.8929
MSE:  0.0004
PSNR:  33.95
GenomeDISCO:  0.9016
___________________________________________

HiCPlus

Chr 5 SSIM:  0.879
Chr 5 MSE:  0.0006
Chr 5 PSNR:  32.2468
Chr 5 GenomeDISCO:  0.8816


Chr 14 SSIM:  0.8754
Chr 14 MSE:  0.0006
Chr 14 PSNR:  31.8515
Chr 14 GenomeDISCO:  0.8864


Chr 15 SSIM:  0.8383
Chr 15 MSE:  0.0009
Chr 15 PSNR:  29.1344
Chr 15 GenomeDISCO:  0.8801


Chr 20 SSIM:  0.8756
Chr 20 MSE:  0.0009
Chr 20 PSNR:  31.1508
Chr 20 GenomeDISCO:  0.8789


Chr 21 SSIM:  0.8729
Chr 21 MSE:  0.0006
Chr 21 PSNR:  32.5142
Chr 21 GenomeDISCO:  0.8858


___________________________________________
Means across chromosomes

SSIM:  0.8682
MSE:  0.0007
PSNR:  31.3795
GenomeDISCO:  0.8826
___________________________________________

HiCSR

Chr 5 SSIM:  0.9068
Chr 5 MSE:  0.0007
Chr 5 PSNR:  31.666
Chr 5 GenomeDISCO:  0.8796


Chr 14 SSIM:  0.9014
Chr 14 MSE:  0.0008
Chr 14 PSNR:  30.9673
Chr 14 GenomeDISCO:  0.8945


Chr 15 SSIM:  0.8562
Chr 15 MSE:  0.0009
Chr 15 PSNR:  29.8111
Chr 15 GenomeDISCO:  0.8251


Chr 20 SSIM:  0.9039
Chr 20 MSE:  0.0009
Chr 20 PSNR:  30.4618
Chr 20 GenomeDISCO:  0.8728


Chr 21 SSIM:  0.902
Chr 21 MSE:  0.0007
Chr 21 PSNR:  31.8795
Chr 21 GenomeDISCO:  0.9042


___________________________________________
Means across chromosomes

SSIM:  0.8941
MSE:  0.0008
PSNR:  30.9571
GenomeDISCO:  0.8752
___________________________________________
