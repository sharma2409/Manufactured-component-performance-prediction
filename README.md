# Manufactured-component-performance-prediction
Complex System Performance prediction of a jet engine component manufacturing process

![image](https://user-images.githubusercontent.com/50777880/125146605-a6cc9700-e0f4-11eb-8965-accdd8781d05.png)

The goal is to predict whether response_2 variable (the final manufactured part) will end in failure or not.

The step-by-step solution to the problem is as follows:

1. Sharma_Raghav_EDA: Contains the exploratory Data Analysis for the dataset of all the input variables.
2. Sharma_Raghav_Regression-Models-iiA_2: Contains four different linear models for response_1
3. Sharma_Raghav_Regression-Models-iiC_Caret: Contains the prediction of response_1 with various machine learning models, each of the models fine-tuned with grid-search. Using the Caret package
4. Sharma_Raghav_Binary_Classification_Option_B_ROC: All models in Sharma_Raghav_Regression-Models-iiC_Caret is used to train a binary classifier with ROC as metric
5. 4. Sharma_Raghav_Binary_Classification_Option_B_Accuracy: All models in Sharma_Raghav_Regression-Models-iiC_Caret is used to train a binary classifier with Accuracy as metric
6. Random Forests is found to be the best performing model for binary classification


