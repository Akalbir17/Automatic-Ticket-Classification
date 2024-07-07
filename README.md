# Automatic Ticket Classification

## Table of Contents
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Loading](#data-loading)
  - [Text Preprocessing](#text-preprocessing)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Feature Extraction](#feature-extraction)
  - [Topic Modelling](#topic-modelling)
  - [Model Building](#model-building)
  - [Model Training and Evaluation](#model-training-and-evaluation)
  - [Model Inference](#model-inference)
- [Results](#results)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)
- [Conclusion](#conclusion)

## Problem Statement
For a financial company, customer complaints are crucial as they indicate shortcomings in products and services. Efficiently resolving these complaints can minimize customer dissatisfaction and retain their loyalty. However, manually evaluating and assigning each ticket to the relevant department becomes tedious as the company grows.

The objective of this project is to automate the customer support tickets system for a financial company. By building a model that can classify customer complaints based on products/services, tickets can be segregated into relevant categories, enabling quick resolution of issues.

## Dataset
The dataset consists of customer complaint tickets, which are unstructured text data. The tickets need to be classified into the following categories:
- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

## Methodology

### Data Loading
- Load the customer complaint tickets dataset into a suitable data structure.

### Text Preprocessing
- Perform text preprocessing steps such as lowercasing, removing special characters, and tokenization.
- Handle missing values and remove any irrelevant information.

### Exploratory Data Analysis (EDA)
- Analyze the distribution of tickets across different categories.
- Visualize the frequency of words and phrases in the tickets.

### Feature Extraction
- Extract relevant features from the preprocessed text data.
- Techniques such as TF-IDF, word embeddings, or bag-of-words can be used.

### Topic Modelling
- Apply topic modeling techniques like Latent Dirichlet Allocation (LDA) to identify underlying topics in the tickets.
- Map each ticket to its respective department/category based on the identified topics.

### Model Building
- Build supervised learning models such as logistic regression, decision trees, or random forests.
- Use the extracted features and mapped categories as input to train the models.

### Model Training and Evaluation
- Split the data into training and testing sets.
- Train the supervised models on the training data.
- Evaluate the models using appropriate metrics such as accuracy, precision, recall, and F1-score.

### Model Inference
- Use the trained model to classify new customer complaint tickets into their relevant departments.

## Results
The following table summarizes the performance of different supervised models tested on the dataset:

| Model Name                | F1 Score (%) | Hyper Parameter Tuned F1 Score (%) |
|---------------------------|--------------|-----------------------------------|
| Logistic Regression       | 91.96        | 94.46                            |
| Decision Tree Classifier  | 78.50        | 80.43                            |
| Random Forest             | 81.70        | 81.60                            |
| Naive Bayes               | 67.75        | 78.17                            |
| Support Vector Machine    | 91.59        | 91.78                            |
| XGBoost                   | 89.74        | 92.16                            |
| CatBoost                  | 90.81        | 79.34                            |
| AdaBoost                  | 84.52        | 78.67                            |

The best-performing model achieved an F1-score of 94.46% after hyperparameter tuning.

## Requirements
- Python 3.7+
- pandas
- numpy
- scikit-learn
- nltk
- gensim
- matplotlib
- seaborn
- jupyter

## Usage
1. Clone the repository: git clone https://github.com/Akalbir17/Automatic-Ticket-Classification.git
   
2. Install the required dependencies: `pip install -r requirements.txt`

3. Open the Jupyter Notebook `notebooks/Automatic_Ticket_Classification_Notebook.ipynb`[1] and run the cells to preprocess the data, build the models, and evaluate their performance.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Conclusion
In this project, we developed an automated ticket classification system for a financial company. By leveraging NLP techniques and supervised learning models, we were able to classify customer complaint tickets into their relevant categories. The best-performing model achieved an F1-score of 94.46% after hyperparameter tuning. This system can significantly reduce the manual effort required in ticket assignment and improve the efficiency of customer support processes.
