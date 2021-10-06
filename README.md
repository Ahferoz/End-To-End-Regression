# End-To-End-Regression
End-To-End Regression on Real World Data

Here we have used concrete data to predict strength of concrete based on the amount of ingredients used in concrete formation.Here Target variable is Strength of concete in MPa.

## Things To learn

### Variable descriptions
- In this we describe about the variables in our data set and what their values represent.
 
   We have described what each variable value mean.We have identified Target variable and Features. Target and features both are numeric data. Features are cement, slag, flyash,     water, superplasticizser, coarseaggregates, fineaggregate and Target is csMp.
 
### Exploratory Data Analysis (EDA)
- In EDA, we get the insights of our data as much as possible such data type of each variable , missing values, relation among the variable,distribution of varibales etc. 
  
  We have split our data into train and test set.We have checked target variable distribution in training and validation data to ensure same distribution.we have also checked        relationship between target variables and features.
   
### Model Selection 
- Here we train different models on our training set to select the one which performe better then do the experiment with the selected one to enhance the model performance.

  We have trained Polynomial Regression Model with Two Three Degree,Random Forest Regression model and evaluated these on model on validation set and selected Random Forest         Regression model because its performance is better than others.

### Hyperparameter Tuning for RandomForest
- Hyperparameter tunning means to select the parameters that give the optimum performance of model.We can do this with the help of scikit-learn library.

  we have performed Hyperparameter Tuning of parameters of Random Forest and found the best combination of parameters  {'bootstrap': False, 'max_depth': None, 'max_features':       'log2', 'n_estimators': 200}.This helped us to reduce overfittings.
 
### R-square
- It is the metrics which measure the performance of our model.
   
   We got 
  
    R2 for Training: 0.8891369689134896 
  
    R2 for Validation: 0.854119546244056
 
 
