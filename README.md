# recipe-recommendation-project

This project is a machine learning-based recipe recommendation system. It uses data science techniques and machine learning algorithms to recommend recipes based on user preferences.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Dependencies](#dependencies)

---

## Project Overview

The goal of this project is to recommend recipes based on user preferences. It includes data preprocessing, model training, evaluation, and recipe recommendation functionalities. 

The project is implemented in Python, using libraries such as `pandas`, `numpy`, and `scikit-learn`. 

---

## Dataset

- Source: [Food.com Recipes and Interactions Dataset](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)
- Description: Contains recipe details (ingredients, cooking time, etc.) and user interaction data for personalized recommendations.
  
---

## Features

- **Data Processing**: Cleans and prepares recipe data (ingredients, cooking time, etc.) for analysis.
- **Feature Engineering**: Converts recipe ingredients into TF-IDF features and reduces dimensions using SVD.
- **Model Training**:
    - Implements **Cosine Similarity**, **KNN**, and **NMF** for recipe recommendations.
- **Evaluation**: Measures recommendation performance using Precision at K and diversity metrics.
- **Recommendations**: Suggests recipes based on input ingredients provided by the user.

---

## Results

- The project compares three recommendation methods: Cosine Similarity, KNN, and NMF.
- **Best Performing Model**: Cosine Similarity with Precision@K = 1.0.
- **Diversity**: KNN and NMF provide a balance between precision and diverse recipe suggestions.

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/recipe-recommendation-project.git
    ```

2. Navigate to the project folder:
    ```bash
    cd recipe-recommendation-project
    ```

3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

1. Open the Jupyter notebook file in the `notebooks/` folder:
    ```bash
    jupyter notebook notebooks/recipe_recommendation_project.ipynb
    ```

2. Follow the step-by-step instructions in the notebook to run the project.

---

## Dependencies

The project uses the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `jupyter`

Install all dependencies using:
```bash
pip install -r requirements.txt
