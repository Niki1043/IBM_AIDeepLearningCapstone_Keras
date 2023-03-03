# IBM_AIDeepLearningCapstone_Keras

# Project Description
Build an image classifier using the VGG16 pre-trained model and evaluate it's performance
Compare it's performance to a ResNet50 pre-trained which was built in other coursework

# Project Techonologies and Techniques
**Data Collection**
- wget API request for train, validation and test data sets

**Design Classifier using VGG16 pre-trained model**
- Construct ImageDataGenerators for training and validation datasets
- Create sequential Keras model with VGG16 model and dense layer
- Compile and fit model

**Evaluate VGG16 and ResNet50 pre-trained models with test data**
- Construct ImageDataGenerators for test dataset
- Evaluate models using evaluate_generator method
- Output performance for each model

**Predict class of test data inputs**
- Predict test image class using predict_generator method
- Output predictions for each model


# Conclusion
- Resnet50 had similar accuracy to VGG16 but with lower loss, indicating it's predicted output class was comparable to the actual data class



# Link to Data Science Capstone Presentation and Jupyter Notebooks
[Link to Capstone Jupyter Notebook](https://github.com/Niki1043/IBM_AIDeepLearningCapstone_Keras/blob/main/NPatel_Keras_AIEng%20(2).ipynb)




