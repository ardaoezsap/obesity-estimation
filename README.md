# Estimation of Obesity Levels

## Project Overview
This project analyzes an obesity dataset to predict obesity levels based on various factors such as eating habits, physical activity, and demographics. The goal is to preprocess the data, engineer features, and apply machine learning models to accurately classify individuals into different obesity categories.

## Dataset Overview
The dataset contains multiple features related to diet, lifestyle, and body measurements. Some of the key attributes include:
- **Gender**
- **Age**
- **Height & Weight**
- **Family history with overweight**
- **Eating habits (frequency of consumption, water intake, etc.)**
- **Physical activity level**
- **Smoking and alcohol consumption**
- **Transportation habits**

The target variable, `NObeyesdad`, classifies individuals into six obesity categories:
1. Insufficient Weight
2. Normal Weight
3. Overweight Level I
4. Overweight Level II
5. Obesity Type I
6. Obesity Type II
7. Obesity Type III

## Project Workflow
### 1. **Data Preprocessing**
- **Handling missing values**: Ensure the dataset has no null values.
- **Encoding categorical variables**: Convert categorical features using one-hot encoding.
- **Feature scaling**: Normalize numerical values for optimal model performance.

### 2. **Feature Engineering**
- **Convert obesity categories to numerical values**
- **Extract meaningful insights from existing features**

### 3. **Model Selection & Training**
- **Split dataset**: Train-Test split (80-20 ratio)
- **Apply Machine Learning models**: Logistic Regression, RandomForestClassifier, GradientBoostingClassifier
- **Hyperparameter tuning**: Use GridSearchCV to optimize model performance

### 4. **Model Evaluation**
- **Accuracy Score**: Evaluate model performance
- **Classification Report**: Analyze precision, recall, and F1-score
- **Confusion Matrix**: Assess misclassifications across obesity levels

## Results
After applying machine learning techniques, the final model achieves an accuracy of **94%** in classifying obesity levels. The classification report highlights strong performance across all categories, with high precision and recall.

## Installation & Requirements
To run this project, install the necessary dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ardaoezsap/obesity-estimation.git
   ```
2. Run the Jupyter notebook or script:
   ```bash
   jupyter notebook estimation_of_obesity_levels.ipynb
   ```

## Future Enhancements
- **Experiment with deep learning models** like Neural Networks
- **Implement additional feature selection techniques** to improve accuracy
- **Enhance interpretability** using SHAP and feature importance analysis
- **Optimize dataset balancing techniques** to improve classification for minority classes

## Contributors
- **Arda Özsap** (ardaozsap03@gmail.com)


## License
This project is licensed under the MIT License.