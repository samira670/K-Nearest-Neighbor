k-Nearest Neighbors (k-NN) Classification Example
This code demonstrates how to implement the k-Nearest Neighbors (k-NN) algorithm using Python libraries such as scikit-learn, pandas, and numpy. The workflow includes:

Data Preparation: The mtcars.csv dataset is loaded and preprocessed. Four features (mpg, disp, hp, wt) are selected as predictors, and am (automatic/manual transmission) is used as the target variable.

Data Scaling: Features are standardized using preprocessing.scale to normalize the input variables.

Train-Test Split: The dataset is split into training and testing sets using an 80/20 ratio with a fixed random state to ensure reproducibility.

Model Training: A KNeighborsClassifier model is instantiated and trained on the training data.

Prediction and Evaluation: The model predicts the target values for the test set. The performance is evaluated using classification metrics such as precision, recall, and F1-score,
