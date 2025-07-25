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

# Sunday, July 20th, 2025

## Discover
Researched on PCA subsections (pca8, pca30 etc) to convert the feature vectors of EMBER dataset.

## Investigate
After performing research on multiple subsections of PCA, it was found that pca30 will be a suitable approach to convert the feature vectors. It will reduce the feature vectors to 30 most important components. 

## Ponder
Pca30 is going to be a suitable approach because, it is reducing all the feature vectors to 30 most important components. In case of pca8, it will reduce to only 8 components.  As a result, substantial amount of information will be lost if pca30 is neglected. 


# Monday, July 21th, 2025

## Discover
Researched on pca30’s implementation to convert the feature vectors of EMBER dataset.

## Investigate
We can use pca30 feature reduction by importing from scikit learn library. To perform pca30 we have to perform a 5 step implementation which includes standardization, quantum normalization, pca transformation etc. 

## Ponder
If we perform the 5 step implementation then we should get the pca30 transformed reduced features of EMBER dataset

# Tuesday, July 22nd, 2025

## Discover
Compared the data preprocessing steps of EMBER dataset with Tak Hur’s MNIST and Fashion MNIST datasets QCNN classification. The code is available on GitHub repository. 

## Investigate
There was similarity between the selected steps of EMBER dataset classification and Tak Hur’s QCNN classification. Found that we do not need to convert the feature vectors into image for EMBER dataset. We can perform direct conversion of feature vectors to qubits. 

## Ponder
As there is similarity between the selected steps of EMBER dataset classification and Tak Hur’s QCNN classification, we can take inspiration about the preprocessing from it. Also, if we do not need to convert the feature vectors into image for EMBER dataset, we can save ourselves from some complex steps. 

# Wednesday, July 23rd, 2025

## Discover
Researched through the entire data preprocessing pipeline of EMBER dataset. Also, researched the working mechanism of the pre-processing pipeline.

## Investigate
After performing the research it was found that the data preprocessing pipeline of EMBER dataset is about six steps. The pre-processing steps include- data splitting, standardization, pca30 transformation etc. 

## Ponder
If we perform those six data pre-processing steps if would be able to convert the feature vectors and store the information to 8 qubits. Those 8 qubits will later be used for QCNN classification.


# Thursday, July 24th, 2025

## Discover
Researched on the coding steps of the finalized pre-processing pipeline of the EMBER dataset. The coding steps will represent the entire preprocessing pipeline of it.

## Investigate
The coding steps include six sections of data pre-processing stage. Each section have to be executed properly to get the 8 qubits which will used in QCNN classification. 

## Ponder
If we perform these 6 sections of coding steps to EMBER dataset’s feature vectors then we will be to get the qubits which we require for the QCNN architecture. We may perform a sanity visualization of pca30 reduction, if we need to verify the reduction process.