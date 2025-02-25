# Project Title: ECG Deep-Diagnosis & Report Generation System.  

## Overview:  
In this Project, we have developed an AI app which processes 12 Lead ECG sensor data, auto-diagnose the heart diseases or conditions thorugh deep learning model, and then utilize LLM (gpt-4o-mini) to generate simple ECG reports explaining the diagnosed heart conditions and recommendations for user understanding.  

## Technologies Used:  
- Deep Learning with tensorflow for building model
- gpt-40-mini for report generation
- streamlit libraries for building dashboard app

## Instructions to Run the code:  
- In CLI, type streamlite run inference.py
- If you want to generate reports, must add api key in the beginning of the code, it was removed for security purposes.
- x10 12 Lead Ecg signals, preserved in .mat files showing sensor data are in data folder. Any of these files can be used to test system. 
- 
##### Dataset: Authentic real-world data from Phyionet[A large scale 12-lead electrocardiogram database for arrhythmia study], link : https://physionet.org/content/ecg-arrhythmia/1.0.0/WFDBRecords/01/010/#files-panel  

##### Model: The proposed algorithm for classifying 12-lead ECG with multi-labeling consists of components of data denoising, framing blocking, and dataset balance for data preprocessing and a neural network structure based on ResNet in combination with attention-based bidirectional long short-term memory (BiLSTM)

![2](https://github.com/user-attachments/assets/90291a9e-2ca8-4729-84df-7b7a2e80464a)
![fcvm-08-616585-g001](https://github.com/user-attachments/assets/111502d9-b909-4125-bf5e-948e02bf5220)  
refernce: https://www.frontiersin.org/journals/cardiovascular-medicine/articles/10.3389/fcvm.2021.616585/full  



