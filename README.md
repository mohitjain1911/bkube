# Churn Prediction

This repository contains a machine learning project aimed at predicting customer churn. The project includes exploratory data analysis (EDA) and model building to understand and forecast which customers are likely to churn.

## Table of Contents

- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)
  
## Project Structure

- `Churn_EDA.ipynb`: This notebook contains the exploratory data analysis, where we explore the dataset, visualize important features, and gain insights into customer behavior.
- `Churn_Model.ipynb`: This notebook covers the machine learning part of the project. It includes data preprocessing, model selection, training, evaluation, and tuning.

## Dataset

The dataset used in this project is the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data) from Kaggle. It contains customer data with features such as tenure, service type, monthly charges, and more. The target variable is whether the customer has churned or not.

## Requirements

The project requires the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/bshan11/Churn-Prediction.git
```

2. Navigate to the project directory:
```bash
cd Churn-Prediction
```

3. Run the Jupyter notebooks to perform EDA and build the model:
```bash
jupyter notebook Churn_EDA.ipynb
jupyter notebook Churn_Model.ipynb
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
