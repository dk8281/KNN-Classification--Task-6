# KNN-Classification--Task-6
📌 Objective
Implement K-Nearest Neighbors (KNN) classification on the Iris dataset, experiment with different values of K, evaluate performance, and visualize decision boundaries.

🛠 Tools & Libraries
Python
Pandas – Data loading & preprocessing
Matplotlib / Seaborn – Data visualization
scikit-learn – Model building & evaluation

📂 Steps Performed
Loaded Dataset (Iris.csv).
Exploratory Data Analysis (EDA)
Checked dataset info, class distribution.
Plotted pairplot to see feature separation.
Preprocessing
Dropped unnecessary columns (Id).
Converted features to numeric and handled missing values (if any).
Normalized features using StandardScaler.

Model Training
Used KNeighborsClassifier from scikit-learn.
Tested multiple values of K (1–20) to find the best accuracy.

Evaluation
Plotted Accuracy vs K graph.
Generated Confusion Matrix and Classification Report.
Visualization
Plotted simple decision boundaries using the first two features.

📊 Results
Achieved high accuracy ( >95% ) on the test set.
Best K value chosen based on highest accuracy.
Decision boundary plot shows clear separation of classes.
