
This repository contains the code and utilizes Machine learning algorithms for regression. 

Execution environment - Google Colab. 

Dataset- Upload the iris.csv file in Google Drive and  paste the path for the execution.

For parsing JSON, upload the JSON file to the drive and paste the path in Google Colab for execution

The main code is uploaded in MAININTERNSHIP.ipynb.

For evaluation purposes, the regression algorithms are considered.
 The project aims to predict the outcome based on the variables. The steps are as follows
 
    1. Convert the RTF file to JSON (algaparams.json)
    
    2. Upload the dataset(iris.csv) from google drive
    
    3. Upload the JSON set for evaluating
    
    4. Preprocess the dataset-
    
        Checked for null values
        
        Label encoding is performed for the feature named species(3)
        
        Standard scaling is done for normalization
        
     5. Imputation is done for missing values, Mean imputation is performed for 2 features, and for the other 2 features,it is imputed with the corresponding values 
     
     6. Feature reduction is performed using F_regression (correlation with target),Decision tree(Tree-Based)
            [ PCA is used for dimensionality reduction]
            
     7. Finally regression is performed with various regression algorithms.
     
          Hyperparameter tuning is performed using a grid search
          
      8. For evaluation performance metrics like MSE, RMSE is calculated.
      
         Test and predicted values are plotted
        
        
    
