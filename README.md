# Iris Species Classification

## Objective
The goal of this project is to build a multiclass classification model using PyTorch to classify iris species based on various features from the Iris dataset.

## Dataset Description
The Iris dataset contains 150 samples of iris flowers with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable (species) can be one of three classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Steps to Run the Code
1. Clone the repository or download the project files.
2. Ensure you have the required dependencies installed (see Dependencies section).
3. Place the `iris.csv` file in the project directory.
4. Open the Jupyter Notebook file `iris_classification.ipynb`.
5. Run the notebook cells sequentially to execute the model training and evaluation process.

##Code Description
- Data Loading: The Iris dataset is loaded into a Pandas DataFrame, and the features (X) and target labels (y) are extracted.
- One-Hot Encoding: The target variable (species) is one-hot encoded to prepare it for training.
- Normalization: The features are normalized to ensure they are on a similar scale for better model performance.
- Train-Test Split: The dataset is split into training (80%) and validation (20%) sets.
- Neural Network Model: A neural network model is created using PyTorch with sufficient hidden layers to capture complex patterns in the data.
- Loss Function and Optimizer: The appropriate loss function (e.g., CrossEntropyLoss) and optimizer (e.g., Adam) are defined to train the model.
- Training Loop: The model is trained over a specified number of epochs, logging the training and validation losses, and calculating accuracy.
- Evaluation Metrics: After training, the model is evaluated using accuracy, confusion matrix, precision, recall, F1-score, and ROC-AUC curve.
- Visualizations: Training and validation loss are plotted, along with ROC curves for each class.
Evaluation Metrics
- The model is evaluated using:

1.Accuracy
2.Confusion Matrix
3.Precision, Recall, and F1-Score
4.ROC-AUC Curve for performance evaluation (using One-vs-Rest for multiclass)
5.Visualizations
During the training process, the following visualizations are generated:


