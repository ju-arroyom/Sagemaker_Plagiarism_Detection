# Sagemaker_Plagiarism_Detection
This repo is based on one of the projects I worked on while taking Udacity'st ML Engineer Nanodegree.

The goal was to build a plagiarism detector in **Sagemaker** that examines an answer text file and performs binary classification. In order to achieve this, it was necessary to transform the raw text files into meaningful features that would capture the degree of similarity between the answer text and a particular source text (See **2_Plagiarism_Feature_Engineering** notebook for a detailed description). 

As mentioned before, the task of the classifier is to label the answer file as plagiarized or not depending how similar the text file is to a provided, source text. The code for this part can be found in the **3_Training_a_Model** notebook, which trains and deploys an sklearn classifier on Sagemaker.