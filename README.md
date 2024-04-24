# Wine-Quality-Prediction
YbiFoundation


Wine Quality Prediction:-
                        This project aims to predict the quality of wine using machine learning techniques. It is done in collaboration with the YBI Foundation.

Overview:-
          This project utilizes a dataset containing various features of white wine samples to predict their quality. The machine learning model is trained on this data to classify wines             into different quality categories.

Getting Started:-
Importing Libraries and Data
                  The project begins with importing necessary libraries such as Pandas and NumPy. The dataset is then imported from the YBI Foundation GitHub repository.

Data Description:-
                  The dataset consists of 4898 entries and 12 columns, including features like fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide,                    total sulfur dioxide, density, pH, sulphates, alcohol, and quality.

*Data Preprocessing*
Before training the model, the data is preprocessed, including:

1.Standardization of features using StandardScaler from scikit-learn.
2.Defining the target variable (quality) and feature variables (X).
3.Splitting the data into training and testing sets.


*Model Training and Evaluation*
A Support Vector Machine (SVM) classifier is trained on the training data and evaluated using the testing data. The evaluation includes:

1.Confusion matrix
2.Classification report, including precision, recall, and F1-score
3.Model accuracy

Results:-
        The model achieves an accuracy of approximately 58% in predicting the wine quality.

Future Predictions:-
                  The project also demonstrates how to make predictions on new data samples using the trained model.

Dependencies:-
                1.Pandas
                2.NumPy
                3.scikit-learn


Usage:-
        To use this project:

1.Clone the repository.
2.Install the required dependencies.
3.Run the Jupyter Notebook file (Final_Project.ipynb) to train the model and make predictions.

Contributors:-
              Mehul Goyal
              
Contact:-
          For any questions or inquiries, please contact mehulgoyal8888@gmail.com.







