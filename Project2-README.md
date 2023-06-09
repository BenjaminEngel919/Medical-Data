#Stroke Prediction Project

1. Source of data

     Source of Data is a Kaggle Data Set

2. Brief description of data

    According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
    This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

3. What is the target?

  The target is 'stroke'

4. What does one row represent? (A person?  A business?  An event? A product?)

  Each Row is a person

5. Is this a classification or regression problem?

  Classification Problem

6. How many features does the data have?

  Five total features

7. How many rows are in the dataset?

  5110 Rows in the Data Set

8. What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?

  The amount of data is sufficient. Challenges I forsee is choosing the proper features for the target. Lots of two choice columns without a lot of variance.
  
  Visuals
  
  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/bdad6b21-e9a9-4eb7-b9c7-fa95e2f30336)
  
  Stroke by Age. This barplot shows how stroke increases greatly with age.

  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/c5ffc454-56b7-4464-9ea6-a6748091c32b)
  
  Best Visual. Stroke by Age with Smoking Status. Shows the dangers of smoking.

  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/618c4e20-def8-4144-8811-c99871dee1ba)
  
  Best Model, Logistic Regression. Predicted a Stroke and had the lowest number of missed strokes.
  
  Summary:
  
  My two recommendations to my stake holders would be to get a much larger data set. This is a hard model because False positive and negatives is acutally life and death. Not just a smaller return on investment. Logistic Regression is the best model as there are just two outcomes to predict with the target. The other models create too many bad predictions without predciting more True Positives. But best isn't something I would stake my life on. More data would definitely help with better predictions.
