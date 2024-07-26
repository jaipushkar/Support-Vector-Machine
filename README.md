# Support-Vector-Machine

**Iris Flower Classification**
This project involves classifying iris flowers into three species using the Iris dataset and Support Vector Machine (SVM) classifier. The Iris dataset consists of measurements of iris flowers' sepal and petal lengths and widths.

**Dataset**
The Iris dataset is loaded from the sklearn.datasets module. It includes the following features:
sepal length (cm)
sepal width (cm)
petal length (cm)
petal width (cm)

**The target variable is the species of the iris flower:**
Setosa
Versicolor
Virginica
Steps

**Data Loading and Preparation:**
Loaded the Iris dataset.
Created a DataFrame with feature names.
Added a target column and mapped target values to their respective species names.

**Data Visualization:**
Plotted scatter plots for sepal length vs. sepal width and petal length vs. petal width for different species.

**Model Training:**
Split the dataset into training and testing sets.
Trained an SVM classifier using the training set.

**Model Evaluation:**
Evaluated the model's accuracy on the testing set.

**Dependencies**
pandas
matplotlib
scikit-learn

**Digits Recognition**
This project involves recognizing handwritten digits using the Digits dataset and SVM classifier.

**Dataset**
The Digits dataset is loaded from the sklearn.datasets module. It includes:
8x8 pixel images of handwritten digits (0-9)
Target variable indicating the digit

**Steps**
**Data Loading and Preparation:**
Loaded the Digits dataset.
Created a DataFrame with the digit images and target values.

**Model Training:**
Split the dataset into training and testing sets.
Trained an SVM classifier using the training set with an RBF kernel.

**Model Evaluation:**
Evaluated the model's accuracy on the testing set.

**Dependencies**
pandas
scikit-learn
