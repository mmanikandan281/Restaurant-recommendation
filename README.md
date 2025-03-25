# Restaurant Recommendation System

## Overview
This project implements a restaurant recommendation system using content-based filtering. The system suggests restaurants based on user preferences such as cuisine type, price range, and location.

## Features
- **Data Preprocessing**: Handles missing values and encodes categorical variables.
- **Feature Engineering**: Extracts useful features such as cuisine popularity and price range category.
- **Content-Based Filtering**: Uses cosine similarity to recommend restaurants similar to user preferences.
- **Evaluation Metrics**: Measures recommendation accuracy using precision@k.

## Dataset
The dataset includes information about various restaurants, such as:
- Cuisine types
- Price range
- Location
- User ratings

## Installation
### Requirements:
- Python 3.x
- pandas
- scikit-learn
- numpy

### Setup:
1. Clone this repository:
   ```bash
   git clone https://github.com/mmanikandan281/Restaurant-recommendation.git
   ```
## Usage
1. Load the dataset
2. Preprocess and clean the data.
3. Encode categorical features using one-hot encoding or label encoding.
4. Implement content-based filtering using cosine similarity.
5. Generate and evaluate recommendations.

## Evaluation
The system is evaluated using the precision@k metric, which measures the percentage of relevant recommendations among the top-k results. The system currently achieves a precision@k score of 0.67.


## Google Colab Link
You can run the project on Google Colab using the following link:
[Google Colab Notebook](https://colab.research.google.com/drive/1771Lq2LMB8rqiSp_DE22WAHVkrflIfdq?usp=sharing)

## Developed By
**Manikandan M**

