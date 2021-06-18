# Metal-Glass-Classification
Pattern Recognition Final Project

## Dataset
Glass and Metal data has been taken from [Flickr Material Database (FMD)](http://people.csail.mit.edu/celiu/CVPR2010/FMD/index.html)
(Sharan, L., Rosenholtz, R., & Adelson, E. H. Material perception: What can you see in a brief glance? Journal of Vision, vol. 14, no. 9, article 12, 2014)

For pre-processing, the masks that are given in the dataset are applied to the original images. 

Gray Level Co-occurence Matrix (GLCM) has been used for feature extraction.

Additionally, in the code there is a PCA trial for feature extraction which is deemed unnecessary but the code is left in the Jupyter notebook for the sake of feature extraction trials. Random decision forest is used for classification.