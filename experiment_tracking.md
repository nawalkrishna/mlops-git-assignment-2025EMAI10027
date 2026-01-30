# Manual Experiment Tracking Table

| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|--------------|-----------|----------------|---------------------|------------------|------------------|-----------|-----------|
| EXP-01 | Decision Tree | Default | None | All features | 80/20 | 0.97 | 0.99 |
| EXP-02 | Decision Tree | Max depth = 5 | Scaling | Selected | 80/20 | 0.98 | 0.99 |
| EXP-03 | Random Forest | 100 trees | Scaling | Selected | 80/20 | 0.99 | 1.00 |
| EXP-04 | SVM | RBF kernel | Scaling | PCA | 80/20 | 0.98 | 0.99 |
| EXP-05 | KNN | k=5 | Scaling | All features | 80/20 | 0.95 | 0.97 |

