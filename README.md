DISEASE PREDICTION USING MACHINE LEARNING


PROJECT OVERVIEW

This project is a Machine Learning–based Disease Prediction System that predicts the most likely disease based on symptoms provided by the user.

The system uses multiple supervised learning algorithms and combines their predictions to improve accuracy and reliability.

Algorithms used:
1. Support Vector Machine (SVM)
2. Naive Bayes (GaussianNB)
3. Random Forest Classifier

Final prediction is obtained using a majority voting (mode) technique.


DATASET DETAILS

• Training Dataset : Training.csv
• Testing Dataset  : Testing.csv

The dataset consists of:
- Binary symptom features (0 or 1)
- Target variable: Prognosis (Disease name)

Missing or empty columns are removed during preprocessing.


FEATURES OF THE PROJECT

• Handles multiclass disease classification
• Dataset balancing visualization using bar plots
• Label encoding for target variable
• Train-test split for performance evaluation
• 10-fold cross-validation for model comparison
• Confusion matrix visualization for each model
• Ensemble prediction using majority voting
• User-input based disease prediction function


TECHNOLOGIES & LIBRARIES USED

Programming Language:
• Python

Libraries:
• NumPy
• Pandas
• Matplotlib
• Seaborn
• Scikit-learn
• SciPy


WORKFLOW

1. Import required libraries
2. Load and clean the dataset
3. Perform exploratory data analysis (EDA)
4. Encode disease labels
5. Split data into training and testing sets
6. Train multiple ML models
7. Evaluate models using:
   - Accuracy score
   - Cross-validation
   - Confusion matrix
8. Train final models on full dataset
9. Predict diseases using ensemble learning
10. Accept user symptoms as input and predict disease


MODEL EVALUATION

• Cross-validation (10-fold) used for model comparison
• Accuracy calculated on both training and test datasets
• Confusion matrices visualized for:
  - SVM
  - Naive Bayes
  - Random Forest
  - Combined Ensemble Model


USER PREDICTION FUNCTION

The function `predictDisease()` allows users to input symptoms as a comma-separated string.

Example:
predictDisease("Itching,Skin Rash,Nodal Skin Eruptions")

Output:
• Prediction by Random Forest
• Prediction by Naive Bayes
• Prediction by SVM
• Final combined prediction


RESULT

The ensemble model improves prediction stability and accuracy by combining multiple classifiers instead of relying on a single model.


APPLICATIONS

• Medical decision support systems
• Symptom-based disease diagnosis
• Healthcare analytics projects
• Academic and learning purposes


FUTURE ENHANCEMENTS

• Web application using Flask or Django
• Real-time user interface
• Severity-based symptom weighting
• Integration with real medical datasets
• Deep learning model integration


AUTHOR

Name : Abhishek Kumar  
Role : Machine Learning Project (Academic / Self Project)


