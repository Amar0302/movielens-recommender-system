# Recommender System Project

## Introduction

This project focuses on building and evaluating an item-based collaborative filtering recommender system using the MovieLens dataset. The objective is to create a system that can predict user ratings for movies and recommend new movies to users based on their viewing history.

## Features

- **Data Preprocessing**: Cleaning and merging MovieLens dataset files to prepare for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing data to understand user rating patterns and genre preferences.
- **Recommendation Model**: Implementing an item-based collaborative filtering model to predict movie ratings and recommend movies.
- **Matrix Normalization**: Standardizing user-item rating data to improve model performance.
- **Similarity Matrix**: Computing item similarity using Pearson correlation to identify movies similar to those a user likes.

## Installation and Setup

To run this notebook, ensure you have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn
```

Clone this repository to your local machine:

```bash
git clone https://github.com/Amar0302/movielens-recommender-system
```

Navigate to the project directory and start Jupyter Notebook to open the `recommender-system.ipynb` notebook:

```bash
jupyter notebook
```

## Data

The dataset used in this project is the MovieLens Latest Small dataset, which includes:
- **`ratings.csv`**: User ratings for movies.
- **`movies.csv`**: Movie titles and genres.

This project involves preprocessing steps like merging datasets and filtering movies with fewer than 100 ratings.

## Usage

Follow these steps within the Jupyter Notebook:

1. **Data Preprocessing**: Merge `ratings.csv` and `movies.csv`, and filter data as needed.
2. **EDA**: Conduct exploratory data analysis to understand the dataset.
3. **Build the Recommender**: Follow the notebook sections to build the recommender system.
4. **Evaluate**: Use the provided functions to predict ratings and recommend movies.

## Methodology

The recommender system uses an item-based collaborative filtering approach, focusing on finding similarities between items (movies) based on user ratings. The steps include:

- Creating a user-item matrix.
- Normalizing the matrix to center data around 0.
- Computing an item similarity matrix using Pearson correlation.
- Predicting user ratings for movies and recommending new movies based on similarities.

## Results

The system demonstrates how to predict user ratings for specific movies and generate movie recommendations. The notebook includes examples of predicting a rating for a movie for a specific user and generating a list of recommended movies.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- MovieLens for providing the dataset.



