# Report

## Overview
The aim is to employ advanced deep learning techniques for predicting the success of organizations. By analyzing various features in the dataset that describe these organizations, we aim to build a robust classification model. This model will enable us to forecast whether an organization is likely to be successful based on its unique characteristics.

## Results
### Data Preprocessing

The objective is to forecast the "IS_SUCCESSFUL" result, utilizing details from the "NAME," "APPLICATION," "TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," "STATUS," and "ASK_AMT" columns as model features. Worth noting is the exclusion of the "EIN" column from the input data.

### Compiling, Training, and Evaluating the Model
The enhanced model featured two hidden layers with an increased number of neurons in the first layer, going from 80 to 100, aiming to boost accuracy. Both layers used the 'relu' activation function, and the training process maintained a consistent 100 epochs. The model achieved the desired performance. Additionally, the "NAME" column was transformed into data points as part of the improvements.

## Summary
The model performed well with an accuracy of about 79.18% on the test data, and the loss was 0.4777. Another option worth exploring is the Random Forest model, especially suitable for classification tasks.

