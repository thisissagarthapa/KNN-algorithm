# Lung Cancer Prediction Using K-Nearest Neighbors

This project implements a K-Nearest Neighbors (KNN) algorithm to predict the presence of lung cancer based on patient features such as age and smoking years. The dataset used for this project contains information about individuals, including their age, years of smoking, and lung cancer diagnosis.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Project Overview

The goal of this project is to classify whether a person has lung cancer based on their age and the number of years they have smoked. The KNN algorithm is used as the primary classification method.

## Dataset

The dataset used in this project is `lung_cancer_data.csv`, which includes the following columns:

- **Age**: Age of the individual.
- **Smoking_Years**: Number of years the individual has smoked.
- **Lung_Cancer**: Target variable (0 = No Lung Cancer, 1 = Lung Cancer).

### Sample Data

| Age | Smoking_Years | Lung_Cancer |
|-----|---------------|-------------|
| 71  | 0             | 0           |
| 34  | 37            | 0           |
| 80  | 12            | 0           |
| 72  | 25            | 1           |
| ... | ...           | ...         |


## Screenshots

![Screenshot (131)](https://github.com/user-attachments/assets/1b551dc6-6b6c-4387-b740-06ebb78e9fec)





![Screenshot (130)](https://github.com/user-attachments/assets/f5a352a6-5181-482c-88a9-4c7136927de5)








## Installation

To run this project, you'll need Python installed along with the following libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn
- mlxtend

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn mlxtend
