# student-stress
Mini-project fot the Introduction to Computational Intelligence course

# Student Stress Level Prediction using Fuzzy Logic

## Description
This project implements a Fuzzy Logic System to classify student stress levels based on several stress-related factors.

The model uses a tuned singleton fuzzy rule system built from the Student Stress Factors dataset.

## Dataset
Dataset source:
https://www.kaggle.com/datasets/samyakb/student-stress-factors

The dataset contains multiple factors affecting student stress levels, such as:
- Academic pressure
- Sleep quality
- Study load
- Social relationships
- Financial concerns
- Future career concerns

## Method
- Data preprocessing
- Fuzzy membership generation
- Singleton fuzzy rule creation
- Defuzzification
- Model evaluation using train-test split

## Stress Level Categories
| Stress Score | Category |
|-------------|----------|
| <= 2 | Low |
| 3 | Medium |
| >= 4 | High |

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

## Results
The tuned fuzzy system achieved approximately **80% accuracy** on the evaluation dataset.

## Repository Structure
```text
student-stress/
├── data/
├── notebooks/
├── results/
├── README.md
└── requirements.txt
