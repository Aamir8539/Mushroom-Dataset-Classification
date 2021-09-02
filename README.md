<h1> Mushroom-Classification </h1>

    1. CLassification of mushrooms into two categories: Edible and Non-Edible

    2. This data is taken from Kaggle.
    
    3. Packages Used to solve this classification problem 
    
           a. import numpy as np
           b. import pandas as pd
           c. import matplotlib.pyplot as plt
           e. import seaborn as sns
           f. pd.options.display.max_columns = None
           g. from sklearn.model_selection import train_test_split
           h. from sklearn.naive_bayes import GaussianNB
           i. from sklearn.metrics import confusion_matrix
           j. from sklearn.metrics import classification_report
           k. from sklearn import metrics
           l. from sklearn.metrics import roc_curve
    
    4. Load the dataset      
    
    5. Understand and prepare the data
    
        a. Shape of Dataset --->  (8124, 23)

    6. Checking for missing values.
    
        a. 0 Null-values present in the dataset.

**Visualizing data using Matplotlib and seaborn libraries.**

    a. *Class Countplot*

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/Class.png)

    b. *Stalk Root Countplot*

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/Stalk%20Root.png)

    c. *Stalk Shape Countplot*

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/Stalk%20Shape.png)

    d. *Cap Shape Countplot*

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/Cap-Shape.png)

    d. *Cap Color Countplot*

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/Cap%20Color.png)

    7. Converting the categorical values into encoded values using Label Encoder
    
    8. Split data into dependent and independent variables

    9. Standardizing the data using Standard Scaler
    
    10. Feature salection
    
           a. x_train (6093, 95)
           b. y_train (6093, 1)
           c. x_test (2031, 95)
           d. y_test (2031, 1)

    11. Modeling Using Naive Bayes machine learning algorithms

<h3> Classification report in table format </h3>    
  
    i.    Model	                  -     Naive Bayes Classification
    ii.   Precision Score	      -     0.94855  
    iii.  Recall Score	          -     0.948694
    iV.   Accuracy Score	      -     0.945839
    V.    f1-score                -     0.945839
          	                	          	          
    12. Plotting Confusion Matrix

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/CM.png)

    13. Plotting ROC Cruve

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/ROC.png)

    14.For complete analysis please see my python notebook 'Naive-Bayes-Classification-Project'.
