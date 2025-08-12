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


# Sunday, July 27th, 2025

## Discover
Researched through the data pre-processing pipeline of BODMAS dataset. The data pre-processing is some extent complicated which is unlike to EMBER dataset.

## Investigate
The pre-processing pipeline of BODMAS dataset includes two major stage: 1) Conversion of PE files to image 2) Conversion of image to qubits. As PE files consists of multiple sections (.text, .data, .rdata etc.) it have to be processed individually using LIEF. 

## Ponder
The individual sections of PE files have to be pre-processed separately. Also, there might be some PE files which may not all the required sections. As a result, those empty sections have to be handled carefully.


# Monday, July 28th, 2025

## Discover
Continued to Research on data pre-processing pipeline of BODMAS dataset. Researched on the two major stage of data pre-processing of BODMAS dataset.

## Investigate
In the first stage of preprocessing pipeline we have to apply LIEF library. It will be applied on each of the PE files of BODMAS dataset. After the extraction we will get 5 different sections which includes .text, .data, rdata etc. Each of the sections will be converted into an image. As a result, one PE file equal to 5 images (if all of the sections present). In the second stage those images will be converted into qubits. 

## Ponder
In case of extraction of sections from the PE files, we will be focusing on mainly: .text, .data, .rdata, .rsrc and .reloc. In the first stage, the pre-processing may be a bit challenging, as we have to handle those 5 sections of images differently. 



# Tuesday, July 29th, 2025

## Discover
Researched on the first stage of data pre-processing of BODMAS dataset and gathered knowledge of the steps of pre-processing pipeline.  

## Investigate
We have selected 5 different sections of the PE files of BODMAS dataset. Each of these sections will get trained individually on QCNN architecture. As a result, there will be 5 different sections of 8x8 images.  

## Ponder
The 5 different sections of images will be a 2D representation of the grayscale values generated form the sections. These image is going to get used in the second stage of data pre-processing of BODMAS dataset. 


# Wednesday, July 30th, 2025

## Discover
Researched on the coding steps of first stage of data pre-processing pipeline of BODMAS dataset.  

## Investigate
The coding steps of the pre-processing pipeline includes three crucial phase: 1) PE file parsing with LIEF 2) Target section identification 3) Section content conversion to 8x8 image.

## Ponder
If the three important steps of the first stage of the data pre-processing of BODMAS dataset are followed, then we would be able to get 8x8 image of the sections of PE files. Afterwards we can proceed to the second stage of pre-processing pipeline. 


# Thursday, July 31th, 2025

## Discover
Researched on the relation between SHA-256 with EMBER and BODMAS dataset. Researched on the characteristics of the SHA-256 hash. 

## Investigate
SHA-256 is a cybersecurity practice which acts as a digital fingerprint. It is useful for its unique sample identification, data integrity verification etc. The SHA-256 hash are provided alongside with the PE files and it is absent on feature vectors dataset.

## Ponder
As SHA-256 is provided with the binary PE files of BODMAS and EMBER dataset, its guarantees data integrity verification, unique sample identification, scientific validation etc. As a result, it is going to be an effective approach, if binary PE files get used instead of feature vectors. 


# Sunday, August 3rd, 2025

## Discover
Researched on the coding steps of 2nd stage of data pre-processing BODMAS dataset. Focused on the initialization of pca30 transformation of each section’s images, reshape into 8x8 images and pca30 model training on each sections data. 

## Investigate
The 64 pixel grayscale values would be reshaped into 8x8 images. Afterwards, those images will be flattened and trained using pca30 model for each sections. Then pca30 transformation will be applied and reduced into 30 features.

## Ponder
The application and pca30 model training might be a bit challenging for each of the PE file sections. The 85% variance threshold has been set up to ensure the preservation of the data’s variability.

# Monday, August 4th, 2025

## Discover
Researched on the coding steps of 2nd stage of data pre-processing BODMAS dataset. Focused on the angular hybrid embedding to the reduced pca30 features images and conversion into 8 qubits. 

## Investigate
The angular hybrid embedding maps the vector of pca30 features efficiently onto a quantum state using a specified number of qubits and a mixture of angular gates and entanglement patterns. In this case, the pca30 features are converted into 8 qubits.

## Ponder
The angular hybrid embedding technique is used to convert the pca30 into quantum states, due to its efficient use of qubits for high dimensional data. Also, it provides increased entanglement and has a better utilization of the NISQ-era devices.


# Tuesday, August 11th, 2025

## Discover
Executed the coding steps of feature vectors data pre-processing of BODMAS and EMBER dataset. 

## Investigate
After conducting several iterative trials and adjustments, up to PCA30 the notebook code cells got executed: load parquet feature vectors, data cleaning, Train/test split, Standardization. While executing the PCA30 the session got crashed due to limited amount of RAM storage.

## Ponder
To execute the PCA30 transformation of those pre-processed feature vectors 16 GB of RAM capacity was insufficient. Therefore, high RAM capacity is essential to execute the PCA30 transformation cell block. 
