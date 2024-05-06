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
MSE:  0.0003
PSNR:  33.8577
GenomeDISCO:  0.919


chr 20 SSIM:  0.9062
MSE:  0.0003
PSNR:  34.8319
GenomeDISCO:  0.9157


Chr 21 SSIM:  0.9036
MSE:  0.0002
PSNR:  36.1269
GenomeDISCO:  0.9204


___________________________________________
Means across chromosomes

SSIM:  0.9056
MSE:  0.0003
PSNR:  35.1795
GenomeDISCO:  0.9186
___________________________________________

HiCARN 2

Chr 5 SSIM:  0.9109
MSE:  0.0002
PSNR:  35.9116
GenomeDISCO:  0.9179


Chr 14 SSIM:  0.9081
MSE:  0.0003
PSNR:  35.1704
GenomeDISCO:  0.9207


Chr 15 SSIM:  0.9001
MSE:  0.0003
PSNR:  33.901
GenomeDISCO:  0.9192


Chr 20 SSIM:  0.9064
MSE:  0.0003
PSNR:  34.831
GenomeDISCO:  0.916


Chr 21 SSIM:  0.9037
MSE:  0.0002
PSNR:  36.1139
GenomeDISCO:  0.9206


___________________________________________
Means across chromosomes

SSIM:  0.9058
MSE:  0.0003
PSNR:  35.1856
GenomeDISCO:  0.9189
___________________________________________

DeepHiC

Chr 5 SSIM:  0.8981
MSE:  0.0003
PSNR:  35.4141
GenomeDISCO:  0.9065


Chr 14 SSIM:  0.8942
MSE:  0.0003
PSNR:  34.6048
GenomeDISCO:  0.9097


Chr 15 SSIM:  0.884
MSE:  0.0004
PSNR:  33.1733
GenomeDISCO:  0.9074


Chr 20 SSIM:  0.8947
MSE:  0.0004
PSNR:  34.24
GenomeDISCO:  0.905


Chr 21 SSIM:  0.8921
MSE:  0.0003
PSNR:  35.6639
GenomeDISCO:  0.9103


___________________________________________
Means across chromosomes

SSIM:  0.8926
MSE:  0.0003
PSNR:  34.6192
GenomeDISCO:  0.9078
___________________________________________

HiCNN

Chr 5 SSIM:  0.9014
MSE:  0.0003
PSNR:  34.832
GenomeDISCO:  0.8993


Chr 14 SSIM:  0.8982
MSE:  0.0003
PSNR:  34.2842
GenomeDISCO:  0.9045


Chr 15 SSIM:  0.8693
MSE:  0.0005
PSNR:  31.2099
GenomeDISCO:  0.8989


Chr 20 SSIM:  0.8992
MSE:  0.0005
PSNR:  34.0096
GenomeDISCO:  0.9004


Chr 21 SSIM:  0.8962
MSE:  0.0003
PSNR:  35.4144
GenomeDISCO:  0.9049


___________________________________________
Means across chromosomes

SSIM:  0.8929
MSE:  0.0004
PSNR:  33.95
GenomeDISCO:  0.9016
___________________________________________

HiCPlus

Chr 5 SSIM:  0.879
MSE:  0.0006
PSNR:  32.2468
GenomeDISCO:  0.8816


Chr 14 SSIM:  0.8754
MSE:  0.0006
PSNR:  31.8515
GenomeDISCO:  0.8864


Chr 15 SSIM:  0.8383
MSE:  0.0009
PSNR:  29.1344
GenomeDISCO:  0.8801


Chr 20 SSIM:  0.8756
MSE:  0.0009
PSNR:  31.1508
GenomeDISCO:  0.8789


Chr 21 SSIM:  0.8729
MSE:  0.0006
PSNR:  32.5142
GenomeDISCO:  0.8858


___________________________________________
Means across chromosomes

SSIM:  0.8682
MSE:  0.0007
PSNR:  31.3795
GenomeDISCO:  0.8826
___________________________________________

HiCSR

Chr 5 SSIM:  0.9068
MSE:  0.0007
PSNR:  31.666
GenomeDISCO:  0.8796


Chr 14 SSIM:  0.9014
MSE:  0.0008
PSNR:  30.9673
GenomeDISCO:  0.8945


Chr 15 SSIM:  0.8562
MSE:  0.0009
PSNR:  29.8111
GenomeDISCO:  0.8251


Chr 20 SSIM:  0.9039
MSE:  0.0009
PSNR:  30.4618
GenomeDISCO:  0.8728


Chr 21 SSIM:  0.902
MSE:  0.0007
PSNR:  31.8795
GenomeDISCO:  0.9042


___________________________________________
Means across chromosomes

SSIM:  0.8941
MSE:  0.0008
PSNR:  30.9571
GenomeDISCO:  0.8752
___________________________________________
