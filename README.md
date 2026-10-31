# Data Science & AI Project Portfolio

An end-to-end portfolio organized by learning module. Each project folder contains a concise case-study summary and the complete solution or reference notebook.

## Portfolio map

| Module | Project | Core techniques |
|---|---|---|
| Foundations of AI | [Medicon Dose Testing](Foundations-of-AI/Medicon-Dose-Testing/) | Probability distributions, confidence intervals |
| Foundations of AI | [Mobile Internet Usage Analysis](Foundations-of-AI/Mobile-Internet-Usage-Analysis/) | Hypothesis testing, z-test |
| Data Analysis & Visualization | [Fantasy Sports Clustering Analysis](Data-Analysis-and-Visualization/Fantasy-Sports-Clustering-Analysis/) | EDA, clustering, PCA, K-Means |
| Machine Learning | [SuperKart Sales Prediction](Machine-Learning/SuperKart-Sales-Prediction/) | Regression, preprocessing, model tuning |
| Practical Data Science | [Hotel Booking Cancellation Prediction](Practical-Data-Science/Hotel-Booking-Cancellation-Prediction/) | Classification, decision trees, random forests |
| Deep Learning | [Food Image Classification](Deep-Learning/Food-Image-Classification/) | CNNs, image preprocessing, classification |
| Recommendation Systems | [Book Recommendation System](Recommendation-Systems/Book-Recommendation-System/) | Ranking, collaborative filtering, matrix factorization |

## Repository structure

Each module is a top-level directory and each project has:

- `README.md` — business problem, objective, approach, and key results
- `solution.ipynb` — complete analysis and solution code

Datasets are not committed because several are large or distributed separately by the course. Dataset names and expected inputs are documented in each notebook.

## Running the notebooks

1. Create a Python 3.10+ virtual environment.
2. Install the common packages with `pip install -r requirements.txt`.
3. Download the corresponding course dataset and update the notebook's data path.
4. Open the notebook in Jupyter or Google Colab and run the cells in order.

Some projects require optional packages such as `scikit-surprise`, `scikit-learn-extra`, or TensorFlow. Their notebooks include project-specific setup guidance.

## About

These projects demonstrate a progression from statistical reasoning and exploratory analysis through classical machine learning, deep learning, and personalized recommendation systems. The materials are organized as educational case studies for portfolio review.
