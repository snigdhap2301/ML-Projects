# Heart Disease Prediction

This project is aimed at predicting the likelihood of heart disease in individuals based on various health parameters. The prediction model is developed using logistic regression, a popular machine learning algorithm for binary classification tasks.

## Getting Started

To get started with the Heart Disease Prediction model, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Ensure you have all the necessary dependencies installed. You can install them using pip:

    ```bash
    pip install numpy pandas scikit-learn
    ```

3. **Data Collection and Processing**: The dataset containing various health parameters such as age, sex, cholesterol levels, blood pressure, etc., is loaded from a CSV file (`heart_disease_data.csv`) using pandas. Missing values are checked and handled appropriately.

4. **Model Training**: The logistic regression model is trained using the training data.

5. **Model Evaluation**: The accuracy of the trained model is evaluated using both training and testing datasets.

6. **Predictions**: Once the model is trained, you can make predictions for new data. Input the health parameters for an individual, and the model will predict whether the person has heart disease or not.

## Usage

To use the Heart Disease Prediction model:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Navigate to the Project Directory**: Open a terminal and change the directory to where the project is cloned.

3. **Run the Script**: Execute the Python script (`heart_disease_prediction.py`).

    ```bash
    python heart_disease_prediction.py
    ```

4. **Input Parameters**: Input the health parameters for the individual you want to make predictions for. These parameters include age, sex, cholesterol levels, blood pressure, etc.

5. **View Results**: The model will output whether the person has heart disease or not based on the input parameters.

## Dataset

The dataset used for training and testing the model is stored in a CSV file named `heart_disease_data.csv`. It contains various health parameters and a target variable indicating whether the person has heart disease or not.

## Credits

This project is developed with the help of a Siddhardhan's YT Channel. The tutorials provided by the channel were instrumental in guiding the development process and understanding the concepts involved in heart disease prediction using logistic regression.