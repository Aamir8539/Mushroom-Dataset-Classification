<h1> Mushroom-Classification </h1>

<h3>1. CLassification of mushrooms into two categories: Edible and Non-Edible </h3>
    
<h3>2. Packages Used to solve this classification problem </h3>
    
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
    
 <h3>3. Load the dataset   </h3>   
    
 <h3>4. Understand and prepare the data </h3>
    
        First, I am getting a basic description of the data, to look quickly at the overall data to get some simple, 
        easy-to-understand information. This is just to get a basic feel for the data.Unsing Genral Functions.
    
        a. Shape of Dataset --->  (8124, 23)

 <h3>5. Checking for missing values. </h3>
    
        a. 0 Null-values present in the dataset.
 <h3>Visualizing data using Matplotlib and seaborn libraries.</h3>

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

<h3>6. Converting the categorical values into encoded values using Label Encoder </h3>
    
<h3>7. Split data into dependent and independent variables </h3>

<h3>8. Standardizing the data using Standard Scaler </h3>
    
<h3>9. Feature salection </h3>
    
           a. x_train (6093, 95)
           b. y_train (6093, 1)
           c. x_test (2031, 95)
           d. y_test (2031, 1)

<h3>10. Modeling Using Naive Bayes machine learning algorithms <h3>

<h3>11. Classification report in table format </h3>    
  
    i.    Model	                  -       Naive Bayes Classification
    ii.   Precision Score	      -       0.94855  
    iii.  Recall Score	          -       0.948694
    iV.   Accuracy Score	      -       0.945839
    V.    f1-score                -       0.945839
          	                	          	          
<h3>12. Plotting Confusion Matrix </h3>

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/CM.png)

<h3>13. Plotting ROC Cruve </h3>

   ![Alt Text](https://github.com/Aamir8539/Naive-Bayes-Classification-Project/blob/main/Image/ROC.png)

<h3>14.For complete analysis please see my python notebook 'Naive-Bayes-Classification-Project'.  </h3>
