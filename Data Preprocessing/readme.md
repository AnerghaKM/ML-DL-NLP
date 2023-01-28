# Data Preprocessing

Data preprocessing, a component of data preparation, describes any type of processing performed on raw data to prepare it for another data processing procedure. It has traditionally been an important preliminary step for the data mining process.

There are several different tools and methods used for preprocessing data, including the following:

   ~ sampling, which selects a representative subset from a large population of data.  
        
   ~ transformation, which manipulates raw data to produce a single input.  
    
   ~ denoising, which removes noise from data.  
    
   ~ imputation, which synthesizes statistically relevant data for missing values.  
    
   ~ normalization, which organizes data for more efficient access.  
    
   ~ feature extraction, which pulls out a relevant feature subset that is significant in a particular context.  
   
   # Steps in Model Creation
   
   
    1-Exploratory Data Analysis (EDA) is used to analyze the raw data
    
    2-Feature Engineering is the process of extracting features from raw data.
       
    3-Feature Selection where we select those features that will give a high impact on the model.  
    
    4-Model creation in this we create a machine learning model using suitable algorithms.  
     
    5-Deployment where we deploy our ML model.
    
    First 3 steps comprises of the Data preprocessing task.Last 2 steps focus on Model Training and deployment.
    
    
    - Fit()
    
    takes the feature F and it will just compute the mean (μ) and standard deviation (σ) of feature F.
    
    - Transform() 
    
    Apply the calculations that we have calculated in fit() to every data point in feature F.
    
    -Fit_transform()
    
    This fit_transform() method is basically the combination of fit method and transform method, it is equivalent to fit().transform(). This method performs fit and transform on the input data at a single time and converts the data points. 
    
    
    
    
     

    

