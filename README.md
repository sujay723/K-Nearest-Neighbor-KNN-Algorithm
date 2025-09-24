# KNN Classifier on Iris Dataset 🌸

This project implements a **K-Nearest Neighbors (KNN)** classification
model using the famous **Iris dataset**.\
The model predicts the species of iris flowers based on sepal and petal
features, evaluates performance, and visualizes results.

------------------------------------------------------------------------

## 📂 Project Structure

-   `knn.py` → Main script containing data preprocessing, model
    training, evaluation, and visualization.

------------------------------------------------------------------------

## ⚙️ Features

-   Loads and explores the Iris dataset\
-   Handles missing values check\
-   Data standardization using **StandardScaler**\
-   Train-test split with **scikit-learn**\
-   Model training with **KNeighborsClassifier**\
-   Model evaluation using:
    -   Accuracy score
    -   Classification report
    -   Confusion matrix\
-   Data visualization with **Seaborn** and **Matplotlib**

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone the repository or download the file.

2.  Install dependencies:

    ``` bash
    pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
    ```

3.  Run the script:

    ``` bash
    python knn.py
    ```

------------------------------------------------------------------------

## 📊 Results

-   Accuracy on training and testing datasets\
-   Detailed classification report\
-   Confusion matrix visualization (heatmap)

------------------------------------------------------------------------

## 🛠️ Dependencies

-   Python 3.x\
-   pandas\
-   numpy\
-   matplotlib\
-   seaborn\
-   scikit-learn\
-   mlxtend

------------------------------------------------------------------------

## 📌 Notes

-   Make sure `IRIS.csv` is available in the same directory or update
    the file path inside `knn.py`.\
-   You can adjust the value of `n_neighbors` in `KNeighborsClassifier`
    for tuning model performance.

**Sujay Roy**
