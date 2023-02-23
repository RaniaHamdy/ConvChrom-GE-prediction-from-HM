# Reference Paper: [ConvChrome: Predicting Gene Expression Based on Histone Modifications Using Deep Learning Techniques] (https://www.eurekaselect.com/article/119403)

ConvChrome use a well-known deep learning technique called Convolution Neural Network (CNN) to predict gene expression from histone modification to learn how Combinatorial Histone Modifications Effects Gene Regulation. Using many variations convolutional models to find the best model, Coordination among CNN layers by Using many convolutional layers stacked on top of each other helps in the learning and extraction of useful features aims to recognize more complex patterns, also can give more abstract and in-depth information from a CNN and to reduce computational time.

# Dataset 
ConvChrome used dataset from Roadmap Epigenomics Mapping Consortium (REMC) database from the Roadmap Epigenomics Projects but used after preprocessing from another previous work mentioned in the paper, 
The dataset can be downloaded from this [repository](https://github.com/ly-zhu/CRNN-gene-expression-with-histone-modifications)


__variation convolutional models__
* CNN1D
* CNN1D_att
* CNN2D

The ConvChrome found that CNN1D proposed model get the highest between the models AUC score with an average of 0.8874. 

__architecture of CNN1D__

![Image of CNN1D model from ConvChrom](https://github.com/RaniaHamdy/ConvChrom-GE-prediction-from-HM/blob/master/CNN1D%20model%20.png)

# Running The Model Script

you can try see [ConvChrom](https://github.com/RaniaHamdy/ConvChrom-GE-prediction-from-HM/blob/master/CNN_Model_Variations.ipynb) architecture.  

# Citation
Hamdy Rania *, Maghraby A. Fahima*, Omar M.K. Yasser, ConvChrome: Predicting Gene Expression Based on Histone Modifications Using Deep Learning Techniques, Current Bioinformatics 2022; 17(3). https://dx.doi.org/10.2174/1574893616666211214110625
![image](https://user-images.githubusercontent.com/37738411/220832999-07cb188d-d01a-4ee4-8859-23cd33275cde.png)
