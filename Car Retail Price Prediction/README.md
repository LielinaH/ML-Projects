# Car Retail Price Prediction Project

This project involves predicting car retail prices using various machine learning models. The dataset is sourced from Kaggle and includes features such as the car's year of manufacture, kilometers driven, fuel type, seller type, and transmission type.

## Project Structure

### 1. Data Preprocessing
- **Importing Libraries**: Essential libraries like numpy, pandas, matplotlib, and seaborn are imported.
- **Loading the Dataset**: The dataset is loaded from a CSV file.
- **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset including checking for null values, data types, and basic statistics.
- **Handling Missing Data**: Visualizing and handling any missing data in the dataset.
- **Encoding Categorical Variables**: Converting categorical features into numerical representations using one-hot encoding.
- **Splitting the Dataset**: Dividing the dataset into training and testing sets.
- **Feature Scaling**: Applying feature scaling where necessary to normalize the data.

### 2. Building the Model
- **Multiple Linear Regression**: Implementing a basic linear regression model to predict car prices.
- **Random Forest Regression**: Implementing a more complex Random Forest model for better accuracy.

### 3. Model Optimization
- **RandomizedSearchCV**: Finding the optimal hyperparameters for the Random Forest model to improve its performance.

### 4. Final Model
- **Final Random Forest Model**: Building the final model with the best parameters obtained from the optimization step.

### 5. Prediction
- **Predicting Car Prices**: Using the final model to predict the retail price of a car based on specific input features.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## How to Use
1. Clone the repository or download the notebook.
2. Ensure you have all the required libraries installed.
3. Open the notebook and run the cells sequentially.
4. Modify the input data in the prediction section to predict prices for different car configurations.

## Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho). It contains information about various cars including:
- Car Name
- Year of Manufacture
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission Type
- Number of Previous Owners

## License
This project is open source and available under the MIT License.