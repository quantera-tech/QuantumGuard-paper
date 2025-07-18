# Tuesday, July 15th, 2025

## Discover
Researched on EMBER dataset and its ways of conversion to image data. EMBER dataset cannot be directly used in QCNN architecture. As a result, we need to transform those dataset to image data. EMBER dataset is available on Kaggle. PEMachineLearning which is a subset of EMBER dataset is available on M. Lester’s site.

## Investigate
It was found that EMBER dataset contains 2,351 feature vectors which have to be converted to image data. Also, found multiple conversion techniques – PCA, t-SNE, Histogram chart etc.

## Ponder
We have to select an efficient and suitable conversion technique among the suggested ones to convert the 2,351 feature vectors of EMBER dataset.


# Wednesday, July 16th, 2025

## Discover
Further researched on EMBER datasets ways of conversion as it cannot be directly used in QCNN architecture. Researched different ways of conversion of EMBER. It is crucial to discover an efficient approach for the overall performance of QCNN network.

## Investigate
Found 5 different types of approaches- PCA, t-SNE, Histogram chart, QR code, Autoencoders. It was found that each of the approaches has their own strength and drawbacks.

## Ponder
After studying the characteristics of all the 5 approaches PCA might be a suitable candidate for EMBER dataset conversion. Because, it is suitable for 8 qubits QCNN architecture which we will be using.


# Thursday, July 17th, 2025

## Discover
Researched on PCA data reduction approach to convert the feature vectors of EMBER dataset. Tried to understand the characteristics and working mechanism of PCA

## Investigate
It was found that PCA will be a suitable approach to convert the feature vectors of EMBER dataset. PCA performs data reduction and keeps the important features of all the feature vectors. There are subsections of PCA which are pca8, pca30 etc.

## Ponder
PCA data reduction approach perfectly fits for the QCNN architecture we will be using on our research. Also, it is considered to be a better approach in areas where we have limitations on the number of qubits we will be using.