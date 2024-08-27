
# Breast Cancer Detection Project

## Overview
This project aims to detect breast cancer using machine learning techniques. The dataset used is the Wisconsin Breast Cancer dataset, available on Kaggle. The primary objective is to preprocess the data, visualize key relationships, and build a model to classify whether a tumor is malignant or benign.

## Dataset Source
The dataset can be accessed [here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

## Installation and Setup
To run this project, follow these steps:

1. **Clone the repository**:
    ```
    git clone https://github.com/your-repo/breast-cancer-detection.git
    cd breast-cancer-detection
    ```

2. **Set up the environment**:
    Ensure you have Python 3.x installed. It's recommended to use a virtual environment.
    ```
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:
    ```
    jupyter notebook Project_1_Breast_Cancer_Detection_Updated.ipynb
    ```

## Project Structure
- **Part 1: Data Preprocessing**
  - Loading the dataset
  - Handling missing values
  - Feature engineering and selection

- **Part 2: Exploratory Data Analysis (EDA)**
  - Visualizing data distribution
  - Analyzing relationships between features

- **Part 3: Model Building**
  - Building a classification model using algorithms such as Logistic Regression, Decision Trees, or Random Forests
  - Evaluating model performance using metrics like accuracy, precision, recall, and F1 score

- **Part 4: Model Evaluation and Interpretation**
  - Analyzing the confusion matrix and ROC curve
  - Interpreting feature importance and model predictions

## Usage
To use the trained model for predictions, follow these steps:
1. Load the preprocessed data or provide new data in the same format.
2. Use the model to make predictions:
    ```python
    predictions = model.predict(new_data)
    ```

## Results
The final model achieved an accuracy of 96.49%, with a precision of 95.74% and a recall of 95.74% on the test set. These results indicate the model's effectiveness in distinguishing between malignant and benign tumors.

## Contributions
Contributions to the project are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
