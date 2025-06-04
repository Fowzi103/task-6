Task 6 - K-Nearest Neighbors (KNN) Classification Objective
The goal of this task is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. We will explore instance-based learning, apply feature normalization, evaluate model performance, and visualize decision boundaries.


- Sepal Length
- Sepal Width
- Petal Length
- Petal Width  
- Target: Iris-setosa, Iris-versicolor, Iris-virginica



 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib



 Steps Performed

1. Loaded the dataset from `iris.csv`.
2. Preprocessed data:
   - Separated features and target labels.
   - Normalized features using `StandardScaler`.
   - Encoded class labels using `LabelEncoder`.
3. Trained KNN classifier:
   - Used `KNeighborsClassifier` from `sklearn`.
   - Experimented with different values of `K` (e.g. 3, 5).
4. Evaluated model:
   - Accuracy score
   - Confusion matrix
5. Visualized decision boundary:
   - Used the first 2 features for 2D plotting.
   - Displayed how the KNN classifier divides the feature space.

