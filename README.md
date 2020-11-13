# principal_component_analysis

Principal Component Analysis or PCA is used to reduce the number of features without the loss of too much information. 
The problem with having too many dimensions is that it makes it difficult to visualize the data and makes training models more computationally expensive.

How PCA works?
To analyse and build new dataset (reduced in dimensions) from original one by PCA, Following steps are used in general:

Calculate the covariance matrix of data
Calculate the eigenvalues and eigenvectors over covariance matrix
Choose the principal components
Construct new featured dataset from chosen components
