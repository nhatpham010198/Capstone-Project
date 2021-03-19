# Capstone-Project
This is the coding work of Nhat Pham's capstone project.
The objective of this work is to develop a ML model used to predict the default probability default. The model is trained and validated on Lending Clubs' dataset from 2007 to 2018Q4, which is available on Kaggle.

From this modeling work, a contextual model development framework will be developed for banks in Vietnam. The framework will clearly explain steps and techniques that are implemented to develop the model. Some other analyses that I think suitable for the credit rating context but are not implemented due to computational and information constraints will also be discussed.

In the development process, the logistic regression will be applied because it is easy to interpret. This advantage of logistic regression is beneficial for creating a framework to target non-technical audience in Vietnam's banking industry.

Regarding the structure, this coding work includes 6 main sections:
 
  I. Data experiment: display some plots to understand the business of Lending Club

  II. Variable matching: identify and extract information available to Lending Club's investors before the approval. 
  
  III. Data preprocess: preprocess data to align their format with the model's requirements

  IV. Variable selection: analyze variable individually and in pair to identify the most optimal variables to train the model 

  V. Model development: training and validate the model with a specific setting of the logistic regression function.

  VI. Model modification: observe the model efficiency and adjust the model over iterations to optimize it.

Conclusion:
Developing the model with various approaches and settings, the best result obtained with logistic regression on the data set is AUROC: 0.69, Accuracy: 0.64, Precision: 0.92, #independent variables: 6. This result surprisingly outplays the best models available on Kaggle.
