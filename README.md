# Rain Prediction: Artificial Neural Network (ANN)

## Developer Profile
**Daniel Calzado Aldana** *SOFTWARE ENGINEER | BACKEND & DATA ANALYST | IT SYSTEMS*

## Description
This repository contains an Artificial Neural Network (ANN) implementation designed to predict binary weather events (rain/no rain for the next day). The project highlights a complete data engineering workflow: handling missing values, categorical variable transformation, feature scaling, and designing a deep learning architecture using TensorFlow/Keras.

## Tech Stack
* **Core:** Python 3.x
* **Data Analysis:** Pandas, NumPy
* **Preprocessing:** Scikit-learn (StandardScaler, train_test_split)
* **Deep Learning:** TensorFlow & Keras
* **Visualization:** Matplotlib

## Key Project Features
1. **Data Cleaning:** Selective removal of variables with high null rates (>20%) and statistical imputation (median/mode) for the remaining missing data.
2. **ANN Architecture:** Sequential network with Dense layers and ReLU activation, utilizing a single-neuron output layer with a Sigmoid function to output classification probabilities.
3. **Performance Evaluation:** Visual monitoring of the model's convergence through accuracy and loss curves to prevent overfitting.

## How to Run and Test the Model

To test this project locally:

1. Clone the repository:
   git clone https://github.com/danielcalzado91/rain-prediction.git

2. Install dependencies:
   pip install pandas numpy scikit-learn tensorflow matplotlib

3. Run the Notebook:
   Open rain_prediction_project.ipynb in Jupyter Notebook, Google Colab, or VS Code to execute the cells sequentially. 

4. Testing with New Data:
   Once the model is trained, you can pass a new standardized array of features to the predict method to get the probability of rain.
