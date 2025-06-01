🎬 Movie Recommendation System using Deep Learning
📌 Project Overview
This project implements a movie recommendation system using Neural Collaborative Filtering (NCF) with PyTorch. It uses the MovieLens 100k dataset to predict user ratings based on user and movie embeddings.

📁 Dataset
Source: MovieLens 100k

Size: 100,000 ratings

Users: 943

Movies: 1,682

🛠️ Methodology
Data Processing: Ratings are loaded and split into train/test sets.

Model:

Embedding layers for users and movies

Dot product of embeddings to predict ratings

Output scaled to the 1–5 range using sigmoid

Loss Function: Mean Squared Error (MSELoss)

Optimizer: Adam

Evaluation Metric: Root Mean Square Error (RMSE)

📊 Results
The model achieved a progressively lower RMSE on the validation set with each epoch.

Demonstrated effective collaborative filtering using deep learning.

📈 Future Work
Add bias terms for user/movie

Use deeper network layers

Incorporate content-based features (e.g., genres, tags)

📚 Tools & Libraries
Python

PyTorch

Pandas, NumPy, Scikit-learn

Google Colab

