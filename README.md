# K-Nearest_Decision-Tree
This project implements and evaluates two fundamental machine learning algorithms: K-Nearest Neighbors (KNN) and Decision Trees. These algorithms are applied to a subset of the Iris dataset, focusing on binary classification between the Versicolor and Virginica species. The project aims to compare algorithm performance under different configurations and methodologies, providing insights into their strengths, limitations, and practical applications.

# Machine Learning - KNN and Decision Trees
This project includes two machine learning algorithms implemented in Python:

1. **K-Nearest Neighbors (KNN)**:
   - Implements a KNN classifier for binary classification.
   - Supports different values for `k` (number of neighbors) and `p` (Minkowski distance metric).
   - Evaluates the classifier's performance using repeated random sampling.

2. **Decision Trees**:
   - Two approaches to build decision trees for binary classification:
     - **Brute-force**: Explores all possible splits up to `k` levels and selects the tree with the minimum error.
     - **Binary Entropy**: Constructs the tree by recursively splitting nodes based on entropy minimization.
   - Both methods are implemented for a maximum depth of `k=3`.

## Files in this repository
- `knn.py`: Python implementation of the K-Nearest Neighbors algorithm.
- `decision_tree.py`: Python implementation of the Decision Tree algorithm with both brute-force and binary entropy approaches.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Machine_Learning_KNN_and_Decision_Trees.git



