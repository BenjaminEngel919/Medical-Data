     Stroke Prediction Project

   According to the WorlHealth Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
    This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

  The target for this dataset is stroke. This is a Classification problem.

  The amount of data should be sufficient. Challenges I forsee is choosing the proper features for the target. Lots of two choice columns without a lot of variance. I might have to use boosting and oversampling to increase the total dataset.
  
  Visuals
  
  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/bdad6b21-e9a9-4eb7-b9c7-fa95e2f30336)
  
  Stroke by Age. This barplot shows how stroke increases greatly with age.

  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/c5ffc454-56b7-4464-9ea6-a6748091c32b)
  
  Best Visual. Stroke by Age with Smoking Status. Shows the dangers of smoking.

  ![image](https://github.com/BenjaminEngel919/Medical-Data/assets/126991382/618c4e20-def8-4144-8811-c99871dee1ba)
  
  Summary:
  
  My recommendations to my stake holders would be to use an oversampled SMOTE Logistic Regression model. Accuracy was 92%. False negatives are what you want to avoid the most with this dataset. This model had the least number of these. I would recommend to contiue to add to the data to try and make an even better model.
