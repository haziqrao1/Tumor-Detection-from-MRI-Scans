# Tumor-Detection-from-MRI-Scans
Introduction:
A brain tumor classification model has been developed by the team. The model is capable of detecting tumors from MRI scans with a high accuracy but not completely a hundred percent accuracy. This project was chosen with advancement of contributions of computer science in the medical field. Also the medical industry in Pakistan is a major market for such a model. Such models reduce costs and increase revenue for the medical industry by a significant degree.

Background:
Such classification models have been developed in recent times. The exact same model demonstrated great accuracy in China against a team of professionals. The doctors were able to detect tumors with a sixty two percent accuracy when compared with ninety percent accuracy of the machine learning model in 2019.

Reference:
https://www.youtube.com/watch?v=X5n2VR37IGthY

Project Specification:
The team had to develop a brain tumor classification model that scans an MRI scan and outputs whether the patient has a tumor or not. The team needs to extract features and feed the feature vectors to machine learning models. The models need to have an accuracy of at least eighty five percent. 
Three to four models are to be trained that are able to classify and then should be combined in an ensemble model as a voting system or voting classifier.

Solution Design:
The team has finalized HOG for feature extraction method and the following models for training
Support Vector Machine
KNN
Decision tree
Stochastic Gradient Descent

Ensemble voting classifiers will be used to combine all the models.

Implementation:
The team first entered the labels and preprocessed the images to a size and resized them according to the models that needed them for training.
Firstly no feature extraction was explicitly performed and the models were trained.
On SVM, we achieved an accuracy of 82 percent whereas KNN gave us 84 percent
The team then extracted features based on HOG technique and provided the feature vectors as input to the machine learning models. There was a significant increase in the accuracy of the models by a margin of 6-12% each.
The team then used ensemble voting classification to consolidate the results of the models and then saved the ensemble model using the pickle library.

Testing: 
The team tested the model on 20 percent of the initial dataset that was split in between training. After testing, we received variable accuracies of all models in between 88-94% ensemble included. Confusion matrix of the individual models are provided in the slides for your reference.

Project management: 
The dataset was obtained by the group leader and data preprocessing was done by Haziq Rao. The models of SVM and SGD were trained by haziq on both without feature extraction and HOG.
The models of KNN and Decision tree were trained by the leader M.Afaq with and without explicit feature extraction.

Conclusion:
The team has developed a good classification model with an accuracy of 84-92 percent while staying in the domain of machine learning. It is noteworthy that feature extraction if done explicitly increases the accuracy manifold in comparison to implicit feature extraction that is done by the models themselves.
Future Work:
Any kind of advancement in this project can be done through deep learning models such as VGG16, ResNet 50, and so on and so forth. The onus is on the developing engineers to expand their domain knowledge and pave the way for more accurate models that will reduce error rate and increase the probability of a successful diagnosis.
