# HSC_ML
### Classifying HSC sources using machine learing without spectra
These scripts explore galaxy/quasar/star classification from photometry sources from the HSC (Hyper Suprime-Cam) using machine learning.

I used matched sources with spectroscopically labelled sources from the Sloan Digital Sky Survey (SDSS) to train an optimised random forest classifier.

And also I used a non-linear dimension reduction technique (Uniform Manifold Approximation and Projection: UMAP) in fully-supervised schemes to visualise the separation of galaxies, quasars, and stars in a two-dimensional space.



My datasets can be found from here : 



### File Description
HSC_ML.ipynb
* Cleans data, builds random forest model

HSC_ML_analysis.ipynb
* Creates analysis plots using the output from HSC_ML.ipynb

HSC_classifynew.ipynb
* Classifies new sources without spectra, and makes plots assessing the output

HSC_UMAP
* Runs UMAP, and makes 2D plots

All Directories
* Place to save the data and the output
