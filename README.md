Twitter Sentiment Analysis

This repository contains the code and resources for performing sentiment analysis on Twitter data. The project uses a Random Forest Classifier to classify sentiments and employs SMOTE to handle imbalanced classes. The notebook includes data preprocessing, model training, hyperparameter tuning, and comprehensive visualizations to understand the model’s performance.

Repository Contents

	•	notebook-1.ipynb: Jupyter notebook containing the complete workflow for sentiment analysis, including data preprocessing, model training, evaluation, and visualization.
	•	train.csv: Dataset used for training and evaluating the model (if you plan to include the dataset in the repo).
	•	test.csv: Dataset used for testing the model (if applicable).

Features

	•	Data Preprocessing: Clean and preprocess Twitter text data.
	•	Model Training: Train a Random Forest Classifier with hyperparameter tuning using GridSearchCV.
	•	Imbalanced Data Handling: Use SMOTE to balance the classes.
	•	Evaluation: Assess model performance using accuracy, classification report, and confusion matrix.
	•	Visualizations: Visualize class distribution and feature importance.

Visualizations

	•	Class Distribution Pie Chart: Shows the proportion of each sentiment class in the dataset.
	•	Confusion Matrix: Visual representation of the model’s performance.
	•	Feature Importance Plot: Highlights the most significant features used by the model.

Results

	•	Accuracy: The model achieved an accuracy of 73.5% on the test set.

 Usage

This project is intended for educational purposes and as a demonstration of sentiment analysis techniques on social media data. Feel free to use, modify, and extend the code for your own projects.

License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

Feel free to customize this description based on the specifics of your project and any additional details you might want to include.
