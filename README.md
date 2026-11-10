# Applied Machine Learning: Initial Project

Solo project for the Applied Machine Learning course (2024) at the Niels Bohr Institute, University of Copenhagen.

The task was to apply classification, regression and clustering to high-dimensional data from particle collisions at CERN's LHC. The project scored 98/100.

## Models

- **Classification:** XGBoost, scikit-learn MLPClassifier and a TensorFlow neural network
- **Regression:** Random forest and a TensorFlow neural network
- **Clustering:** K-means, with PCA and UMAP for visualisation

## Results

| Task | Best model | Score |
| --- | --- | --- |
| Classification | XGBoost | 97.8% accuracy, AUC 0.995 |
| Regression | Random forest | Relative MAE 0.30 (validation) |
| Clustering | K-means | 75.2% accuracy |

## Files

| File | Description |
| --- | --- |
| `classification_tree.ipynb` | XGBoost classifier |
| `classification_MLPClassifier_NN.ipynb` | MLPClassifier and TensorFlow classifier |
| `regression.ipynb` | Random forest and TensorFlow regression |
| `clustering.ipynb` | K-means clustering |
| `solutions/` | Submitted predictions, variable lists and method descriptions |
| `report_on_initial_project_TheodoreBeevers.pdf` | Grading report |

## License

MIT
