# forest_cover_type_classification

Project Title: Forest Cover Type Classification

Language: Python (Jupyter Notebook)

Motivation and Notes:
  - This project was completed for DATA 11900 at the University of Chicago in Winter 2023.
  - The curated dataset can be downloaded from the UCI Machine Learning Repository at https://archive.ics.uci.edu/ml/datasets/covertype.
  - Motivations for the analysis of this dataset can be found in the included final report.
  - Note: dataset citations and related papers are included in the final report

Description:
  This project analyzes a dataset containing 581,012 instances and 54 attributes in order to classify and predict forest 
  cover types within 4 wilderness areas in Roosevelt National Forest, CO. Each instance is a 30x30m plot of land. The dataset
  contains 53 descriptive variables (both continuous and indicator) and one column containing each instance's correct 
  classification. The dataset was split into training and test datasets and scaled before classifying using logistic 
  regression and knn-classification.
  
Structure:
  The project includes a final report, the dataset, the codebook, and the jupyter notebook with analysis ('CoverType Prediction'). 
  Not all of the analysis included in the jupyter notebook is found in the final report, and some analysis in the report was 
  done by my partner in this group project. Note that the csv file referred to in the prediction Jupyter notebook can be created
  via the 'CoverType Convert to CSV' notebook file.
