# Prediction-of-Covid-19-using-Chest-images

# Introduction
Globally, the new coronavirus illness 2019 (COVID-19) represents a public health emergency. Every day, the number of sick persons and deaths grows, putting immense strain on our social and healthcare systems. COVID-19 cases must be diagnosed quickly to battle the virus and relieve the burden on the healthcare system.
The chest X-ray was the first imaging procedure that was used in the treatment of COVID-19. The use of radiological imaging to emphasise the performance of chest X-rays is common. COVID-19 has been found in patients with abnormal results on chest X-rays, according to new research. Machine learning algorithms for detecting COVID-19 using chest X-rays are included in several studies on this issue.
There are right now 269,993,520 affirmed cases in 222 nations and regions . The casualty rate is as yet being evaluated. Many researchers have worked on covid prediction in recent years, employing various machine learning techniques such as Logistic Regression (LR), Random Forest (RF), Decision Tree (DT), K-Nearest Neighbour (KNN), Artificial Neural Network (ANN), Support Vector Machine (SVM), Xgboost (XGB), Naive Bayes, and others. In this paper, we describe a model that combines data preprocessing and scaling approaches to clean the dataset, different classifiers applied to this dataset, and obtained the highest accuracy of 99.86 percent and Roc AUC of 99.86 percent by applying K-Nearest Neighbour over the test data.

# Documentation
One can find out more about the machine learning algorithms used to predict the sovid-19 using chest images in the https://github.com/shubham20315/Prediction-of-Covid-19-using-Chest-images/blob/main/Covid-19%20Prediction.pdf and you can also find our working model at https://covid-india-working-app.herokuapp.com/ here you can upload a chest image in jpeg format and it will provide you the information wether the image is of a covid patient or not.

# Dataset Description 
We have worked on the covid prediction dataset that we have acquired from github [15]. The dataset consists of 5184 total images in which we have taken 2084 images for training and 3100 images for Testing purposes. In training we have used 84 images for Covid and 2000 images for Non-Covid. In testing we have taken 100 images for Covid and 3000 images for Non-Covid.
 1) The Dataset link is as follows https://drive.google.com/drive/folders/1PQyLPCZvwN1T6NopAiAHA9O-q5SpgHNH?usp=sharing

# Installation of Prediction Model
# Prerequisite
One needs Python 3.6 with standard libraries such as pandas, matplotlib, seaborn, numpy, sklearn, keras and tensorflow.
# Steps to run the code
1) Download the code using https://github.com/shubham20315/Prediction-of-Covid-19-using-Chest-images/blob/main/Covid_19_detection_Final_Code.ipynb
2) Downlaod the dataset using https://drive.google.com/drive/folders/1PQyLPCZvwN1T6NopAiAHA9O-q5SpgHNH?usp=sharing
3) You can run the code in your local machine having python 3.6 and libraries or you can use the Google Collab for running code without any difficulty.
