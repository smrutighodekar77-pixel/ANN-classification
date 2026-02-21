Customer Churn Prediction using ANN

Overview
This project predicts customer churn using an Artificial Neural Network (ANN).
The model was built, optimized, and deployed as a web application using Streamlit.

It demonstrates the complete end-to-end machine learning workflow — from data preprocessing to model deployment.

Tech Stack

Python
Pandas
Scikit-learn
TensorFlow / Keras
SciKeras
Streamlit

Project Workflow

Data Preprocessing
Dropped unnecessary columns (RowNumber, CustomerId, Surname)
Applied Label Encoding (Gender)
Applied One-Hot Encoding (Geography)
Performed feature scaling using StandardScaler
Split data into training and testing sets

Model Building
Built an ANN using TensorFlow and Keras
Used ReLU activation in hidden layers
Used Sigmoid activation in output layer
Compiled model with Adam optimizer and Binary Crossentropy loss

Hyperparameter Tuning
Used GridSearchCV with SciKeras
Tuned number of neurons, hidden layers, and epochs

Deployment
Saved encoders and scaler using Pickle
Deployed the trained model as an interactive web application using Streamlit

Learning Outcome
Hands-on experience in ANN model building
Hyperparameter tuning
End-to-end ML pipeline implementation
Model deployment using Streamlit
