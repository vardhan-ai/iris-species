# iris-species
Imports required libraries such as pandas, scikit-learn, matplotlib, and seaborn. Loads the Iris dataset from a CSV file through pd.read_csv('Iris.csv'). Inspects the dataset: Prints the shape (number of rows and columns) using df_iris.shape. Displays the distribution of Iris species using sns.countplot. Verifies for missing values using df_iris.isnull().sum(). Inspects data types of columns using df_iris.dtypes. Generates box plots for numerical features ('SepalLengthCm', 'SepalWidthCm', 'PetalLengthCm', 'PetalWidthCm') to display their distributions and possible outliers. Computes and plots the correlation matrix of numerical features with sns.heatmap. Data Preprocessing:

Scales numerical features with MinMaxScaler to a common scale (0-1). Divides the data into training and testing sets with train_test_split having a test size of 20% and random state of 42. Model Training and Evaluation:

Trains and creates four K-Nearest Neighbors (KNN) classifiers with varying n_neighbors values (1, 3, 5, 7). Fits every KNN model to training data using knn.fit(X_train, y_train). The code ends by printing model object description to console. Data Preprocessing:

Scales numerical features with MinMaxScaler to a common scale (0-1). Divides the data into training and testing sets with train_test_split having a test size of 20% and random state of 42. Model Training and Evaluation:

Trains and creates four K-Nearest Neighbors (KNN) classifiers with varying n_neighbors values (1, 3, 5, 7). Fits every KNN model to training data using knn.fit(X_train, y_train). The code ends by printing model object description to console.
