# Company Bankruptcy Prediction ML Project
## Introduction
This is a machine learning project that predicts the bankruptcy of a company using various financial features. The project includes data preprocessing, model selection, and evaluation. The best-performing model has an accuracy of 96.63%.

## Prerequisites
The following packages are required to run the project:
- numpy
- pandas
- scikit-learn
- matplotlib

## Data
The data used in this project is obtained from a public dataset and contains financial information of companies. The features used in the project are selected based on their relevance to the bankruptcy prediction task.

## Preprocessing
The data is preprocessed to handle missing values, outliers, and scaling issues. The preprocessing steps include:
- Train-test split
- Standard scaling

## Models
The following machine learning models are used to predict the bankruptcy of a company:
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Support Vector Machine (Linear and RBF kernel)
- Neural Network
- Random Forest
- Gradient Boosting

## Dimensionality Reduction

To improve the performance of the models, the number of features is reduced using PCA (Principal Component Analysis).

## Results
The performance of each model is evaluated using accuracy, and the best-performing model is Support Vector Machine with an RBF kernel, achieving an accuracy of 96.63%.

## Conclusion
This project provides a framework for predicting the bankruptcy of a company using machine learning algorithms. The best-performing model can be used as a reference for future projects with similar objectives.

### How to run the code
- Clone the repository
- Install the required packages
- Run the bankruptcy_prediction.py file

### Contributing
Contributions are welcome and appreciated. To contribute, create a pull request with your changes.

### License
This project is licensed under the MIT License.
