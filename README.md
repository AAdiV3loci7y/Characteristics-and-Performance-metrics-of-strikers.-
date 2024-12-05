# Characteristics-and-Performance-metrics-of-strikers.-
The project involves utilizing data analytics techniques to explore and understand the characteristics and performance metrics of strikers. It will cover a complete picture of real-world data analytics application in python programming language.

Let's Jump Right in!

# Strikers Performance Analysis Project

## Overview

This project leverages **sports data analytics** to analyze the performance of football strikers and classify them into different categories based on their contributions and engagement levels. The analysis aims to predict the type of striker (e.g., "Best Strikers" or "Regular Strikers") using machine learning techniques like **Logistic Regression**.

This repository includes:
- The **dataset** in `.xlsx` format, containing detailed performance metrics of 500 strikers.
- A **Jupyter Notebook** that outlines the entire data preprocessing, analysis, clustering, feature engineering, model training, evaluation, and visualization.

## Features of the Project
1. **Data Preprocessing**:
   - Missing value handling.
   - Encoding categorical variables (e.g., Footedness, Marital Status, and Nationality).
   - Scaling numerical features for consistency.

2. **Clustering Analysis**:
   - Used clustering to group strikers based on performance.
   - Created a feature mapping between "Best Strikers" and "Regular Strikers."

3. **Feature Engineering**:
   - Feature selection: Extracted relevant features like "Goals Scored," "Assists," "Shot Accuracy," and others.
   - Engineered the `Strikers types` column to classify strikers into:
     - `1` → **Best Strikers**
     - `0` → **Regular Strikers**

4. **Machine Learning**:
   - Logistic Regression Model to predict striker types.
   - Model Evaluation:
     - Confusion Matrix visualization.
     - Accuracy score calculation.

5. **Exploratory Data Analysis**:
   - Visualized the confusion matrix for classification.
   - Explored the contribution scores of strikers across clusters.
   - Analyzed demographics, including left-footed players from different nationalities (e.g., France).

## Repository Contents

1. **`Sports_Data.xlsx`**:
   - The dataset used for the analysis.
   - Contains performance metrics for 500 football strikers, including their goals scored, assists, and engagement levels.

2. **`Sports Data Analytics.ipynb`**:
   - Jupyter Notebook containing the Python code for:
     - Data preprocessing.
     - Clustering and feature engineering.
     - Machine learning model implementation.
     - Model evaluation with performance metrics.

3. **Generated Visualizations**:
   - Confusion matrix visualizing model predictions.
   - Clustering and performance insights.

## Requirements

To run the notebook and reproduce the analysis, the following Python libraries are required:

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
```

You can install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Key Results
- **Logistic Regression Accuracy**: The model achieved a high accuracy in predicting striker types.
- **Confusion Matrix Analysis**:
  - Predicted **55 regular strikers** correctly.
  - Predicted **40 best strikers** correctly.
  - Incorrectly classified 5 best strikers as regular.
- **Cluster Analysis**: Grouped strikers based on performance metrics to uncover hidden patterns.

## How to Use

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your_username/strikers-performance-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd strikers-performance-analysis
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Sports Data Analytics.ipynb"
   ```

4. Explore and run each section of the notebook to perform data analysis and model training.

## Contributions

Feel free to fork this repository and contribute improvements. Suggestions for extending the analysis or using advanced machine learning techniques are always welcome.

## Acknowledgments

## Acknowledgments

This project is powered by data-driven insights into football performance metrics. A special thanks to **Shahriar's Sight Academy** for providing the dataset through their comprehensive course, *Learn Excel, MySQL, Python, Power BI, ChatGPT for A-Z Data Analysis: Become a Full-Packed Data Analyst [5 Courses in 1]*. The course served as a valuable resource for enhancing data analysis skills and guided the methodology for this project.
