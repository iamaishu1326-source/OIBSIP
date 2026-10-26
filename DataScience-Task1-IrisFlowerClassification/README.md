# Iris Flower Classification Using Machine Learning

## Author
**Aishwarya M**

## Internship
OASIS INFOBYTE — Data Science Intern

## Project Overview
This project uses machine learning to classify iris flowers into three species: Setosa, Versicolor, and Virginica, based on four physical measurements.

## Objective
The objective is to explore the Iris dataset, train multiple classification models, evaluate their performance, and identify the best-performing model based on test results.

## Dataset
The Iris dataset is built into the scikit-learn library. It contains 150 samples from three iris species.

The four input features are:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The target variable is the flower species.

## Technologies Used
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Google Colab

## Project Workflow
1. Loaded the Iris dataset using scikit-learn.
2. Performed exploratory data analysis (EDA).
3. Checked dataset shape, data types, missing values, and descriptive statistics.
4. Created a pairplot and box plots to visualize feature distributions.
5. Split the dataset into training and testing sets using an 80/20 ratio.
6. Trained four classification models:
   - Logistic Regression
   - K-Nearest Neighbors
   - Decision Tree
   - Random Forest
7. Compared test accuracy and evaluated model performance using precision, recall, F1-score, and a confusion matrix.
8. Tested a sample flower prediction.

## Model Results

| Classification Model | Test Accuracy |
|---|---:|
| Logistic Regression | 93.33% |
| K-Nearest Neighbors | 93.33% |
| Decision Tree | 93.33% |
| Random Forest | 90.00% |

### Best-Performing Models
Logistic Regression, K-Nearest Neighbors, and Decision Tree achieved the highest test accuracy of 93.33%. These models are tied based on test accuracy.

Precision, recall, F1-score, and confusion matrices provide additional information about each model's performance.

## Sample Prediction
The notebook tests the model using the following flower measurements:
- Sepal length: 5.1 cm
- Sepal width: 3.5 cm
- Petal length: 1.4 cm
- Petal width: 0.2 cm

The sample prediction is **Setosa**.

## How to Run the Project
1. Open `Iris_Flower_Classification.ipynb` in Google Colab.
2. Run the notebook cells from top to bottom.
3. Review the data analysis, visualizations, model comparisons, evaluation metrics, and sample prediction.

No external dataset download is required.

## Conclusion
This project demonstrates a basic supervised machine learning workflow, including data exploration, visualization, model training, performance comparison, and classification evaluation. It helped me understand how different classification algorithms can predict iris flower species from physical measurements.
