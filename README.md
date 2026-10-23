# EmployeeAttrition

Employee Attrition: what are the tipping points that lead to employee turnover

4 Jupyter Notebooks included, broken down by milestone workflow. Run through each to get a full picture plus all work completed as part of this study. For just an overview of the whole process just run Milestone4.

Complete write up available in the EmployeeAttrition.pdf

## Data Set: 

IBM HR Analytics Employee Attrition & Performance Dataset from Kaggle

Includes: Exploratory Data Analysis, visualizations, and feature engineering

## EDA

- Monthly Income vs Attrition: box plot
- Overtime vs Attrition: stacked bar chart
- Correlation Heatmap
- Attrition segmented by Martial Status: violin plot

- feature pruning
- feature engineering
- consolidation of features
- one hot encoding on categorical features and create dummy variables

## Evaluation Metrics

- Imbalanced dataset (84/16)
- F1-Score
- Recall


## Models

- Logistic Regression
- Random Forest Classifier
- Tuned Logistic Regression
  - Balanced Weights
  - SMOTE
 
| Model | Technique | recall | Precision | F1-Score | Accuracy |
| -- | -- | -- | -- | -- | -- |
| Baseline | Default Logistic Regression (0.5) | 0.36 | 0.65 | 0.47 | 87% |
| Tuned | Logistic Regression (0.3) | 0.51 | 0.51 | 0.51 | 84% |
| Refinement 1 | Balanced Weights | 0.64 | 0.37 | .47 | 77% |
| Refinement 2 | SMOTE | 0.49 | 0.41 | 0.45 | 81% |

## Techniques used

- Tuning
- `class_weight='balanced'`
- SMOTE

___

## How To

- pull each milestone to slowly build the full study, or pull milestone 4 and have a condensed view.
- Data is the included csv file
- PDF is for write up of results/study
