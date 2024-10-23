# ThreatDetection_UsingAI


# Overview

The Threat Detection Using AI project aims to enhance cybersecurity by utilizing machine learning techniques to analyze network traffic data. By leveraging the CIC-IDS2017 dataset, the project focuses on identifying various types of cyber threats through a systematic approach that includes data preprocessing, attack filtering, feature selection, and machine learning algorithm evaluation. This comprehensive methodology allows for effective detection and classification of potential threats in network environments.

# Implementation

Step 1: Data Preprocessing (PreProcessing.ipynb)
- Conducts data preprocessing to prepare the CIC-IDS2017 dataset for machine learning.
- The dataset files should be stored in the "CSVs" folder located in the same directory as the program.
  
Step 2: Attack Data Filtering (AttackDivision.ipynb)
- Uses the "all_data.csv" file to create attack-specific files.
- Saves these files in the "./attacks/" directory for further analysis.
- Separates a total of 12 different attack types for individual examination.
  
Step 3: Feature Selection and Machine Learning (FeatureSelection.ipynb)
- Focuses on selecting relevant features from the attack files created in Step 2.
- Identifies the four most significant features for each file to be used as input for machine learning algorithms.
  
Step 4: Machine Learning Algorithm Evaluation (MachineLearningSep.ipynb)
- Applies seven machine learning algorithms to each attack file multiple times for robust evaluation.
- Displays results on-screen and saves them in the "./attacks/results_1.csv" file.
- Generates box and whisker plots representing the results, which are saved in the "./attacks/result_graph_1/" folder.
  
# Dataset Source
Access the CIC-IDS2017 dataset here.

This structured README provides a clear overview of the project, outlining its purpose and detailed steps involved in its implementation.

