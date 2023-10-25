### Principal Component Analysis
Principal component analysis, or PCA, is a dimensionality reduction method that is often used to reduce the dimensionality of large data sets, 
by transforming a large set of variables into a smaller one that still contains most of the information in the large set.

### Data
This is a copy of [https://goo.gl/U2Uwz2] (UCI ML Breast Cancer Wisconsin (Diagnostic) datasets). Features are computed from a digitized image of a fine needle
aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image.

### Source
The Project is one of the Capstone project given by Jose Portilla in his Machine Learning Course on [https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/](Udemy).

### How to run the project
To view this file:
1. Download this repository and unzip it
2. Download the Anaconda distribution of python
3. Launch a new Jupyter Notebook from Anaconda
4. Open the Loan-prediction.ipynb from the browser launch by Jupyter Notebook
5. Run all cells
6. Optional: If you don't have the libaries used install it using !pip install <name of the liberay you dont have>

### Steps
The dataset was loaded and explored. The feaure key contained information about the different features of the dataset while the target contained 2 categorical information which are whether the cancer is malignant or benign.
The data was then scaled so that the PCA model isn't affected by extreme values. The scaling model used is the Standard Scaler model. The PCA model was later used to extract the 2 main principal components from the dataset which turned out could be easily classified using the SVM model. 
Atthe end, a heatmap was plotted to visualise the linear combination of the different features.

### Findings
The PCA components are not exactly the features of the dataset. They are linear combinations of the original features and PCA is under a model call the single value decomposition. 
