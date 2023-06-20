# Neuro-Network - Challenge 21

## Overview
Alphabet Soup, a nonprofit foundation, is seeking a tool that can assist in selecting the most promising funding applicants. By using machine learning and neural networks, a binary classifier is created based on the provided dataset, which predicts the likelihood of success of applicants if they were funded by Alphabet Soup. The business team at Alphabet Soup has provided a CSV file containing over 34,000 organizations that have received funding from the foundation over the years.

## Results
Using the knowledge of Pandas and scikit-learn’s StandardScaler(), the data was preprocessed. The columns "IS_SUCCESSFUL" was identified as the target column as it tells us whether the applications were successful or not. All the other columns were classified as features. The data was then compile, train and evaluated by designing a Neuro Network Model. The model was created with two hidden layers followed with the outcome layer. The hidden layers consisted of 80 and 30 nodes respectively. The activation function used in the model was relu for the hidden layers and sigmoid for the outcome layer. The model showed the following accuracy.

<img width="500" alt="model" src="https://github.com/SaeedaKhuwaja/Neuro-Network/assets/83857632/e77b8d2b-bfb3-4f9f-b9c4-398b8e2b8c68">

Three more attempts were made to optimize the data and get the accuracy more than 75%. 

### Attempt 1
In the first attempt, one hidden layer was added in the model. The nodes were distributed as 80, 40 and 20 with activation function as Relu. The data displayed the following accuracy.

<img width="520" alt="model01" src="https://github.com/SaeedaKhuwaja/Neuro-Network/assets/83857632/11756774-3dd6-4663-a3cb-01e17b5d24ee">

### Attempt 2
In the second attempt, the activation function of last hidden layer was changed to Sigmoid and number of nodes were increased. The nodes were distributed as 85, 45 and 22. The data displayed the following accuracy.

<img width="520" alt="model02" src="https://github.com/SaeedaKhuwaja/Neuro-Network/assets/83857632/72fde9ac-3233-4fcd-9818-a5fb26692424">

### Attempt 3
In the third and final attempt, the hidden layer was added; making it four. The nodes were distributed as 85, 50, 32 and 15 with activation in first three hidden layers as Relu and last one as Sigmoid. The data displayed the following accuracy.

<img width="520" alt="model03" src="https://github.com/SaeedaKhuwaja/Neuro-Network/assets/83857632/3d92f41e-0d93-40fb-b73c-e09a40d565d5">

## Summary

All of the attempts show almost the same accuracy of around 72%. The target percentage is not achieved in all the attempt; may be because the number of nodes were not used efficiently or the activation function was in not appropriate. In order to get the more accurate results, a proper research is required where usage of activation functions is clear and number of layers are used properly. 






