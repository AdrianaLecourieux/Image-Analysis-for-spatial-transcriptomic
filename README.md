# Image Analysis for spatial transcriptomic

This repository contains all the scripts I realized during my end-of-studies internship at Servier Institut (6 months). I worked on images and data from spatial transcriptomic experiments (Visium 10X Genomics).

## Project summary
Spatial transcriptomic (ST) is a method which allows to quantify the number of transcripts of a gene at a distinct spatial location in an intact tissue. One important step in ST analysis is identification of spatial domains coherent both in gene expression and histology analysis. The aim of my internship was to elucidate if the combination of these modalities provides relevant information for spatial domains partitioning. I compared the combination of these two modalities with gene expression alone. For this purpose, one H&E images preprocessing pipeline was created and used for the extraction of cell nuclei morphological features. To have a balance between the two modalities, a dimensionality reduction was applied on gene expression profiles. The clustering is realized for the two conditions compared with each other and compared with the ground truths of the datasets. The poor performance of our results does not allow us to conclude on the issue, but new tests will be done by implementing the data extracted from the images to existing tools for identifying spatial regions.

## Project structure

Four directories are present in the repository and three of them contains notebooks :
- **analysis** : contains tools or methods I used for my project
- **tests** : contains tools or methods that I tested but did not use for my project
- **other** : containes one script which convert h5 data to H5AD format and one scrit which normalize H&E images
- **src** : contains the bibliography I did during my internship (ST, image analysis, methods)

