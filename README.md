# Image-Analysis-for-spatial-transcriptomic

Spatial transcriptomic is a method which allows to quantify the number of transcripts of a gene at a distinct spatial location in an intact tissue. One important step in ST analysis is identification of spatial domains coherent both in gene expression and histology analysis. The aim of my internship was to elucidate if the combination of these modalities provides relevant information for spatial domains partitioning. I compared the combination of these two modalities with gene expression alone. For this purpose, one H&E images preprocessing pipeline was created and used for the extraction of cell nuclei morphological features. To have a balance between the two modalities, a dimensionality reduction was applied on gene expression profiles. The clustering is realized for the two conditions compared with each other and compared with the ground truths of the datasets. The poor performance of our results does not allow us to conclude on the issue, but new tests will be done by implementing the data extracted from the images to existing tools for identifying spatial regions.

To reproduct the project you need :
- Preprocessing_H&E_remove_background.ipynb : the H&E image preprocessing pipeline 
- processing_visiopharm_output_clean.ipynb : visiopharm processing
- visiopharm_anndata.ipynb: cells attribution by spots
- autoencodeur_clean.ipynb : Dimensionality reduction by autoencoder
- merged_DR_morpho_features.ipynb : merged modalities
- ARI.ipynb : Clustering and ARI evaluation

These files are not necessary for the projet
- DBSCAN_morpho_features.ipynb
- Dimensionality_reduction.ipynb
- png_to_tiff.ipynb
