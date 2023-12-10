# Chess Game Outcome Prediction using Apache Spark

This project performs an in-depth analysis on a dataset of over 20,000 chess games from Lichess.org to uncover insights related to game outcomes and build machine learning models to predict match results.

## Project Overview

The key aspects of this project include:

- Extensive exploratory data analysis on 20,058 chess games to understand factors influencing victory, defeat or draw
- Preprocessing data by handling null values, duplicates, outliers and converting categorical features
- Visualizations for intuitive analysis of player ratings, openings impact and other attributes   
- Feature engineering new attributes like game duration for additional context
- Dimensionality reduction using PCA for visual detection of patterns
- Training classification models like Logistic Regression, Random Forest and Neural Networks  
- Comparing model performance to predict game winner between white player, black player or draw   

## Tech Stack

**Language**: Python  
**Technologies**: Apache Spark, PySpark MLlib, Pandas, Matplotlib, Seaborn   
**Environment**: Jupyter Notebook  

## Getting Started  

### Prerequisites
- Apache Spark  
- Python 3
- Jupyter Notebook

### Installation

- Clone the repository
  ```bash
  git clone https://github.com/meric2/Chess-Game-Analysis/tree/main
  ```
  
- Install dependencies
  ```bash
  pip install -r requirements.txt
  ```
  
- Start Jupyter notebook
  ```bash
  jupyter notebook
  ```
  
- Open `chess_analysis.ipynb` notebook and run all cells


## Usage

The notebook covers:

- Loading and overview of chess games dataset
- Data inspection, preprocessing and feature engineering  
- Extensive EDA with interactive visualizations    
- Applying PCA for dimensionality reduction 
- Model training using PySpark MLlib algorithms  
- Performance evaluation of models with confusion matrix

It can serve as a reference for chess games analysis at scale and building machine learning pipelines with PySpark. 

## Contributors

- [Berkay Yıldız](https://github.com/berykay)
- [Zeynep Meriç Aşık](https://github.com/meric2)
