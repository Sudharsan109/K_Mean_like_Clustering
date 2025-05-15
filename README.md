# K_Mean_like_Clustering
This project implements a custom version of the K-Means clustering algorithm in Python using only NumPy and basic Python tools—no machine learning libraries involved. It includes a unique feature: automatic feature weighting, which helps improve clustering performance by giving more importance to relevant features.
🔧 Key Features
Custom matrix class to handle CSV loading, standardization, and mathematical operations.

Min-Max Normalization to scale features between 0 and 1.

Weighted Euclidean Distance: Calculates distances using a dynamically adjusted weight vector for each feature.

Iterative Clustering: Cluster assignments and feature weights are updated until convergence.

Between and Within Cluster Separation: Used to update feature weights for more accurate clustering.

Flexible Testing: The script tests cluster sizes from K=2 to K=10, 20 times each, for robust evaluation.

📁 Project Structure
matrix class handles data operations

get_groups() function runs the weighted K-Means

run_test() runs clustering on the dataset (DataAnubavam.csv) and prints cluster sizes for each K

🧪 Use Case
This type of clustering is useful for datasets where not all features contribute equally. Feature weighting improves the performance by reducing the influence of noisy or irrelevant dimensions.
