# Face Recognizer

## Dataset Description

This dataset comprises images of various individuals, each represented by at least two pictures. For the purpose of this project, we have focused on individuals with a minimum of 150 images in the dataset, resulting in a selection of two distinct people.

## Project Description

This Python script aims to recognize different faces using Principal Component Analysis (PCA) for feature reduction and an MLP (Multi-Layer Perceptron) classifier for image classification. The following steps are performed:

1. Data is fetched from the dataset.
2. The dataset is split into training and testing sets.
3. Standard Scaling is applied to normalize the data.
4. Principal Component Analysis (PCA) is utilized to reduce the number of features.
5. An MLP classifier is employed to recognize and classify the images.

### Requirements

- Python
- NumPy
- pandas
- scikit-learn

### Usage

1. Make sure you have the required Python packages installed.
2. Run the script to perform face recognition.
3. The script will output accuracy scores for both the training and testing datasets.

### Results

- The script achieves desirable results on the training set without overfitting.
- The accuracy score on the test set is approximately 92%, indicating a satisfactory performance.
- A confusion matrix is included in the code to visualize and summarize the classification performance.

Please note that this script is a part of a larger project and can be integrated into more comprehensive face recognition systems or applications.
