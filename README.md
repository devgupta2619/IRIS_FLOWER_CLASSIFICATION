

# Iris Flower Classification🪻

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) 
![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.1-orange)

## Project Overview

This project implements a classification model to predict the species of Iris flowers based on four features: sepal length, sepal width, petal length, and petal width. Using the famous Iris dataset, we train machine learning models to classify flowers into one of three species: Setosa, Versicolor, or Virginica. The project walks through data exploration, model training, evaluation, and prediction steps, providing an end-to-end approach to classification problems.

## Dataset Information

- **Source:** The dataset used is the Iris Flower Dataset, a popular dataset for machine learning classification tasks, containing 150 samples across three species.
- **Columns:**
  - `Sepal Length (cm)`
  - `Sepal Width (cm)`
  - `Petal Length (cm)`
  - `Petal Width (cm)`
  - `Species`: The class label representing the species (Setosa, Versicolor, Virginica)

## Data Analysis and Visualization

### Key Insights

1. **Data Distribution:**
   - The dataset contains balanced classes with 50 samples of each species.
   - Sepal and petal measurements provide clear distinctions between Setosa and the other two species, while Versicolor and Virginica exhibit overlapping feature values.
   
2. **Correlation Between Features:**
   - Strong correlations were observed between petal length and petal width, as well as sepal length and petal length, making these features critical for classification.
   
3. **Species Separation:**
   - Using pair plots, Setosa can be clearly separated from Versicolor and Virginica, while the latter two require more sophisticated modeling for accurate classification.

### Model Training and Evaluation

We trained and evaluated two classification algorithms:

- **Naive Bayes Classifier**
- **MLP Classifier**


The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The MLP Classifier model performed the best with an accuracy score of over 100%, making it the optimal choice for this task.

### Visualizations

- **Pair Plot of Features:** A scatter plot matrix showing the relationship between the four features and their correlation with each species.
- **Confusion Matrix:** Visual representation of the classification results, showing how well the models performed across the three species.

## Libraries Used

- **Python:** ![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
- **Pandas:** For data manipulation and analysis. ![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
- **NumPy:** For numerical operations. ![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
- **Matplotlib:** For visualizations. ![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
- **Seaborn:** For statistical data visualization. ![Seaborn](https://img.shields.io/badge/seaborn-0.11.1-orange)
- **Scikit-learn:** For machine learning algorithms. ![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.1-orange)

## Conclusion

This project demonstrated the use of multiple machine learning algorithms for classification tasks, particularly in distinguishing between flower species based on their features. The MLP classifier was the most effective, achieving the highest accuracy.

## How to Use This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/devgupta2619/IRIS_FLOWER_CLASSIFICATION.git
   ```

2. Install the necessary libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Run the Jupyter Notebook or Python script to see the analysis in action.

---
