DS 805 - Statistical Learning - Spring 2023 Term 1 Project

Using Titanic Survivor Data, creating a model to predict survivorship based on specific demographic information ie wealth, age, gender, ect. 

Data came from UCI Machine Learning Repository - https://archive.ics.uci.edu/ml/datasets.php?format=&task=cla&att=&area=&numAtt=&numIns=&type=&sort=nameUp&view=table

Project Details:

You can pick any data you want as long as it is a classification problem.
Read your data in R and call it df. For the rest of this document y refers to the variable you are predicting.

Part 1: Exploratory Data Analysis (20 points)

  Check for existence of NA’s (missing data)

  If necessary, classify all categorical variables except the one you are predicting as factors. Calculate the summary statistics of the entire data set.

   For the numerical variables, plot box plots based on values of y. Do you see a difference between the box plots for any of the variables you choose?

  For the categorical variables, plot bar charts for the different values of y. Do you see a difference between plots for any of the variables you choose?

  Test/training separation: Separate your data into 80% training and 20% testing data. Do not forget to set seed. Please use the same separation for the whole assignment, as it is needed to be able to compare the models.

Part 2: Logistic Regression or LDA (15 points)

  Develop a classification model where the variable y is the dependent variable using the Logistic Regression or LDA, rest of the variables, and your training data set.

  Obtain the confusion matrix and compute the testing error rate based on the logistic regression classification.

  Explain your choices and communicate your results.

Part 3: KNN (15 points)

  Apply a KNN classification to the training data using.

  Obtain the confusion matrix and compute the testing error rate based on the KNN classification.

  Explain your choices and communicate your results.

Part 4: Tree Based Model (15 points)

  Apply one of the following models to your training data: Classification Tree, Random Forrest, Bagging or Boosting

  Obtain the confusion matrix and compute the testing error rate based on your chosen tree based model.

  Explain your choices and communicate your results.

Part 5: SVM (15 points)

  Apply a SVM model to your training data.

  Calculate the confusion matrix using the testing data.

  Explain your choices and communicate your results.

Part 6: Conclusion (20 points)

  (10 points) Based on the different classification models, which one do you think is the best model to predict y? Please consider the following in your response:
        Accuracy/error rates
        Do you think you can improve the model by adding any other information?

  (10 points) What are your learning outcomes for this assignment? Please focus on your learning outcomes in terms of statistical learning, model interpretations, and R skills - it is up to you to include this part in your presentation or not.

