# Neural_Network_Charity_Analysis


## **Background**

The project aims to analyse and determine which organisation to fund with the help of machine learning and neural networks. We will use the features provided in the dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The analysis was performed four times using a different method to improve the accuracy of the model.

## **Results**
### ***Data Processing***
- <ins>Target variable</ins> : The target variable in this model was 'IS_SUCCESSFUL' column.
- <ins>Features</ins>: The features of the model are the columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS,and ASK_AMT.
- <ins>Removed from the input data</ins>: The columns EIN and NAME have unique values and will not be contributing to our statistical prediction.

### ***Compiling, Training, and Evaluating the Model***

- In the first attempt we used two hidden layers. The first one had 80 neurons and the other one had 30 neurons. The initial speculation was there are high chances of overfitting but that could have been reversed using the checkpoints. Although that turned out not to be the case. The model accuracy in the first attempt was 72%. The target model performance was 75% or higher.
- I tried to make three more attempts to improve the accuracy of the model. In the second attempt, I changed the activation method of the second layer from 'relu' to 'tanh'. The accuracy of the second attempt was 73.9%. In the third attempt, I added another hidden layer to the model. Two of the hidden layers had 'relu' activation method while the third one had 'tanh' activation. The accuracy of that model turned out to be 73.8%. Finally, I tried adjusting epochs, adding the number of hidden layers and changing the activation method. The accuracy of the fourth and final model was 74%. 

## **Summary**
The target accuracy was nearly achieved although it was still an average performing model. Accuracy could have been improved by adjusting hidden layers and changing the activation methods further. Although other supervised learning models could have also been utilised here for example Random Forest Method and Support Vector Machine.
