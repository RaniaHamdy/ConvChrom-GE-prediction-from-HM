# ConvChrome:predicting gene expression based on histone modifications using deep learning techniques 
ConvChrome use a well-known deep learning technique called Convolution Neural Network (CNN)  to predict gene expression from histone modification to learn how Combinatorial Histone Modifications Effects Gene Regulation. Using many variation convolutional models to find the best model, Coordination among CNN layers  by Using many convolutional layers stacked on top of each other helps in the learning and extraction of useful features aims to recognize more complex patterns, also can give more abstract and in-depth information from a CNNand to reduce computational time
ConvChrome used datase from Roadmap Epigenomics Mapping Consortium (REMC) database from the Roadmap Epigenomics Projects but used after preprocessing from anoher previous work mention in the paper 

__variation convolutional models__
* CNN1D
* CNN1D_att
* CNN2D

The ConvChrome  found that CNN1D proposed model get the highest between the models AUC score with an average of 0.8874 

__architecture of CNN1D__

![Image of CNN1D model from ConvChrom](https://github.com/RaniaHamdy/ConvChrom-GE-prediction-from-HM/blob/master/CNN1D%20model%20.png)

# Running The Model Script

you can try see [ConvChrom](https://github.com/RaniaHamdy/ConvChrom-GE-prediction-from-HM/blob/master/CNN_Model_Variations.ipynb) architecture  

# Citation
