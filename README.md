# CMPE_256-Fashion_Reccomendation_System
Panache
# A Fashion Recommendation System
CMPE 256 Project Proposal
-By
-Team 8
-Reshma Krishnakumar Parakkal (015326454)
-Shiyon Kurian (015351297)
-Sparsha Ramakrishna (015274571)
Project Advisor
Professor Gheorghi Guzun
Date: 04/05/2022
# Project Goal:
This project intends to create a visual image-based recommendation system for e-commerce platforms in order to deliver a personal and unique fashion experience. The project uses Reverse Image Search, which is extensively utilized in e-commerce websites like Amazon, Shein, and Pinterest.
# Dataset Requirements:
Kaggle provided the data for this project. Each product is given a unique identifier. It contains properties such as gender, classification, style, color and seasonality, which offer a description of the product and help classify it for feature recognition. The dataset is 593 megabytes in size.
Dataset link: https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small
# Methods and Algorithms:
Deep learning methods will be used to build the Recommender System. For evaluating visual information, the Convolutional Neural Network (CNN) is a common choice. We mostly employ Convolutional Neural Network (CNN) and Transfer Learning for feature extraction. Convolutional neural networks are made up of many layers of artificial neurons. The picture is put into multiple layers, each of which serves a particular purpose. The very first layer searches for rudimentary characteristics. The layers search for more complicated traits as they go. Each picture's retrieved features are then given to the ResNet model, which creates a collection of features for every picture. The Nearest Neighbors method, which is used in pattern classification and data mining, is used to identify the best product suggestions.
# Proposal Planning:
Our approach involves the below steps:
# Import the Model:
The model that we are using, as discussed already is the Convolutional Neural Network (CNN) model. The ResNet is a CNN architecture and is a high performing CNN model. The initial step involves loading the ResNet model. This eliminates the need to train the data. This will help in cutting down the downtime taken to train data as well as improves the accuracy as reliable and previously tested models are used.
# Feature Extraction:
The next step in the process would be feature extraction. CNN has various layers; at each layer the feature is extracted. As the image is processed through these layers, the complexity of the features extracted improves. Features in this image is the smallest details of the picture. The project deals with images and hence extracting features from these images with great accuracy improves the accuracy of the recommender system as well.
# Export Features:
The extracted features from the image dataset are saved as vectors.
# Generate Recommendations:
The final step of the approach calls for generating recommendations based on the image provided as input. The image inputted is saved as vector and using the Nearest Neighbor method we calculate the Euclidean distance with the other vectors. The top five closest vectors can be outputted as the result.
