# Project: Chest-Cancer-Prediction
# Problem Statement
Cancer Prediction using Computer Vision Model(VGG16 & InceptionV3)
# Need
Cancer is a dreadful disease and millions of people die every year. It is very essential for medical practitioners to opt a proper treatment for cancer patients. Therefore cancer cells should be identified correctly.This software system is made to predict cancer accurately and is user friendly, cost effective and is an effective approach for doctors. We have used an convular neural network that uses a connectionist approach to process information for computation. Convular neural network had been proven a very effective method for pattern recognition. This made them very useful for the diagnosis of cancer disease at very early stages. 
# Target
Our system software makes it more efficient for cancer specialists worldwide to predict cancer at a really early stage hence helping patients to recover faster and helping scientists to make a more reliable solution.Our software is directed to medical professionals specializing in cancer and its various diseases. Its also directed towards people who have been determined to be at risk for the disease.Market growth in machine learning projects refers to the expected increase in demand for machine learning products and services over time. 
# Solution Details
We have a dataset of Chest Cancer consisting of three types of Chest Cancers:

1)Adenocarcinoma:Adenocarcinoma is a type of cancer. It develops in the glands that line your organs.

2)Large cell carcinoma:Large cell carcinoma can appear in any part of the lung. It tends to grow and spread quickly, which can make it harder to treat.

3)Squamous cell carcinoma:Squamous cell carcinoma of the skin is a common form of skin cancer that develops in the squamous cells that make up the middle and outer layers of the skin.

The Dataset contains 617 training images, 315 testing images and 72 validation images.
# Information of Pre-Trained Models
1)VGG-16: VGG16 is a convolutional neural network trained on a subset of the ImageNet dataset, VGG16, as its name suggests, is a 16-layer deep neural network. VGG16 is thus a relatively extensive network with a total of 138 million parameters—it’s huge even by today’s standards. However, the simplicity of the VGGNet16 architecture is its main attraction.

![image](https://github.com/Akanksha-neural-networks/Chest-Cancer-Prediction/assets/101962662/c845b837-492f-4c6d-bc30-1d81247c7cc9)

2)InceptionV3: Inception v3 is an image recognition model that has been shown to attain greater than 78.1% accuracy on the ImageNet dataset. The model is the culmination of many ideas developed by multiple researchers over the years.
The inception V3 is a superior version of the basic model Inception V1 which was introduced as GoogLeNet in 2014. As the name suggests it was developed by a team at Google.

![image](https://github.com/Akanksha-neural-networks/Chest-Cancer-Prediction/assets/101962662/ad2fbb4e-b035-4307-80ee-5f515768d0b9)
# Flowchart

![image](https://github.com/Akanksha-neural-networks/Chest-Cancer-Prediction/assets/101962662/178a1b39-ce02-4302-b088-13c814385ae6)

# VGG 16 Results
Metrics(Accuracy, Loss, Recall, F1-Score and AUC) Graphs

![image](https://github.com/Akanksha-neural-networks/Chest-Cancer-Prediction/assets/101962662/fb4b2978-a2d4-4c14-99a9-0b7201664809)

Accuracy graphs depict the number of correct predictions, Loss graphs contain the values depicting the difference between desired targets.

1)loss: 2.4178 

2)accuracy: 0.6056

3)precision: 0.1862 

4)recall: 0.1714 

5)f1_score: 0.1757  
# Technologies Required
1)Numpy and Pandas

2)Matplotlib and Seaborn

3)Tensorflow

4)Keras

5)Google Collab

6)Sklearn Library

7)TypeGuard
# Installations
1)Download Anaconda

2)To run the notebook: jupyter notebook

3)pip install numpy pandas seaborn matplotlib scikit-image os-tf tqdm glob3 tensorflow keras typeguard typing
# Future Readiness

We collected various data sets of cancer cells from various platforms providing open-source datasets and developed a detailed list of the features that the system software would contain. We did not need to clean the datasets as we didn’t have any missing values in our datasets and then we loaded them onto the platform we are working on. In machine learning, an epoch refers to a complete iteration through a training dataset during the training process of a neural network so we used the epoch method to increase the accuracy of the software.For Future reference we can also build a software through Gradio or Flask to further develop the Model into a Web Application or an Interface.
# Youtube Link
https://youtu.be/VOHZYMVQ9io
