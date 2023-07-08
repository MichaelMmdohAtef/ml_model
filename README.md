# Tradational nd Dilated CNN
we use Architecture used in the upper Paper in different dataset to explain the different models acheive a different accuracy
# Dataset
 ### about Traffic Sign Classification and Recognition
#### Link: https://www.kaggle.com/datasets/wjybuqi/traffic-sign-classification-and-recognition
This data set contains 6358 manually labeled category labels. The labels include the following 10 categories: “GuideSign” , “M1”, “M4, “M5”, “M6”, “M7”, “P1”, 
“P10_50”, “P12”, “W1”, corresponding to ten Different traffic sign categories .The data set contains one folders include 6358 images, and in the model separate it 
into training, validation, and testing.
Traffic light classification is the process of automatically identifying traffic lights along a road, including speed limit signs (label in dataset P10_50), start 
signs (label in dataset m1), merging signs (label M4), and signs for people walking (label in dataset m7), no-parking signs(label in dataset p1),etc. The ability to 
Automatically recognize traffic lights .

# implementation
#### Ratio used for training : 4062
#### Ratio used for Validation : 1270
#### Ratio used for testing : 1016
#### hyperparameters used in your model : 
                                                          Adam (Learning rate =0.001)
                                                          Droupout (0.25)
                                                          Epochs :35
                                                          BatchSize=32
                                                          Adding additional hidden layer
                                                          Activation =relu
                                                          Use_Validation .20 of dataset
                                                          Increasing # of units in hidden layer to 128


