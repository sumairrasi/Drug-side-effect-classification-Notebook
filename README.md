# Drug Side Effects Classification

## Table of Contents
- [Project Overview](#project-overview)
- [Data Overview](#data-overview)
- [Technologies Used](#technologies-used)
- [Implementation Steps](#implementation-steps)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

## Project Overview
This project aims to develop a machine learning model that classifies the side effects of a drug based on patient data. The notebook encompasses the complete workflow from exploratory data analysis (EDA) to model evaluation, demonstrating the steps necessary to preprocess the data, train the model, and assess its performance. This work is part of my internship at TCS, where I was tasked with building a reliable classification model using the provided dataset.

## Data Overview
The dataset used in this project consists of the following features: 
- **NAME**
- **GENDER**
- **DRUG NAME**
- **AGE**
- **RACE**
- **SIDE EFFECTS**
- **RACE_White**
- **RACE_Hispanic, White**
- **RACE_Black**
- **RACE_Unknown**
- **RACE_Hispanic, Black**
- **RACE_Other**
- **RACE_Asian, Other**
- **RACE_Asian Indian**
- **RACE_Chinese**

This data was sourced from TCS and provides insights into the side effects experienced by patients taking various drugs.

## Technologies Used
- Python
- Jupyter Notebook
- Libraries: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Implementation Steps
1. **Exploratory Data Analysis (EDA)**: 
   - Conducted an analysis to understand the dataset's structure and distribution of features.
   - Visualized relationships between different features and the target variable.

2. **Data Cleaning**: 
   - Identified and handled missing values and outliers.
   - Converted categorical variables into numerical formats where necessary.

3. **Data Preprocessing**: 
   - Normalized and scaled features for model training.
   - Split the dataset into training and testing sets to evaluate model performance effectively.

4. **Model Training**: 
   - Implemented various classification algorithms, including Logistic Classifier, KNN Classifier, Random Forest Classifier, and Decision Tree Classifier.
   - Tuned hyperparameters to optimize model performance.

5. **Model Testing and Evaluation**: 
   - Evaluated the model using metrics such as accuracy.
   - Visualized the results using confusion matrices and classification reports.

## Results
The final model achieved an accuracy of **98.04%** on the test dataset, demonstrating its effectiveness in classifying drug side effects. Detailed evaluation metrics are provided within the notebook.

## Future Work
Future enhancements to this project could include:
- Exploring additional feature engineering techniques to improve model performance.
- Experimenting with advanced models such as ensemble methods or deep learning approaches.
- Conducting a more extensive analysis to validate findings across different datasets.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
