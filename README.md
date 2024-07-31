# Forest Cover Type Analysis

This repository contains the project for analyzing and classifying forest cover types using various clustering and classification algorithms. The project follows the guidelines provided and includes implementations of different methods along with their evaluations.

## Project Structure

- **Part I: Clustering**
    - Load the dataset using the scikit-learn interface.
    - Apply at least two clustering methods.
    - Evaluate the clustering methods using internal and external evaluation metrics.
    - Optimize the parameters of the clustering methods.
    - Clearly separate code for training and evaluation.

- **Part II: Classification**
    - Apply at least two classification methods.
    - Split the data into training (70%) and testing (30%).
    - Evaluate the classification approaches using metrics such as Balanced Accuracy, Precision, Recall, F1-Score, and ROC AUC.
    - Plot ROC curves and confusion matrices for comparison.
    - Optimize the parameters of the classification methods.
    - Clearly separate code for training and evaluation.

## Dataset

The dataset used in this project is the Forest Cover Type dataset, which contains information about different types of forest cover.

## Clustering Methods Used

We used the following clustering algorithms:
- K-Means Clustering
- Gaussian Mixture Model (GMM)
- DBSCAN
- Birch Clustering
- Mini Batch K-Means

### Evaluation Metrics

The clustering algorithms were evaluated using:
- Silhouette Coefficient
- Calinski-Harabasz Index
- Davies-Bouldin Index
- Adjusted Rand Index
- Adjusted Mutual Information

## Classification Methods Used

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes Classifier

### Evaluation Metrics

The classification algorithms were evaluated using:
- Balanced Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

## Results

### Clustering
- The best performing clustering algorithm was **DBSCAN** with the highest Adjusted Rand Index and Adjusted Mutual Information scores.

### Classification
- **Random Forest** achieved the highest scores across all internal evaluation metrics, making it the best classifier for this dataset.
- 
## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Patric-1613/Forest-Cover-Type-Analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook forest_cover_type_analysis.ipynb
    ```

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Dataset Source](https://archive.ics.uci.edu/ml/datasets/Covertype)
