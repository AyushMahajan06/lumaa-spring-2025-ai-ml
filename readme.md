# Netflix Content Recommender

This project implements a content-based recommendation system for Netflix TV shows and movies using TF-IDF and cosine similarity.

## Dataset

The dataset used is a sample of 450 entries from the Netflix TV Shows and Movies dataset available on Kaggle:
https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?resource=download

The sample data is stored in `titles.csv` in the project directory.

### Requirements

- Python 3.7+
- pandas
- scikit-learn

### Installation

1. Clone this repository:
git clone https://github.com/AyushMahajan06/lumaa-spring-2025-ai-ml.git

2. Open the Jupyter notebook

3. Run all the cells in the notebook

4. Input the desired description

The system returns the top 5 similar items with their titles, descriptions, and similarity scores.
The similarity score ranges from 0 to 1, where 1 represents perfect similarity and 0 indicates no similarity. Higher scores mean more relevant recommendations based on the input description.
