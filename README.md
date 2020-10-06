# Breast Cancer Detection (IDC) Using CNN

## The dataset user

The datset used in traing the model is from [Kaggle](https://www.kaggle.com/)

The dataset used is [Breast Histopathology Images](https://www.kaggle.com/paultimothymooney/breast-histopathology-images)

## Context

Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers. To assign an aggressiveness grade to a whole mount sample, pathologists typically focus on the regions which contain the IDC. As a result, one of the common pre-processing steps for automatic aggressiveness grading is to delineate the exact regions of IDC inside of a whole mount slide

## Inspiration

This was a project assigned to me by my Machine Learning Professor for my end of the semester project. Looking into this matter I found out it is a diffiluct and long processes for pathologists to examine each tissue slide.

This model will make the process of classifying tissue samples more efficient for the pathologists.

## Overview

The goal is to create a deep learning model that can be used to ease the work of the pathologist so that they can check the tissue samples in greater batches and in a more efficient manner.

This requires the model to be highly accurate i.e. above 85% accuracy and have good recall in both negative and postive classes.

## About Invasive Ductal Carcinoma(IDC)

<a title="Mikael Häggström, M.D. - Author info - Reusing images [CC BY (https://creativecommons.org/licenses/by/2.5)]" href="https://commons.wikimedia.org/wiki/File:Lobules_and_ducts_of_the_breast.jpg"><img width="309" alt="Lobules and ducts of the breast" style="float:left; margin:0px 15px 15px 15px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Lobules_and_ducts_of_the_breast.jpg/256px-Lobules_and_ducts_of_the_breast.jpg"></a>

This illustration created [Mikael Häggström](https://commons.wikimedia.org/wiki/File:Lobules_and_ducts_of_the_breast.jpg) shows the anatomy of a healthy breast. One can see the lobules, the glands that can produce milk which flews through the milk ducts. Ductal carcinoma starts to develop in the ducts whereas lobular carcinoma has its origin in the lobules. Invasive carcinoma is able to leave its initial tissue compartment and can form metastases.
