# HSC_ML
### Classifying HSC sources using machine learning without spectra
These scripts explore galaxy/quasar/star classification from photometric sources observed from the HSC (Hyper Suprime-Cam) using machine learning.

I used matched sources with spectroscopically labelled sources from the SDSS (Sloan Digital Sky Survey) to train an optimised random forest classifier.

Finally I used a non-linear dimension reduction technique (Uniform Manifold Approximation and Projection: UMAP) in fully-supervised schemes to visualise the separation of galaxies, quasars, and stars in a two-dimensional space.



My datasets can be found from here : 



### File Description
HSC_ML.ipynb
* Cleans data and builds random forest model

HSC_ML_analysis.ipynb
* Creates analysis plots using the output from HSC_ML.ipynb

HSC_classifynew.ipynb
* Classifies new sources without spectra and generates plots assessing the output

HSC_UMAP.ipynb
* Runs UMAP and generates 2D plots

All Directories
* A location to save the data and the output

> [!IMPORTANT]
> Python Environment  
> HSC_ML.ipynb, HSC_ML_analysis.ipynb, and HSC_classifynew.ipynb : Python3.6.13  
> HSC_UMAP.ipynb : Python 3.8.18  


### Reference
"Identifying galaxies, quasars, and stars with machine learning: A new catalog of classifications for 111 million SDSS sources without spectra" (Clarke et al. 2020, A&A, 639, A84)
