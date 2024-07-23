# Green AI Credit Risk Assessment in P2P Lending

This repository hosts the implementation of a Machine Learning (ML) experiment aimed at credit risk assessment in Peer-to-Peer (P2P) lending platforms. It emphasizes the application of Green AI principles to minimize environmental impacts and enhance the transparency of ML models.

## Project Overview

The project explores the use of various ML models to predict loan defaults effectively while ensuring minimal environmental impact. Additionally, Explainable AI (XAI) techniques are utilized to increase the transparency of the decision-making processes of the models.

### Models Evaluated

- **XGBoost**
- **Random Forest**
- **Decision Trees**
- **Logistic Regression**

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Libraries: scikit-learn, XGBoost, CodeCarbon

### Installation

To set up your local environment:

```bash
# Clone the repository
git clone https://github.com/username/repository.git
# Navigate to the project directory
cd repository
```

## Experiment Details
### Data Source
The dataset is sourced from Bondora.com, available on Kaggle, including data on defaulted and non-defaulted loans from February 2009 to July 2021.

### Methodology
Data Preprocessing: Addressing missing values, encoding categorical variables, normalizing data.
Model Training: Hyperparameter tuning using GridSearchCV, validating models through k-fold cross-validation.
Sustainability Evaluation: Estimating CO2 emissions using the CodeCarbon library.
Transparency Evaluation: Applying SHAP and LIME for insights into the decision-making processes.
### Results
The models were assessed based on accuracy and environmental impact. Logistic Regression offered a good balance between accuracy and sustainability, whereas Random Forest achieved high accuracy but at a significant environmental cost.


### License
This project is licensed under the MIT License.

