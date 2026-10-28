Sentiment Analysis on Movie Reviews
An Introduction to Machine Learning course project at Prince Mohammad Bin Fahd University (PMU).
Overview
This project aims to classify IMDb movie reviews as positive or negative, comparing traditional machine learning approaches with a transformer-based model.

Status: In progress. Model training and evaluation results will be added after experiments are completed.
Dataset
The project uses the IMDb Movie Reviews Dataset specified in the course project brief. Each record contains review text and a sentiment label.
- review: the movie review text
- sentiment: the positive or negative label
Download the dataset from the link in the course brief and extract the archive. Keep the original CSV for loading into the notebook. The dataset source URL and observed dataset statistics will be documented in the completed notebook.
Workflow
1. Load and explore the dataset.
2. Visualize sentiment counts and review lengths.
3. Preprocess text and address missing values and duplicate reviews.
4. Split the data into training and test sets, keeping duplicate reviews out of separate splits.
5. Use TF-IDF features for traditional models and BERT tokenization for the transformer model. Fit learned preprocessing on training data only.
6. Train and compare Naive Bayes, Logistic Regression, and BERT.
7. Tune hyperparameters using training/validation data.
8. Evaluate the final models on held-out test data and discuss their errors and limitations.
Planned Evaluation
- Accuracy
- Precision, recall, and F1-score
- Confusion matrices
Getting Started
1. Download or clone this repository.
2. Install Jupyter Notebook and the Python packages required by the notebook.
3. Place the extracted dataset in the notebook folder, or update the dataset path in the loading cell.
4. Open the project's .ipynb file in Jupyter Notebook.
5. Run cells from top to bottom.
Initial exploration and visualization use pandas, matplotlib, and seaborn. Traditional model training will use scikit-learn. Additional BERT dependencies and runtime instructions will be documented when that stage is implemented.

Google Colab can also open the notebook. Upload the dataset to the active runtime and update its path as needed.
Results
Pending completion of model training and evaluation. No performance results are claimed yet.
Academic Context
AINT 3411 — Introduction to Machine Learning, Fall 2026.

Created for educational purposes at PMU. Team details are recorded in the notebook.
