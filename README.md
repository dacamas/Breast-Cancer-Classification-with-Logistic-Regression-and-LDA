# Breast-Cancer-Classification-with-Logistic-Regression-and-LDA

This project is part of the University of Colorado Boulder Master of Science (MSc) in Artificial Intelligence program and demonstrates classification techniques for predicting whether a breast tumor is malignant or benign using the Wisconsin Breast Cancer dataset.

Overview: The project follows a standard machine learning classification workflow including preprocessing, feature scaling, model training, and evaluation. A baseline Logistic Regression model and a Linear Discriminant Analysis (LDA) model are trained and compared. L2 regularization is then applied to improve generalization by shrinking coefficient magnitudes and reducing potential overfitting. The regularized model achieves an accuracy of 0.9825, outperforming both the baseline Logistic Regression (0.9737) and LDA (0.9561), with a ROC–AUC of 0.9974, indicating extremely strong classification performance.

Technologies Used: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn (for data processing, visualization, and machine learning)

Dataset: The dataset used is the Wisconsin Breast Cancer dataset, which contains diagnostic measurements of cell nuclei from breast tumor samples along with labels indicating whether the tumor is malignant or benign.
