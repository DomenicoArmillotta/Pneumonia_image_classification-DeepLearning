# Pneumonia_image_classification-DeepLearning
1.  Pre-processing phase and retrieval of images that were already divided into Train,Test,Validation set folders.
Put into np array with image-label


2.  Created class_weight class to give more importance to classes with few elements in the training phase. 
As the dataset was unbalanced.


3 models were trained : 



##ALEXNET from scratch : 

- overfitted

- accuracy 80%

##MNIST from scratch : 

- overfitted

- accuracy 88%


##EfficientNet Feature extraction preTrained : 

- accuracy 38%


The dataset is too small, so even using overfitting reduction techniques results in unusable models.
Techniques used : 
- multiple dropout layer 
- Augmentation for the training phase


