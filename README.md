# Heart Disease Analysis Using R

This project uses R programming to analyze a dataset related to heart disease. The analysis includes data exploration, visualization, and modeling to uncover insights and predict heart disease based on several medical features.

## Overview

The project includes:
- **Data Preprocessing**: Cleaning, handling missing values, and data transformations.
- **Exploratory Data Analysis (EDA)**: Statistical summaries and visualizations to understand the dataset.
- **Feature Engineering**: Creating normalized and one-hot encoded features for analysis.
- **Visualization**: Using `ggplot2` to create histograms, scatter plots, box plots, violin plots, and more.
- **Modeling**: Logistic regression and decision tree models for predicting heart disease status.
- **Statistical Tests**: Confidence intervals, t-tests, and correlation analysis to identify significant relationships.

## Prerequisites

### Libraries Used:
- `dplyr`: For data manipulation.
- `ggplot2`: For creating visualizations.
- `caret`: For feature importance.
- `corrplot`: For heatmap visualizations.
- `rpart`: For decision tree modeling.

Install these libraries using:
```R
install.packages(c("dplyr", "ggplot2", "caret", "corrplot", "rpart"))
```

## Dataset

The dataset is assumed to be stored in a file named `Heart.csv`. It includes columns such as:
- **Age**: Age of the individual.
- **Sex**: Gender of the individual (0 or 1).
- **RestBP**: Resting blood pressure.
- **Chol**: Cholesterol level.
- **ChestPain**: Type of chest pain experienced.
- **MaxHR**: Maximum heart rate achieved.
- **AHD**: Presence of heart disease (Yes/No).

Ensure the dataset is placed at the specified file path in the script or update the file path accordingly.

## Key Features

### Data Exploration:
- Summarizing the dataset using functions like `summary()` and `dim()`.
- Identifying missing values and performing data type conversions.

### Visualizations:
- Distribution of numerical variables (e.g., Age, RestBP, Chol).
- Box plots, violin plots, and scatter plots to observe relationships between variables.
- Correlation heatmaps to understand variable relationships.

### Feature Engineering:
- One-hot encoding for categorical columns like `ChestPain` and `Thal`.
- Normalizing columns such as `Age`, `RestBP`, and `Chol` to a 0-1 scale.

### Modeling:
- Logistic regression to predict the presence of heart disease.
- Decision tree models for feature importance ranking.
- Evaluation metrics like accuracy and confusion matrices.

### Statistical Analysis:
- Confidence intervals for average age in each heart disease group.
- T-tests to determine significant differences in cholesterol levels.

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open the script in your preferred R editor or IDE (e.g., RStudio).

3. Update the file path to your dataset if necessary.

4. Run the script to reproduce the analysis and visualizations.

## Results

The project identifies key factors influencing heart disease and provides visual insights and predictive models to assess heart disease likelihood.

## Contributions

Contributions are welcome! Feel free to submit pull requests or suggest improvements.


![Himage1](https://github.com/user-attachments/assets/ec42ad15-bd50-4255-bdea-7cb36c7beac7)
![Himage2](https://github.com/user-attachments/assets/3713fb77-1941-46cc-aa34-00f64bc1ffeb)
![Himage3](https://github.com/user-attachments/assets/bc3b63f0-24c3-4cbb-871a-047b3a06937c)
![Himage4](https://github.com/user-attachments/assets/6bc1335a-0f48-4e58-afce-f46bcfde96cd)
![Himage5](https://github.com/user-attachments/assets/6746d2b1-809e-40e6-b699-c9de6773f10b)
![Himage6](https://github.com/user-attachments/assets/8f340dce-0c0f-4bd1-9308-9d321b9d0be8)
![Himage7](https://github.com/user-attachments/assets/a431e69d-e231-4b7b-8178-47f09852f05b)
![Himage8](https://github.com/user-attachments/assets/fa574c98-aa36-4b0b-aef5-2ba77859ef00)
![Himage9](https://github.com/user-attachments/assets/c2beb3c0-c15b-4214-9cd0-b6357311cbea)
![Himage10](https://github.com/user-attachments/assets/0e3c4b22-4abc-4270-94bd-5d219b99195b)
![Himage11](https://github.com/user-attachments/assets/d68746c0-dccf-41b3-9cae-7d4a77459a57)




