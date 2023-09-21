# Consumer-Complaint-Text-Classification
A Text Classification project on consumer complaint dataset (https://catalog.data.gov/dataset/consumer-complaint-database)
---



## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Setup and Requirements](#setup-and-requirements)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Predictions](#predictions)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project demonstrates the process of performing text classification on the Consumer Complaints dataset. The goal is to categorize consumer complaints into predefined categories, including Credit reporting, repair, or other, Debt collection, Consumer Loan, and Mortgage.

The project includes the following key steps:
1. Exploratory Data Analysis (EDA) and Feature Engineering
2. Text Pre-Processing
3. Selection of Multi-Classification Model
4. Comparison of Model Performance
5. Model Evaluation
6. Making Predictions

## Dataset

The dataset used in this project is the Consumer Complaints dataset, which can be obtained from [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database). It contains consumer complaints and their corresponding categories.

## Project Structure

The project directory is organized as follows:
- `complaints.csv`: The dataset file.
- `Customer Complain Text Classification.ipynb`: Jupyter Notebook containing the code for the entire project.
- `README.md`: This README file.


## Setup and Requirements

To run the project, you will need the following dependencies:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- NLTK
- SciPy
- scikit-learn

You can install the required packages using the following command:

```bash
pip install numpy pandas matplotlib seaborn nltk scipy scikit-learn
```

Additionally, make sure to download NLTK data by running the following Python code in your Jupyter Notebook or Python environment:

```python
import nltk
nltk.download('punkt')
```

These dependencies are necessary to execute the code and reproduce the results presented in the project.

## Usage

1. Clone the project repository to your local machine.
2. Navigate to the project directory.

```bash
git clone <repository_url>
cd Consumer-Complaint-Text-Classification
```

3. Open the Jupyter Notebook `Consumer-Complaint-Text-Classification.ipynb` to access the project code and follow the step-by-step instructions.

## Exploratory Data Analysis (EDA)

The EDA section provides insights into the dataset, including data distribution, class distribution, and visualizations of key statistics.

## Feature Engineering

This section covers text pre-processing, including TF-IDF vectorization and feature selection.

## Model Building

Multiple machine learning models are implemented and compared for text classification, including Random Forest, LinearSVC, Multinomial Naive Bayes, and Logistic Regression.

## Model Evaluation

The models' performance is evaluated using various metrics such as accuracy, confusion matrix, and classification report.

## Predictions

You can make predictions on new text data using the trained model.

## Contributing

If you would like to contribute to this project, please open an issue or create a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
